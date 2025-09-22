Linear Regression: Predicting Salary Based on Experience

This project applies Linear Regression to predict an employee’s salary based on their years of experience. It demonstrates how a simple machine learning model can capture the relationship between two variables and make accurate predictions.

Project Structure

├── Linear-Regression.ipynb   # Jupyter Notebook with implementation

├── data/                     # (Optional) Folder for dataset

├── README.md                 # Project documentation

Project Overview

Algorithm Used: Linear Regression

Input Feature: Years of Experience

Target Variable: Salary

Goal: Train a regression model to predict salary based on years of experience.

Steps Implemented

Data Preprocessing

Loaded dataset and checked for missing values.

Extracted features (X = YearsExperience) and labels (y = Salary).

Exploratory Data Analysis (EDA)

Visualized scatter plot to identify the trend.

Checked correlation between experience and salary.

Model Training

Used scikit-learn’s LinearRegression model.

Trained the model on training data.

Model Evaluation

Predicted salary values for test data.

Plotted regression line over data points.

Measured accuracy using R² score.

Prediction

Tested with new values of years of experience.

Technologies Used

Python

Libraries:

Pandas & NumPy (Data Handling)

Matplotlib & Seaborn (Visualization)

Scikit-learn (Linear Regression Model)

Visualization Example

Scatter plot of salary vs years of experience

Regression line showing predicted salary trend
