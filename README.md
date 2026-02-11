# House Price Prediction using Linear Regression

Project Overview

A real estate company operating across multiple cities wants to automate its house pricing process. Instead of manually estimating property values, the company aims to build a Machine Learning model that can accurately predict house prices based on historical housing data. This project implements a Linear Regression model to predict house prices using 13 property-related features including physical attributes, location details, and construction characteristics.

Dataset Description

- The dataset contains 13 features.
- Each row represents one residential house.
- Features include physical attributes, location details, and construction-related information.
- Target variable: House Price.

Objective

To build a supervised machine learning regression model that:
-Analyzes housing data.
-Performs necessary preprocessing.
-Trains a Linear Regression model.
-Evaluates model performance using standard regression metrics.

⚙️ Project Workflow

1. Data Loading
Loaded the dataset using pandas and inspected its structure.

2. Exploratory Data Analysis (EDA)
Analyzed summary statistics, checked missing values, and examined feature relationships.

3. Data Preprocessing
Handled missing values and prepared numerical features for modeling.

4. Train-Test Split
Split the dataset into training and testing sets for unbiased evaluation.

5. Model Training
Trained a Linear Regression model using scikit-learn.

6. Model Evaluation
Evaluated performance using:
-Mean Absolute Error (MAE)
-Root Mean Squared Error (RMSE)
-R² Score

Model Performance

The Linear Regression model was able to capture the relationship between housing features and sale price effectively. Evaluation metrics indicate the model provides a reasonable predictive baseline for house pricing.

Technologies Used:

Python
NumPy
Pandas
Scikit-learn

Learning Outcomes:

Practical implementation of regression modeling.
Understanding of data preprocessing pipeline.
Experience with real-world ML workflow.
Model evaluation and performance interpretation.

📌 This project is part of my Machine Learning portfolio and preparation for open-source ML contributions.
