There are two notebooks in this repository: 
1. EDA - This notebook focuses on plotting the various features and creates the final modeling dataset which includes test and train.
2. Tabular_MLP_Classifier - this notebook defines the MLP class and several helper functions that help me tune the final model. It also features a grid search cross validation to help me choose the best model.

To run the code is pretty straightforward. First run the EDA notebook in entirety. You will need to modify the location where the final dataset is saved to. Next run Tabular_MLP_Classifier. You can skip the training iterations and jump to the model predictions section to go directly to scoring the test dataset. Model output is written to the MLP subfolder in the repository head.

Package Versions:

IPython==8.30.0
PIL==11.1.0
argparse==1.1
astroid==3.3.8
asttokens==3.0.0
bottleneck==1.4.2
charset_normalizer==3.3.2
cloudpickle==3.0.0
colorama==0.4.6
comm==0.2.1
csv==1.0
ctypes==1.1.0
dateutil==2.9.0.post0
debugpy==1.8.11
decimal==1.70
decorator==5.1.1
defusedxml==0.7.1
dill==0.3.8
executing==0.8.3
filelock==3.17.0
gmpy2==2.2.1
ipaddress==1.0
ipykernel==6.29.5
jedi==0.19.2
joblib==1.4.2
json==2.0.9
jupyter_client==8.6.3
jupyter_core==5.7.2
logging==0.5.1.2
lxml==5.3.0
lz4==4.3.2
mkl==2.4.0
mpmath==1.3.0
networkx==3.4.2
numexpr==2.10.1
numpy==2.1.3
openpyxl==3.1.5
packaging==24.2
pandas==2.2.3
parso==0.8.4
pickleshare==0.7.5
platform==1.0.8
platformdirs==4.3.7
prompt_toolkit==3.0.43
psutil==5.9.0
pure_eval==0.2.2
pyarrow==19.0.0
pydevd==3.2.3
pygments==2.19.1
pytz==2024.1
re==2.2.1
scipy==1.15.3
six==1.17.0
sklearn==1.6.1
socketserver==0.4
stack_data==0.2.0
sympy==1.13.3
threadpoolctl==3.5.0
torch==2.7.1+cpu
tornado==6.5.1
tqdm==4.67.1
traitlets==5.14.3
typing_extensions==4.12.2
wcwidth==0.2.5
zlib==1.0
zmq==26.2.0
zstandard==0.23.0