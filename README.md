# Fraud Detection in Financial Transactions

## Project Objective

The objective of this project is to analyse patterns associated with fraudulent financial applications and develop a machine learning-based fraud detection framework. Through exploratory data analysis and predictive modelling, the project aims to identify key factors contributing to fraudulent behaviour and support risk management decisions.

---

## Data Source Acknowledgement

Dataset Used:
Bank Account Fraud Dataset (NeurIPS 2022)

Source:
https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022

All credit for data collection and preparation belongs to the original dataset authors.

---

## Dataset Description

The dataset contains customer-level and application-level information used for fraud detection.

Target Variable:

- fraud_bool
  - 0 = Legitimate Application
  - 1 = Fraudulent Application

Important Features:

- credit_risk_score
- proposed_credit_limit
- customer_age
- income
- employment_status
- housing_status
- behavioural indicators

The dataset is highly imbalanced, reflecting real-world fraud detection scenarios.

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

- Fraud vs Non-Fraud Comparison
- Target Class Distribution
- - Feature Distribution Analysis
- Correlation Analysis
- Pair Plot Analysis
- Missing Value Analysis
