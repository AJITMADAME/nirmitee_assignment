# Microfinance Loan Default Prediction
## Problem Statement
A microfinance institution (MFI) is collaborating with a telecommunications company to offer micro-loans to low-income families. The goal is to predict whether a customer will pay back the loan within 5 days, based on historical transaction data. The data contains customer behavior and mobile recharge details to predict if the customer is a defaulter (Label '0') or a non-defaulter (Label '1').

## Objective
The objective of this project is to build a machine learning model that predicts the likelihood of loan repayment for each transaction. A prediction of 1 indicates the customer has repaid the loan, and a prediction of 0 indicates the customer has not repaid the loan (defaulted).

## Dataset
The dataset contains customer behavior features and transaction details. Some important points about the dataset:

Imbalanced Data: Label 1 (non-defaulter) represents approximately 87.5% of the data, while label 0 (defaulter) represents about 12.5%.
Features: The dataset contains various features, including transaction amounts, recharge history, account balance, etc.
No missing values: There are no null values in the dataset, but some unrealistic values and outliers may exist, which need to be handled during the data preprocessing step.
Steps to Build the Model
Data Preprocessing:

## Drop irrelevant or unnecessary columns.
Handle unrealistic values and outliers where applicable.
Normalize/scale numerical features.
Exploratory Data Analysis (EDA):

## Visualize the data to understand distributions and correlations.
Identify imbalances in the data and apply techniques like SMOTE or class weighting to address them.
## Model Building:
Use various machine learning algorithms such as Logistic Regression, XGBoost, etc.
Tune hyperparameters to optimize the model performance.
Evaluate the model using appropriate metrics like accuracy, ROC AUC, precision, recall, etc.

## Model Evaluation:
Perform cross-validation to check for model generalization.
Handle class imbalance using techniques like SMOTE or class-weighted loss functions.
Prediction:
Predict the probability of a customer being a non-defaulter for future loan transactions.

## Model Performance
The best-performing model is selected based on metrics such as ROC AUC, precision, recall, and accuracy. The model is evaluated on the test set and saved for future use in predictions.
