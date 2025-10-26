## 📂 Folder Contents

CarPrice_Assignment.csv → Original dataset

Car_Price_Prediction.ipynb → Jupyter Notebook with full data cleaning, feature engineering, model building, and evaluation

car_price_prediction.py → Python script version of the project (optional)

visualizations/ → Folder containing plots (e.g., Actual vs Predicted prices, Feature Importance)

## 📘 Project Overview

Predicting car prices based on features like engine size, horsepower, brand, fuel type, and car dimensions. The goal was to compare different regression models and understand which features most influence car pricing.

## ⚙️ Key Steps

Data cleaning and preprocessing (brand extraction, encoding, scaling)

Trained multiple models: Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, Gradient Boosting

Evaluated performance using R², RMSE, and MAE

## 📊 Results

Random Forest performed best:

R² = 0.957

RMSE = 1852

MAE = 1285

Key predictors: engine size, horsepower, brand, and curb weight
