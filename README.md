# Car_price_prediction_by_Regression_Elasticnet

Predict car prices using linear regression with the ElasticNet method.

## Description

This project aims to predict car prices based on various features using linear regression in terms of the ElasticNet method.

Usage
Run the main script to execute the project:
elastic_net_car_price_mc.ipynb

Dependencies
The project requires the following libraries:

numpy
pandas
matplotlib
scikit-learn

Dataset Preparation
Load the dataset using pandas.
Preprocess the data by handling missing values and categorical features.
Split the dataset into training and testing sets using train_test_split from scikit-learn.
Model Training
Utilize the ElasticNetCV model from scikit-learn for training.
Perform feature scaling and encoding.
Train the model using the training set.
Model Evaluation
Evaluate the trained model using the following metrics from scikit-learn:

r2_score
mean_squared_error
mean_absolute_error
mean_absolute_percentage_error
