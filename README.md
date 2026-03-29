
# COMPAS Recidivism Risk Analysis

## Purpose of the Analysis
The purpose of this project is to analyze the COMPAS recidivism dataset and evaluate how risk scores predict whether a defendant will reoffend within two years. The analysis also investigates potential disparities across demographic groups such as race, gender, and age.

The workflow includes:
- Data preprocessing and filtering
- Exploratory data analysis
- Logistic regression modeling
- Model evaluation using a confusion matrix
- Fairness analysis using FPR and FNR across racial groups

## Python Libraries Used
The analysis was implemented using the following Python libraries:

- pandas – data manipulation and cleaning
- numpy – numerical computations
- matplotlib – visualization
- seaborn – statistical plotting
- statsmodels – logistic regression modeling
- scikit-learn – confusion matrix and evaluation metrics

Example imports used in the notebook:

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sm
from sklearn.metrics import confusion_matrix

## Instructions for Reproducing the Results

1. Clone the repository

git clone https://github.com/yourusername/yourrepository.git

2. Navigate to the project directory

cd yourrepository

3. Install the required Python libraries

pip install pandas numpy matplotlib seaborn statsmodels scikit-learn

4. Run the Jupyter Notebook

jupyter notebook Lecture_01_alignment.ipynb

Run all cells in the notebook to reproduce the results including:
- Data cleaning
- Logistic regression model
- Confusion matrix
- Fairness analysis by race

## Repository Contents

Lecture_01_alignment.ipynb – Python implementation of the analysis  
README.md – Project documentation

## Author
Prepared for Responsible Machine Learning assignment analyzing fairness in recidivism prediction models.
