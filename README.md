# Car Price Prediction and Recommendation System

## Overview

This project aims to analyze car prices and provide actionable recommendations to car dealers. By leveraging various regression models, we predict car prices based on key features such as odometer reading, year of manufacture, vehicle type, and drivetrain. The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework to ensure a structured and comprehensive approach.

## CRISP-DM Phases

### 1. Business Understanding
- **Objective**: Help car dealers optimize their pricing strategies by understanding the factors that influence car prices.
- **Key Questions**:
  - What features most significantly impact car prices?
  - How can car dealers use this information to set competitive prices?

### 2. Data Understanding
- **Data Collection**: Gathered data from various sources including car listings and sales records.
- **Exploratory Data Analysis (EDA)**: Performed EDA to identify patterns, outliers, and relationships between features.

### 3. Data Preparation
- **Data Cleaning**: Handled missing values, outliers, and inconsistencies.
- **Feature Engineering**: Created new features and transformed existing ones to improve model performance.
- **Data Splitting**: Split the data into training and testing sets.

### 4. Modeling
- **Model Selection**: Evaluated multiple regression models including Linear Regression, Ridge Regression, Lasso Regression, and Random Forest Regressor.
- **Parameter Tuning**: Optimized model parameters using techniques like cross-validation.
- **Model Evaluation**: Assessed model performance using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R^2 Score.

### 5. Evaluation
- **Model Comparison**: Compared the performance of different models to select the best one.
- **Visualization**: Created visualizations to compare model metrics and interpret results.
- **Recommendation**: Provided recommendations based on the best-performing model.

### 6. Deployment
- **Model Serialization**: Serialized the best model using Joblib.
- **API Development**: Developed a Flask API to serve the model for real-time predictions.
- **Monitoring**: Implemented logging and monitoring to track model performance in production.

## Recommendations for Car Dealers

Based on our analysis, we recommend car dealers focus on the following factors to optimize their pricing strategies:

1. **Odometer Reading**: Lower mileage cars tend to sell for higher prices.
2. **Year of Manufacture**: Newer cars generally command higher prices.
3. **Vehicle Type**: Trucks and pickup trucks typically achieve higher sales prices.
4. **Drivetrain**: All-Wheel Drive (AWD) cars tend to sell for higher prices than Front-Wheel Drive (FWD) cars.

