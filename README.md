# Rainfall Prediction Model: An EDA and Machine Learning Approach

## Overview
This project aims to predict rainfall using machine learning techniques. The dataset "Rain in Australia" used in this analysis contains approximately 10 years of daily weather observations from various locations across Australia, obtained from https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

## Files
1- Rainfall_prediction.ipynb

&nbsp;&nbsp; Covers exploratory data analysis (EDA) with data visualizations, data wrangling, preprocessing (including imputing missing data and encoding), outlier handling, scaling, and data splitting. Outputs the preprocessed data to "Preprocessed_Data.csv." Also, includes classification with logistic regression without feature selection.

2- Feature_selection.ipynb

&nbsp;&nbsp; Uses "Preprocessed_Data.csv" for feature selection with logistic regression and random forest classifiers. Compares the results, including various metrics for evaluation.

3- weatherAUS.csv

&nbsp;&nbsp; Dataset used in this project, downloaded from [Kaggle](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package).

4- Preprocessed_Data.csv

&nbsp;&nbsp; Cleaned and preprocessed data from Rainfall_prediction.ipynb.

5- requirements.txt

&nbsp;&nbsp; Includes dependencies for the project. To install dependencies, use: 
  
    pip install -r requirements.txt


## Requirements
Python

Jupyter Notebooks

Dependencies: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, etc.

