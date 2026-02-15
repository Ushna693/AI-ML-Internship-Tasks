# AI-ML-Internship-Tasks

This repository contains all tasks completed during my Machine Learning and Artificial Intelligence Internship.

## Task 1: Iris Dataset Analysis

### Objective:
The goal of this task is to explore and visualize the Iris dataset to understand feature relationships and distributions.

### Dataset Used:
Iris dataset (loaded using seaborn)

### Steps Performed:

Loaded dataset using pandas

Checked shape, columns, and summary statistics

Created scatter plots to see relationships

Used histograms to see data distribution

Used boxplots to detect outliers

### Key Findings:

Petal length and petal width show strong relationship

Data is well distributed with few outliers

Species are clearly separable using petal features

## Task 2: Stock Price Prediction

### Objective:
The goal of this task is to predict the next day's closing stock price using historical data.

### Dataset Used:
Apple stock data retrieved using yfinance

### Features Used:
Open, High, Low, Volume

### Target Variable:
Next day Close price

### Model Used:
Linear Regression

### Evaluation Metric:
Mean Absolute Error (MAE)

### Results:
The model achieved an MAE of approximately 3.05, meaning the predictions were on average 3 dollars away from the actual closing price.

### Final Insight:
The model performs reasonably well for short-term prediction, but stock markets are highly volatile, so more advanced models may improve accuracy.
