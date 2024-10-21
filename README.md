# Building Neural Networks with PyTorch
This is the repo for the Building Neural Networks with PyTorch workshop. In the folder you will find:
- the slides: pytorch.pptx
- the notebook used for the PyTorch basics: pytorch.ipynb
- the notebook for the case study: case_study.ipynb

# Setting up an enviroment for the workshop
### 1. Clone the Repository
-	Open VS Code.
-	Clone the repository and choose H:\repos as the destination folder.
### 2. Create a Virtual Environment either via conda or virtualenv
#### 2.1 using a conda env
-   Open de anaconda prompt
-	Create a conda environment using Python 3.11 by running:
- `conda create --name pytorch python=3.11`
-	Activate the conda environment by running:
- `conda activate pytorch`
#### 2.2 using virtualenv
-	Open the terminal
-   Make sure virtualenv is installed, if not you can install it by:
- `pip install virtualenv`
-	In the terminal, create a virtual environment using Python 3.11 by running:
- `python -m virtualenv --python=python311 pytorch`
-   go to the venv directory
- `cd pytorch/scripts`
-	Activate the virtual environment by running:
- `activate`
### 3. Install the Dependencies (Command Line)
-	Finally open a terminal and install the dependencies listed in requirements.txt by running:
- `pip install -r ./requirements.txt`


***

If you have not set the index url for PyPi in DSW, you will notice this by see that a pip install will give a timeout error, than you should run the following commands in the terminal:

- `pip config set global.index-url https://nexus.dnb.nl/repository/pypi/simple`


If you want to sync the repo you should flag the repo as safe:
-	In VS Code, go to Source Control and select Manage Safe Repo.
