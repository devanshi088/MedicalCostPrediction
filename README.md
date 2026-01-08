Medical Insurance Cost Prediction using Machine Learning
Project Overview

This project focuses on predicting medical insurance costs based on demographic and health-related factors such as age, BMI, smoking status, and region. Since the target variable is a continuous numerical value, the problem is treated as a regression task. A Random Forest Regressor is used to model complex, non-linear relationships in the data.

Problem Statement

Medical insurance charges vary significantly due to lifestyle and demographic factors. Accurate cost prediction can support insurance companies in pricing strategies, risk assessment, and financial planning.

Dataset Description

The dataset (insurance.csv) includes the following variables:

Age

Sex

Body Mass Index (BMI)

Number of children

Smoking status

Region

Charges (target variable)

Machine Learning Approach

Problem Type: Regression

Target Variable: Charges

Features: Age, BMI, children, sex, smoker, region

Tools and Technologies

Python

pandas

NumPy

scikit-learn

Data Preprocessing

Loaded data using pandas

Separated features and target variable

Applied one-hot encoding to categorical variables

Split data into training and testing sets

Model Selection

Random Forest Regressor was selected due to its ability to handle non-linear relationships, robustness against overfitting, and strong performance on structured datasets.

Model Evaluation

The model was evaluated using regression metrics:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

The model achieved an MAE of approximately 2559, indicating that predicted medical costs differ from actual costs by about ±2559 on average.

Key Insights

Smoking status, BMI, and age were identified as the most influential features, which aligns with real-world healthcare cost factors.

Conclusion

The Random Forest model demonstrates strong predictive performance for medical insurance cost estimation. The approach can be extended with hyperparameter tuning, advanced ensemble models, or deployment for real-world use.
