# Customer Churn Prediction

## Problem Statement
Predict which telecom customers are likely to churn
before it happens, helping companies retain customers.

## Dataset
- Source: Kaggle — Telco Customer Churn
- Rows: 7,043 | Features: 21

## Tech Stack
Python, Pandas, Scikit-learn, Seaborn,
Matplotlib, SMOTE, Joblib

## Steps
1. Data Cleaning (Hidden null detection, TotalCharges fix)
2. Exploratory Data Analysis
3. Preprocessing using Pipeline and ColumnTransformer
4. SMOTE for class imbalance handling
5. Logistic Regression with GridSearchCV
6. Model Evaluation

## Results
- Recall (Churn Class): 79%
- ROC-AUC Score: 84%
- Cross-Validated F1 Score: 76%

## Key Learning
For imbalanced classification, F1 Score and
Recall matter more than plain Accuracy.
