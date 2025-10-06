# Loan Interest Rate Prediction and Analysis

## Project Overview

This project analyzes the factors influencing Peer-to-Peer (P2P) loan interest rates and develops a simple, interpretable predictive model. The primary goal is to identify which customer and loan characteristics have the most significant impact on the interest rate, which can be valuable for personalizing loan offers and reduce risk.

## Data Source

The analysis is based on the **Bondora P2P Loan Data** dataset, which can be found on [Kaggle] (https://www.kaggle.com/datasets/marcobeyer/bondora-p2p-loans/data).

## Methodology

The analysis follows a standard data science pipeline focused on statistical inference:

1.  **Data Acquisition & Cleaning:** Initial cleaning, handling missing values, and preparing the raw dataset for analysis.
2.  **Exploratory Data Analysis (EDA):** Visualizing key financial and personal features (e.g., age, loan amount, monthly income) and assessing their correlation with the target variable: **Interest Rate**.
3.  **Feature Engineering & Selection:** Transforming categorical features (creating dummy variables) and using statistical techniques to select the most statistically significant predictors.
4.  **Model Building (OLS Regression):** Employing an **Ordinary Least Squares (OLS) regression model** using the `statsmodels` library to quantify the linear relationship between the selected features and the Interest Rate. This approach prioritizes model interpretability.

## Key Findings

* The analysis confirmed that both **financial characteristics** (like loan amount and income) and certain **personal/behavioral factors** (such as applicant age and the specific day of the month the loan was requested) significantly influence the final interest rate.

## Future Work
Future analyses could explore each feature separately to better understand its individual effect on interest rates and improve model accuracy.  

## 🧩 Technologies Used
Python | Pandas | Matplotlib | Seaborn | Statsmodels | Scipy | Jupyter Notebook  
