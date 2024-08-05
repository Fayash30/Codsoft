# SMS Spam Detection

This project aims to build a machine learning model that can classify SMS messages as spam or ham. It utilizes a logistic regression model trained on a dataset of SMS messages.

## Dataset

The dataset used for this project is the "spam.csv" file, which contains a collection of SMS messages labeled as either spam or ham.

## Dependencies

The following libraries are required to run this project:

- numpy
- pandas
- scikit-learn

## Preprocessing

The following preprocessing steps are performed on the dataset:

- Replacing null values with empty strings
- Renaming columns for clarity
- Removing duplicate entries
- Encoding the labels (spam: 0, ham: 1)

## Feature Extraction

The TfidfVectorizer is used to convert the text messages into numerical feature vectors. This process involves:

- Removing stop words
- Converting text to lowercase
- Calculating the TF-IDF values for each word

## Model Training

A logistic regression model is trained on the preprocessed and feature-extracted data.

## Evaluation

The trained model is evaluated on a test set using the accuracy score metric.

## Prediction

The project includes a simple predictive system that takes an SMS message as input and classifies it as spam or ham.
