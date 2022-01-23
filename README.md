# LIGHTHOUSE
This is the repository for the results presented in our manuscript. Please see the <a href='https://github.com/Shimizu-group/LIGHTHOUSE/blob/main/DEMO.ipynb'>DEMO.ipynb</a> file.

Dependencies:
Python Anaconda distribution, PyTorch, RDKit, subword-nmt
## Setup environments
### Virtual enrionment
conda create -n LIGHTHOUSE_demo -y

### Install dependencies
conda install pytorch==1.9.0 -c pytorch
conda install matplotlib
conda install scikit-learn
conda install -c rdkit rdkit=2021.03.4
conda install -c conda-forge jupyterlab

pip install subword-nmt==0.3.7
### Clone this repository
git clone 
## Basic Usage
### Initialization
LIGHTHOUSE.setups()
### Predict confidence score
LIGHTHOUSE.predict_confidence (chemical, protein)
### Predict interaction score
LIGHTHOUSE.predict_interaction (chemical, protein)
