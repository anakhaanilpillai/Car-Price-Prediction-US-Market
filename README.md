# Car-Price-Prediction-US-Market


Project Overview

This project models car prices based on various independent variables to help a Chinese automobile company enter the US market. The analysis includes identifying significant variables that influence car prices and creating regression models to predict prices accurately. The insights will guide the company in designing competitive car models and formulating pricing strategies.


---

Dataset

Source: Market survey data of various car types in the American market.

Link to Dataset: Download Here

Target Variable: price

Features: Various attributes such as car brand, engine type, horsepower, etc.



---

Key Objectives

1. Determine the significant factors affecting car prices.


2. Develop predictive models using:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regressor



3. Evaluate and compare model performance.


4. Perform hyperparameter tuning to optimize model performance.


5. Provide actionable business insights.




---

Implementation Steps

1. Data Preprocessing

Handle missing values and outliers.

Encode categorical variables.

Scale numerical features.



2. Train-Test Split

Split data into training (80%) and testing (20%) sets.



3. Model Building

Train and test five regression models.



4. Model Evaluation

Compare models based on R-squared, MSE, and MAE.



5. Feature Importance Analysis

Identify top factors influencing prices using tree-based models.



6. Hyperparameter Tuning

Use GridSearchCV to fine-tune the best-performing model.





---

Project Files

Jupyter Notebook: Car_Price_Prediction.ipynb

Dataset: cars_dataset.csv

README.md: This file for project documentation.



---

Setup and Usage

Prerequisites

Python 3.7 or above

Libraries: pandas, numpy, scikit-learn, matplotlib, `



