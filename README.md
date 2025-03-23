Project Documentation: PowerPulse

1️⃣ Introduction

PowerPulse is a machine learning project designed to forecast household energy consumption based on historical electricity usage data. It leverages multiple regression models to analyze and predict power consumption trends.

2️⃣ Dataset Overview

Source: UCI Machine Learning Repository

Main Target Variable: Global Active Power

Features Used:

Datetime (converted to hour, weekday, month)

Global Intensity

Sub-metering 1, 2, and 3

Rolling Averages (7-day and 14-day moving averages)

3️⃣ Model Development

Algorithms Used:

Linear Regression

Random Forest

Gradient Boosting

Feature Engineering:

Extracted time-based features (hour, weekday, month)

Applied rolling averages to capture trends

Scaled numerical data using StandardScaler

Performance Metrics

Linear Regression

RMSE: 0.1237

MAE: 0.0942

R² Score: 0.9848

Random Forest

RMSE: 0.0425

MAE: 0.0287

R² Score: 0.9982

Gradient Boosting

RMSE: 0.0440

MAE: 0.0306

R² Score: 0.9981

Random Forest was selected as the final model due to superior performance.
