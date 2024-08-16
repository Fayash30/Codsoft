# Customer Churn Prediction

This repository contains a Jupyter Notebook that demonstrates customer churn prediction using machine learning. The goal is to build models that can predict whether a customer is likely to leave a bank or financial institution.

## Dataset

The dataset used in this analysis is the [Bank Customer Churn Prediction](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction). This dataset contains information about bank customers, including demographics, account details, and whether they churned (left the bank).

## Steps

1. **Data Loading and Preprocessing:**
   - Load the dataset and remove irrelevant columns.
   - Handle categorical variables using one-hot encoding.

2. **Exploratory Data Analysis (EDA):**
   - Explore the distribution of the 'Exited' variable.
   - Analyze correlations between features and the target variable.

3. **Model Building and Evaluation:**
   - Split the data into training and testing sets.
   - Scale numerical features using StandardScaler.
   - Train Logistic Regression and Random Forest Classifier models.
   - Evaluate model performance using metrics like accuracy, F1-score, precision, and recall.
   - Generate confusion matrices.

4. **Prediction on a Single Observation:**
   - Demonstrate how to use the trained model to predict churn for a new observation.

## Requirements

- Python 3.x
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn


## Results

The notebook provides a comparison of the performance of Logistic Regression and Random Forest Classifier models. The results are summarized in a DataFrame and visualized using confusion matrices.
