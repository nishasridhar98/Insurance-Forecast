# Insurance Forecast 
   To accurately predict the medical insurance costs of an individual.
   
# Install
This project requires python 3.6 or higher versions of python, along with these libraries :
* [Numpy](https://www.numpy.org)
* [Pandas](https://pandas.pydata.org)
* [Matplotlib](https://matplotlib.org)
* [scikit-learn](https://scikit-learn.or/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](https://jupyter.org/)

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has 
the above packages and more included.

# Dataset
   The dataset is obtained from Kaggle.Here is the link,
   https://www.kaggle.com/mirichoi0218/insurance
   
# Description of the repository
This repository contains 2 notebooks
  1. Linear Regression-Insurance Dataset.ipynb: 
      This notebook contains implementation of the dataset using Multivariate Linear Regression.
      
  2. Linear Regression with SKlearn-Insurance Dataset.ipynb:
      This notebook contains Scikit-learn implementation using Multivariate Linear Regression

# Run
In the anaconda promt, navigate to the top-level project directory and run one of the following commands:
      
      jupyter notebook "Linear Regression-Insurance Dataset.ipynb"
      
      jupyter notebook "Linear Regression with SKlearn-Insurance Dataset.ipynb"
      
This will open the Jupyter Notebook software and project file in your browser.


# Attribute information
* age: age of primary beneficiary

* sex: insurance contractor gender, female, male

* bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of        body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

* children: Number of children covered by health insurance / Number of dependents

* smoker: Smoking

* region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

# Output Variable( Desired Target)
  Charges: Individual medical costs billed by health insurance
  
# Models Trained 
  | Training Model  | Root mean squared error |
  | ----------------| ------------------------|
  | Multivariate Linear Regression | 0.075   |
  | Using Sklearn                  | 0.087   |
