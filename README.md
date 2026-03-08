# My-Portfolio
A curated collection of my Data Science and Machine Learning projects — showcasing skills in data analysis, feature engineering, and model development.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🔩 1. Metal Surface Defect Classification (Deep Learning)

📁 Folder: Metal-Surface-Defect-Classification

Goal:
Build a deep learning model to automatically classify different types of metal surface defects using image data. The objective is to assist automated quality inspection in manufacturing environments by detecting defects from surface images.

🎯 Objectives

-Develop a computer vision model capable of identifying different metal defects
-Understand visual characteristics of manufacturing defects
-Build and train a Convolutional Neural Network (CNN)
-Evaluate classification performance across defect categories
-Visualize model predictions and performance metrics

🧩 Dataset

Source: NEU Metal Surface Defect Dataset from Kaggle

Defect Classes:

-Crazing
-Inclusion
-Patches
-Pitted Surface
-Rolled-in Scale
-Scratches

Each class contains grayscale images of metal surfaces captured during industrial inspection processes.

Key Steps:

-Image loading and preprocessing
-Image resizing and normalization using torchvision transforms
-Dataset preparation using ImageFolder
-Creation of training and testing data loaders
-Design and implementation of a custom Convolutional Neural Network (CNN)
-GPU-enabled model training using PyTorch
-Model evaluation on test data
-Visualization of predictions and classification performance
-Generation of confusion matrix for model evaluation

Highlights:

-Built a custom CNN architecture for multi-class defect classification
-Used PyTorch DataLoader pipeline for efficient batch training
-Automated image preprocessing and transformation pipeline
-Visualized sample predictions and classification results
-Evaluated model performance using accuracy and confusion matrix

🧾 Skills used:
Python, PyTorch, Computer Vision, Deep Learning, CNNs, NumPy, Matplotlib, Scikit-learn

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 2. 📞Telecom Customer Churn Prediction

📁 Folder:Customer Churn Prediction

Goal:
Build a machine learning model to predict customer churn for a telecom company and identify the key factors influencing customer retention.

🎯 Objectives

-Analyze customer behavior and service usage patterns

-Handle class imbalance and optimize recall for churn detection

-Compare multiple machine learning models

-Identify key factors driving churn

🧩 Dataset

-Source: Telco Customer Churn Dataset (Kaggle)

Key Features:

-tenure, MonthlyCharges, Contract, PaymentMethod, InternetService

-Derived features like avg_charge_per_tenure, tenure_monthlycharges, is_long_term

Key Steps:

-Data loading, exploration, and visualization of churn distribution

-Handling missing values and data type conversions

-Encoding categorical variables using Label Encoding and One-Hot Encoding

-Feature engineering: created tenure-based and interaction features

-Balancing data using SMOTE to address class imbalance

-Data scaling using StandardScaler

-Model comparison: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting

-Hyperparameter tuning using GridSearchCV for Gradient Boosting

-Model evaluation using Accuracy, ROC-AUC, Classification Report, and Confusion Matrix

-ROC Curve and Permutation Importance visualization

Highlights:

-Achieved Test Accuracy = 0.79 and ROC-AUC = 0.844 using tuned Gradient Boosting

-Identified key drivers of churn such as Contract Type, Fiber Optic Internet, Tenure, and Monthly Charges

-Used SMOTE to effectively balance churn vs. non-churn classes

-Visualized Confusion Matrix, ROC Curve, and Top 10 Important Features

🧾 Skills used: Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Imbalanced-learn

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🚗 3. Car Price Prediction

📁 Folder: Car-Price-Prediction

Goal:
Build a machine learning model to predict car prices based on various features such as engine specifications, fuel type, and brand.

Key Steps:

-Data cleaning and preprocessing

-Feature engineering (brand extraction and correction)

-One-hot and target encoding for categorical data

-Model comparison: Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, and Gradient Boosting

-Evaluation using R², MAE, MSE, RMSE and Cross-Validation

-Predicted vs Actual Prices Visualization

-Feature importance visualization

Highlights:

-Achieved R² = 0.956 using Random Forest

-5-Fold Cross-Validation confirmed robust model performance (CV R² mean ≈ 0.887, Std ≈ 0.069) 

-visualized Predicted vs Actual Prices

-Visualized top 10 most influential features

-Compared baseline and regularized regression models


🧾 Skills used: Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib


-------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊Much More Stuff coming soon!

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
 ## 👤 Author:
 ### Madhav Grover
 
 Data Science & Machine Learning Enthusiast

🌐 Connect with Me

📎 LinkedIn:
    https://www.linkedin.com/in/madhav-grover-a126b1226/

📧 Email:
    grovermadhav@gmail.com

💻 GitHub:
    https://github.com/madhavgrover10/My-Portfolio/
    

