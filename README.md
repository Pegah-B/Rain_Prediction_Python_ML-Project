# Rain-Prediction-Project

## Overview
This project aims to predict rainfall using machine learning techniques. The dataset "Rain in Australia" used in this analysis contains approximately 10 years of daily weather observations from various locations across Australia, obtained from https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

## Files
1- Rainfall_prediction.ipynb

Covers EDA, preprocessing, and outlier handling. Outputs "Preprocessed_Data.csv."

Also includes classification with Logistic Regression (No Feature Selection).

2- Feature_selection.ipynb

Uses "Preprocessed_Data.csv" for feature selection with logistic regression and random forest classifiers. Compares results.

3- weatherAUS.csv

Dataset used in this project, downloaded from the above Kaggle link.

4- Preprocessed_Data.csv

Cleaned and preprocessed data from Rainfall_prediction.ipynb.

5- requirements.txt

Includes dependencies for the project. To install dependencies, use: pip install -r requirements.txt


## Requirements
Python

Jupyter Notebooks

Dependencies: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, etc.

