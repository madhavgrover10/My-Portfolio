## 📂 Folder Contents

CarPrice_Assignment.csv → Original dataset

Car_Price_Prediction.ipynb → Jupyter Notebook with full data cleaning, feature engineering, model building, and evaluation

Data Dictionary -carprices.xlsx → Excel file explaining the features present in the CarPrice_Assignment.csv dataset

## 📘 Project Overview

Predicting car prices based on features like engine size, horsepower, brand, fuel type, and car dimensions. The goal was to compare different regression models and understand which features most influence car pricing.

## ⚙️ Key Steps

Data cleaning and preprocessing (brand extraction, encoding, scaling)

Trained multiple models: Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, Gradient Boosting

Evaluated performance using R², RMSE, and MAE

## 📊 Results

Random Forest performed best:

Test Set:

R² = 0.956

RMSE = 1871

MAE = 1287

-5-Fold Cross-Validation: Mean R² = 0.887, Std = 0.069 

Key predictors: engine size, highwaympg, horsepower, brand, and curb weight

##Author:Madhav Grover
