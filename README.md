# SmartKart_Churn_Prediction_ML_Pipeline


A machine learning project that predicts whether a SmartKart customer is likely to churn using Logistic Regression.

## Project Overview

The project uses the `SmartKart_dirty_100_rows.xlsx` dataset containing 100 customer records with intentionally messy data, including missing values, duplicates, invalid entries, and outliers.

The data is cleaned and prepared before training a Logistic Regression model to predict customer churn.

## Features

* Age
* Monthly Spend
* Complaints

Target:

* `0` → No Churn
* `1` → Churn

## ML Workflow

```text
Data Collection → Data Cleaning → Outlier Treatment
        ↓
Feature Selection → Train/Test Split → Standardisation
        ↓
Logistic Regression → Prediction → Model Evaluation
        ↓
Customer Churn Risk Report
```

## Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

The project also analyzes Logistic Regression coefficients to understand which factors are associated with higher or lower churn risk.

## Tech Stack

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab.

## Dataset

`SmartKart_dirty_100_rows.xlsx`

Author
Khushmeet Kaur

Machine Learning | AI | Business Analytics

The dataset is intentionally messy and is used for educational purposes to demonstrate a complete data preprocessing and machine learning pipeline.

## Disclaimer

This project is created for educational purposes. The dataset and predictions should not be treated as a production customer-retention system.
