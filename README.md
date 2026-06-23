# E-Commerce Conversion Prediction

## Project Overview

This project was developed as part of the Summer Analytics 2026 Week 2 Hackathon.

The goal is to predict whether a user will make a purchase on an e-commerce platform based on browsing behavior, demographic information, and historical activity.

---

## Dataset

Files used:

- train.csv
- public_test.csv
- private_test.csv

Target Variable:

- Conversion (0 = No Purchase, 1 = Purchase)

---

## Data Preprocessing

- Missing value imputation using median values
- Ordinal Encoding for categorical variables
- Feature scaling using StandardScaler

---

## Feature Engineering

Created additional features such as:

- Pages_Per_Minute
- Product_Page_Ratio
- Returning_User
- Products_Per_Minute
- Income_Log
- Time_Log
- Pages_Log
- Income_Per_Age
- Pages_x_Time
- Products_x_Time
- Products_Per_Page
- Purchase_History_Score

---

## Model

Model Used:

- Logistic Regression

---

## Results

Public F1 Score:

0.534358

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

---

## Repository Structure

E-Commerce-Conversion-Prediction/
│
├── ecommerce_conversion_prediction.ipynb
├── train.csv
├── public_test.csv
├── private_test.csv
├── submission.csv
└── README.md

---

## Author

Amrit
IIIT Bhagalpur
B.Tech Mechatronics and Automation Engineering