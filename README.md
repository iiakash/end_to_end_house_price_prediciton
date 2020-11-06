## House Price Prediction and Build a Client Facing API using Flask

# This repository contains the project of house price prediction using Linear, Lasso and Decision Tree Regressor.

## Overview

In this project a house price predictor is trained using three different machine learning regression models. In the beginning phase of the project exploratory analysis is done on the dataset to identify the KPIs. After this phase significant data cleaning is done as the data contained a lot of discrepancies. Tasks like handling missing values, outlier detection and removal is done on the dataset to make the data suitable for feeding into the machine learning model. The large part of this project is focused towards data cleaning and pre-processing.

One hot encoding is done to handle the categorical variable present in the data and then the data is fed into the machine learning model. In this project three different regression algorithms are tested with different hyperparameters to find out the best model. For hyperparameter tuning and model selection GridSearchCV is used.

Finally, after the training is done, a client facing web API using Flask server is built to predict the house price.

## Data

The data for this project is taken directly from Kaggle and can be downloaded following this link: https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data

## Dependencies

The dependencies for this project are listed in the requirements.txt file
