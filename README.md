# Credit Card Fraud Detection Data Analysis Project

## Project Objective
The objective of this project is to identify fraudulent credit card transactions using data analysis and machine learning techniques. The project aims to analyze transaction patterns and build a model that can accurately distinguish between legitimate and fraudulent activities.

## DataSet Used
- <a href="https://github.com/Priyanshu25482/Credit-Card-Fraud-Detection-/blob/main/synthetic_fraud_dataset1.csv">DataSet</a>

## Questions (KPIs)
- What percentage of total transactions were identified as fraudulent?
- Which transaction type has the highest fraud occurrence rate?
- How accurately can the model distinguish between legitimate and fraudulent transactions?
- Which features (Transaction Amount, Location, Device Type, etc.) contribute most to fraud detection?
- Which machine learning model achieved the best performance based on Accuracy, Precision, Recall, and ROC-AUC Score?

## Process
1.Data Collection & Understanding
- Imported the credit card transaction dataset and analyzed its structure, data types, missing values, and statistical summary.
2.Data Preprocessing & Feature Engineering
- Handled duplicate records, encoded categorical variables using Label Encoding, removed outliers, and prepared data for modeling.
3.Exploratory Data Analysis (EDA)
- Performed visual analysis to identify fraud patterns, transaction behavior, feature distributions, and class imbalance.
4.Data Balancing & Model Building
- Applied SMOTE to balance fraudulent and non-fraudulent transactions and trained multiple machine learning models such as Logistic  Regression, Decision Tree, Random Forest, XGBoost, SVM, and Isolation Forest.
5.Model Evaluation & Fraud Detection
- Evaluated models using Accuracy, Precision, Recall, Confusion Matrix, and ROC-AUC Score, then selected the best-performing model for fraud prediction and real-time alert generation.

## Jupyter File
