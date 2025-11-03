## 📂 Folder Contents

Telco-Customer-Churn.csv → Original dataset

Telecom_Customer_Churn.ipynb → Complete Jupyter Notebook with EDA, feature engineering, model training, evaluation, and visualization

## 📘 Project Overview

This project focuses on predicting customer churn for a telecom company — identifying which customers are most likely to discontinue their service.
The goal is to support business decision-making by detecting at-risk customers early, reducing churn, and improving customer retention.

## ⚙️ Key Steps

Data Understanding & Cleaning:

Handled missing TotalCharges values, dropped unnecessary identifiers, and ensured proper data types.

Feature Engineering:

Created new variables such as tenure × MonthlyCharges, avg_charge_per_tenure, and is_long_term to capture customer behavior.

Encoding & Scaling:

Applied Label Encoding for binary variables and One-Hot Encoding for multi-category features.

Standardized numeric features using StandardScaler.

Handling Class Imbalance:

Used SMOTE (Synthetic Minority Oversampling Technique) to balance churn vs. non-churn customers.

Model Training & Evaluation:

Trained models: Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.

Tuned the Gradient Boosting model using GridSearchCV (5-fold CV).

Evaluation Metrics:

Accuracy, ROC-AUC, Confusion Matrix, and Classification Report.

Visualization:

Plotted Churn distribution, ROC Curve, and Feature Importance (Permutation Importance).

## 📊 Results

✅ Best Model: Tuned Gradient Boosting Classifier
Metric	 Validation	  Test
Accuracy	   0.81	    0.79
ROC-AUC	     0.86	    0.844

## 🔍 Key Insights

-Customers with Fiber Optic Internet and Month-to-Month contracts are more likely to churn.

=Tenure (how long a customer has been with the company) is a strong indicator of loyalty.

=Tech Support and Online Security availability reduce churn probability significantly.

=The combination of Contract Type, Monthly Charges, and Tenure provides the highest predictive power.

📈 Visuals Included

Churn distribution plot

Confusion matrix heatmap

ROC-AUC curve

Top 10 feature importance (bar chart)

## 🧠 Business Value

The model helps telecom companies:

Identify high-risk churn customers early

Design targeted retention offers

Reduce customer loss and improve revenue predictability

## 🧾 Skills & Tools Used

Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn (SMOTE), Matplotlib, Seaborn, GridSearchCV, Permutation Importance
