# FUTURE_ML_02
Bank Customer Churn Prediction Project
Project Overview

This project aims to predict bank customer churn (whether a customer will leave the bank) using machine learning models. The project includes Exploratory Data Analysis (EDA), feature engineering, model training, evaluation, and exporting prediction outputs for use in Power BI.

Dataset

The dataset used is Churn_Modelling.csv, which contains customer demographic data, bank account statistics, credit behavior, and churn status (Exited).

Main Project Steps

Data Cleaning

Removed irrelevant columns (RowNumber, Surname, CustomerId)

Handled missing values in numerical and categorical variables

Exploratory Data Analysis

Univariate distributions (Age, Balance, CreditScore)

Churn distribution across Gender and Geography

Correlation heatmap

Additional EDA visuals:

Age vs Churn Relationship

Credit Score vs Churn Relationship

Balance vs Churn Boxplots

Modeling

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Evaluation

Metrics used:

Accuracy

Precision

Recall

F1-score

ROC-AUC Score

Feature Importance

Random Forest feature importances plotted (Top 10 features driving churn)

Exporting Outputs for Power BI

Tools Used

Python

Jupyter Notebook

pandas, xgboost, matplotlib, seaborn

Power BI (visual dashboards)

Goal

Help the bank understand customer behavior patterns leading to churn and enable early customer retention strategies.
