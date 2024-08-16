# Credit Card Fraud Detection

This project is a **Credit Card Fraud Detection** system implemented using a Logistic Regression machine learning model. The goal of the project is to detect fraudulent transactions from a dataset of credit card transactions.


## Introduction

Credit card fraud is a significant issue in the financial industry. The purpose of this project is to develop a machine learning model that can accurately detect fraudulent transactions to help minimize financial losses.

## Dataset

The dataset used in this analysis is the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly imbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.

**Features:**
- `Time`: The time elapsed between this transaction and the first transaction in the dataset.
- `V1, V2, ..., V28`: The result of a PCA transformation.
- `Amount`: The transaction amount.
- `Class`: The response variable (1: fraud, 0: not fraud).

## Model

A Logistic Regression model was used for this project. Logistic Regression is a simple yet effective algorithm for binary classification problems, making it well-suited for fraud detection.

**Key Steps:**
1. **Data Preprocessing**: The dataset was scaled using StandardScaler, and missing values were handled appropriately.
2. **Model Training**: The Logistic Regression model was trained on the preprocessed dataset.
3. **Evaluation**: The model was evaluated using accuracy, precision, recall, and F1-score metrics.

## Results

The model achieved the following results:
- **Accuracy on Training data**: _e.g., 94.7%_
- **Accuracy on Testing data**: _e.g., 93.9%_

The high recall indicates that the model effectively identifies fraudulent transactions, which is critical in this context.
