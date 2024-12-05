# Ml_Car_Price_Project

This repository contains a machine learning project focused on predicting car prices using linear regression. The project addresses the business goal of a Chinese automobile company that aims to enter the US market and compete with established US and European counterparts. The company has partnered with an automobile consulting firm to understand the factors influencing car pricing in the American market, which may differ significantly from the Chinese market.

## Problem Description

The Chinese automobile company seeks to gain insights into the factors that impact car pricing in the American market. The key objectives are:

Identify significant variables that play a role in predicting the price of a car.
Assess the effectiveness of these variables in describing the price of a car.

## Business Goal

The ultimate business goal of this project is to build a predictive model that can accurately estimate car prices based on various independent variables. By understanding the relationship between car attributes and pricing, the management can:

Optimize car design and features to align with target price levels. Formulate an effective business strategy tailored to the dynamics of the US market.

## Project Overview

### Data Preprocessing:

Handled missing values by filling numerical columns with their mean and categorical columns with their mode.
Visualized outliers using boxplots and identified outliers using the Z-score method.

### Outlier Handling:

Removed outliers based on Z-scores to clean the dataset for better model performance.

### Skewness Handling:

Applied Box-Cox transformation to reduce skewness in numerical features.

### Feature Encoding:

Utilized One-Hot Encoding to convert categorical variables into a numerical format suitable for regression analysis.

### Model Implementation:

Implemented various regression algorithms including Linear Regression, Decision Tree Regressor, Random Forest Regressor, Gradient Boosting Regressor, and Support Vector Regressor.

### Hyperparameter Tuning:

Performed hyperparameter tuning on the Random Forest model using Grid Search to optimize its performance.

### Model Evaluation:

Compared model performance using metrics such as R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE).

## Results 

The Random Forest model emerged as the best-performing model, demonstrating a significant ability to predict car prices accurately. Hyperparameter tuning further improved its performance metrics.
