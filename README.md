# Internship Tasks Repository

This repository contains the code and documentation for the tasks I completed during my internship. Each task is an independent project that addresses different real-world problems using machine learning techniques.

## Table of Contents

- [Task 1: SMS Spam Detection](#task-1-sms-spam-detection)
- [Task 2: Credit Card Fraud Detection](#task-2-credit-card-fraud-detection)
- [Task 3: Customer Churn Prediction](#task-3-customer-churn-prediction)

---

## Task 1: SMS Spam Detection

This project focuses on building a machine learning model that classifies SMS messages as spam or ham (not spam). It employs a logistic regression model trained on a dataset of SMS messages.

### Key Features:
- **Dataset**: A collection of SMS messages labeled as either spam or ham.
- **Preprocessing**: Handling null values, renaming columns, removing duplicates, and encoding labels.
- **Feature Extraction**: Using TfidfVectorizer to convert text into numerical vectors by removing stop words and calculating TF-IDF values.
- **Model**: Logistic regression is used for classification.
- **Evaluation**: Model evaluated using the accuracy score metric.

[Detailed documentation](./Task1/README.md)

---

## Task 2: Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using logistic regression. The dataset used is highly imbalanced, with fraudulent transactions accounting for only 0.172% of the total.

### Key Features:
- **Dataset**: Transactions made by European cardholders, including PCA-transformed features.
- **Model**: Logistic regression for binary classification (fraud vs. non-fraud).
- **Preprocessing**: StandardScaler for feature scaling.
- **Evaluation**: Metrics such as accuracy, precision, recall, and F1-score were used to evaluate model performance.

[Detailed documentation](./Task2/README.md)

---

## Task 3: Customer Churn Prediction

This project focuses on predicting customer churn (whether a customer will leave a bank) using logistic regression and random forest classifiers.

### Key Features:
- **Dataset**: Customer demographic and account data from a bank.
- **Preprocessing**: One-hot encoding for categorical features, and feature scaling using StandardScaler.
- **Models**: Logistic regression and random forest classifiers.
- **Evaluation**: Accuracy, F1-score, precision, recall, and confusion matrices for model comparison.

[Detailed documentation](./Task3/README.md)

---

## Requirements

- Python 3.x
- Required libraries for all tasks:
  - numpy
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn

