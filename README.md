[![Shipping files](https://github.com/neuefische/ds-hands-on-ml/actions/workflows/workflow-02.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-hands-on-ml/actions/workflows/workflow-02.yml)
# Hands on Machine Learning

This repo contains notebooks explaining different machine learning techniques every Data Scientist should know. 

Notebook [Scaling & Hyperparameter Tuning](1_Scaling_Hyperparameter_Tuning.ipynb) will show you two different ways to scale your data and tune the hyperparameter of your models. Furthermore it will introduce the concept of cross-validation. 

In the notebook [Exercise_Machine_Learning](2_Exercise_Machine_Learning.ipynb) you will have the chance to practice what you have seen in the previous notebooks, but first you will need to download the data from the database.


## Set up your Environment

Please make sure you have forked the repo and set up a new virtual environment. For this purpose you can use the following commands:

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the hands-on ml notebooks.

*Note: If there are errors during environment setup, try removing the versions from the failing packages in the requirements file. M1 shizzle.*

### **`macOS`** type the following commands : 


- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :

  ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

The data used in this notebook is saved in a data folder. 


