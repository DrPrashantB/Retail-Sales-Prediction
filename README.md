# Retail Sales Prediction Project

## Table of Contents
1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Data Collection](#data-collection)
4. [Data Preprocessing](#data-preprocessing)
5. [Exploratory Data Analysis](#exploratory-data-analysis)
6. [Feature Engineering](#feature-engineering)
7. [Model Development](#model-development)
8. [Model Evaluation](#model-evaluation)
9. [Hyperparameter Tuning](#hyperparameter-tuning)
10. [Deployment](#deployment)
11. [Results](#results)
12. [Conclusion](#conclusion)
13. [Future Work](#future-work)
14. [References](#references)
15. [Appendix](#appendix)


---
## Introduction
Retail sales prediction is crucial for inventory management, financial planning, and marketing strategies. This project aims to build a robust model to predict daily sales using historical sales data.

## Problem Statement
The goal is to forecast daily sales for a retail store using historical sales data, considering factors like customer behavior, product attributes, and external influences.

## Data Collection
- **Dataset**: Customer Shopping Dataset
- **Source**: [Kaggle](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset/data)
- **Description**: 
  This dataset contains shopping information from 10 different shopping malls between 2021 and 2023. The dataset creater has gathered data from various age groups and genders to provide a comprehensive view of shopping habits in Istanbul. The dataset includes essential information as given below:

  **Content**

  **Attribute Information**:
  - **invoice_no**: Invoice number. Nominal. A combination of the letter 'I' and a 6-digit integer uniquely assigned to each operation.
  - **customer_id**: Customer number. Nominal. A combination of the letter 'C' and a 6-digit integer uniquely assigned to each operation.
  - **gender**: String variable of the customer's gender.
  - **age**: Positive Integer variable of the customers age.
  - **category**: String variable of the category of the purchased product.
  - **quantity**: The quantities of each product (item) per transaction. Numeric.
  - **price**: Unit price. Numeric. Product price per unit in Turkish Liras (TL).
  - **payment_method**: String variable of the payment method (cash, credit card or debit card) used for the transaction.
  - **invoice_date**: Invoice date. The day when a transaction was generated.
  - **shopping_mall**: String variable of the name of the shopping mall where the transaction was made.

## Data Preprocessing
- Handling missing values.
- Managing outliers.
- Converting data types.
- Normalizing/standardizing data.

## Exploratory Data Analysis
- Visualization of sales trends.
- Analysis of seasonal patterns.
- Customer segmentation insights.

## Feature Engineering
- Creating features for date (day, month, year).
- Generating lagged features for time series analysis.
- Encoding categorical variables.

## Model Development
- Models tested: Linear Regression, Decision Tree, Random Forest, LSTM.
- Implementation details and code snippets provided.

## Model Evaluation
- Metrics: RMSE, MAE.
- Comparison of model performances.

## Hyperparameter Tuning
- Techniques: Grid Search, Random Search.
- Tuning results and optimal parameters.

## Deployment
- Deployment using Flask.
- Creating an API for real-time sales prediction.

## Results
- Final model performance metrics.
- Visualizations of actual vs. predicted sales.

## Conclusion
- Summary of findings.
- Impact on retail forecasting.

## Future Work
- Suggestions for model improvement.
- Potential extensions and additional features.

## References
- [Customer Shopping Dataset](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset/data) by Mehmet Tahir Aslan on Kaggle. All credits for the dataset go to the original author.
- Relevant research papers and articles.

## Appendix
- Additional code snippets and data samples.


