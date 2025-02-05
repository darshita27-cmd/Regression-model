# Regression-models
Using Linear regression, Polynomial, Ridge & Lasso Regression

## Overview

This project implements a housing price prediction model using Polynomial Regression, Ridge Regression, and Lasso Regression. The dataset used contains various features like area, bedrooms, bathrooms, and stories, which are used to predict house prices.

## Features

#### Data Preprocessing 
Handles missing values and normalizes features.

#### Visualization
Uses Seaborn and Matplotlib for exploratory data analysis.

#### Model Training
Implements Linear Regression, Polynomial Regression (degree=5), Ridge Regression, and Lasso Regression.

#### Hyperparameter Tuning
Finds the best regularization parameters for Ridge and Lasso using RidgeCV and LassoCV.

#### Model Evaluation
Uses Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score to measure performance.

## Dependencies

Ensure you have the following libraries installed:
pandas
numpy
matplotlib
seaborn
sklearn


### Visualization of Predictions
Plots actual vs. predicted prices for each model

![image](https://github.com/user-attachments/assets/9e4eb7c2-7d89-4f10-bc00-aae4965dab0e)

## Conclusion

Linear Regression provides a baseline model.

Polynomial Regression improves performance but risks overfitting.

Ridge Regression helps control overfitting by penalizing large coefficients.

Lasso Regression further improves by selecting important features.
