# House Price Prediction

This is a machine learning project to predict the prices of houses based on various features such as the area of the house, the number of bedrooms and bathrooms, the number of stories, the presence of amenities like a main road, guest room, basement, hot water heating, air conditioning, parking, preferred area, and the furnishing status.

## Table of Contents

- [Problem Statement](#problem-statement)
- [Data Collection](#data-collection)
- [Data Checks and Exploratory Data Analysis](#data-checks-and-exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Model Training and Selection](#model-training-and-selection)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)

## Problem Statement

The goal of this project is to build a machine learning model that accurately predicts house prices using various features. The dataset used for this project is sourced from Kaggle.

## Data Collection

The dataset used for this project can be found on Kaggle [here](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset). The dataset contains information about houses and their corresponding prices.

## Data Checks and Exploratory Data Analysis

In this section, we performed various data checks and explored the dataset to understand its structure and characteristics. We checked for missing values, duplicates, data types, and the number of unique values for each column. We also visualized the data using various plots and analyzed the distribution of the target variable (house prices) and its correlation with other features.

## Data Preprocessing

Before training the machine learning models, we performed data preprocessing steps, which included dealing with outliers and feature engineering. We handled outliers in the 'price' and 'area' columns using the IQR method. Categorical features were one-hot encoded to convert them into numerical form for model training.

## Model Training and Selection

We trained multiple machine learning models on the preprocessed data. The models used include Linear Regression, Lasso Regression, Ridge Regression, K-Neighbors Regressor, Decision Tree Regressor, Random Forest Regressor, XGBoost Regressor, CatBoosting Regressor, and AdaBoost Regressor. We evaluated each model's performance using R2 score as the metric.

## Model Evaluation

The R2 score was used to evaluate the performance of each model. The model with the highest R2 score was chosen as the best model for house price prediction.

## Conclusion

In this project, we successfully built a machine learning model to predict house prices based on various features. The best-performing model was Linear Regression with an R2 score of 71.01 The model can be used to predict house prices and assist in making informed decisions in the real estate market.

