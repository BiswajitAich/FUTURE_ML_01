# 📊 **Sales Forecasting using Machine Learning**

[![Click for CODE](https://img.shields.io/badge/Click%20for%20CODE-Python-blue?style=for-the-badge&logo=python&logoColor=ffdd54)](/FUTURE_ML_01-Time_Series.ipynb)

## Project Overview

This project was developed as part of the **Future Interns Machine Learning Internship Program (2026)**. [🔗](https://futureinterns.com/machine-learning-task-2-2026/)

Project focuses on predicting future sales using historical sales data and machine learning techniques.
The goal is to learn how time-series data can be transformed into a supervised learning problem using feature engineering and regression models.

The model analyzes past sales patterns and predicts upcoming sales values based on trends and historical behavior.

___

## 🎯 Objective

- Analyze historical sales data
- Perform time-based feature engineering
- Train a machine learning regression model
- Predict future sales values
- Evaluate prediction performance using standard metrics

___

## 📂 Dataset Features

The dataset contains daily sales records with engineered features:

| Feature |	Description |
|---|---|
| Order Date | Date of sale |
| Sales	| Target variable (sales amount) |
| Year |	Extracted from date |
| Month |	Extracted from date | 
| Day |	Extracted from date |
| DayOfWeek |	Day index (0–6) |
| lag_1 |	Previous day sales |
| lag_7 |	Sales from 7 days before |

___

## Feature Engineering

To capture temporal patterns, the following steps were performed:

- Converted date column into datetime format
- Extracted calendar features:
- - Year
  - Month
  - Day
  - Day of Week

- Created lag features:
- - lag_1 → previous day sales
  - lag_7 → weekly dependency

- Removed missing values created due to lag shifting
___

## Model Used

Regression Model (Machine Learning based)

- Trained on historical sales data
- Learned trend and seasonal behavior from lag features

___

## Evaluation Metrics

Model performance was evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

Results
MAE  : 1698.07
RMSE : 2376.57

These metrics indicate how far predictions deviate from actual sales values on average.

___

## Prediction Goal

The model learns patterns such as:

👉 Using previous sales data to predict next day's sales.

Example:
- Today’s and past week’s sales → Predict tomorrow’s sales.

___
## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (for visualization)
- Jupyter Notebook

___

## 👨‍💻 Author

Biswajit Aich
B.Tech CSE | Machine Learning Enthusiast

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BiswajitAich)
[![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/biswajitaich)

___

Thank you 
Please give review.
