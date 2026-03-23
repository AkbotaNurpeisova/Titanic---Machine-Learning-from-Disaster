Project Overview
This repository contains my solution for the classic Kaggle Titanic competition. The goal is to predict which passengers survived the Titanic shipwreck using machine learning models based on data like age, sex, passenger class, and more.

Key Objectives
Perform Exploratory Data Analysis (EDA) to find patterns.

Handle missing values (Imputation) and clean the dataset.

Transform categorical data into numerical format (Feature Encoding).

Compare multiple classification models to find the most accurate one.

Technical Workflow
1. Data Preprocessing

Handling Missing Values: Filled missing Age and Fare data using the median, and Embarked using the mode.

Feature Engineering: Dropped irrelevant columns like Cabin, Name, and Ticket to reduce noise.

Categorical Encoding: Converted gender and port of embarkation into numerical values using One-Hot Encoding.


2. Model Comparison

I implemented and compared three different algorithms using scikit-learn:

Logistic Regression: A baseline linear model for binary classification.

Decision Tree: A non-linear model that splits data based on feature importance.

Random Forest: An ensemble method that uses multiple decision trees to improve accuracy and reduce overfitting.
