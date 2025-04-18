# ChurnSense-Predicting-Customer-Attrition-with-Business-Impact-Simulation

## Project Overview

ChurnSense is a complete analysis of telecom customer churn using real-world data. The goal isn’t just to predict who’s going to leave — it’s to understand why, and simulate how much money a business could save if it acted earlier. It’s built the way a data analyst would actually use it inside a company: clean logic, meaningful visuals, and business impact.

## Dataset

This project uses the [Telco Customer Churn dataset from Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). It contains information on over 7,000 customers, including:

- Demographics (gender, senior citizen status, dependents)
- Services used (internet, phone, streaming)
- Account details (contract type, tenure, payment method)
- Churn status (whether the customer left or stayed)

## What’s in This Project

Here’s what the notebook walks through:

- **Data cleaning** – fixing issues like incorrect data types and missing values
- **Exploratory analysis** – breaking down churn patterns using visual insights
- **Feature engineering** – creating meaningful flags like long-term contracts, add-on usage, etc.
- **Modeling** – using a Random Forest model to predict churn
- **Feature importance** – analyzing top drivers of churn using model outputs
- **Business simulation** – estimating how much revenue could be saved by retaining high-risk customers
- **Recommendations** – clear strategy suggestions based on the data

## Key Insights

- Customers on month-to-month contracts have the highest churn risk by far.
- New customers (tenure < 12 months) are much more likely to leave.
- People without add-on services like streaming or device protection are also more likely to churn.
- Retaining even 30% of the top predicted churners could result in substantial revenue savings.

## Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn for modeling

## Running the Notebook

If you want to run this locally:

1. Download the Telco dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
2. Place it in the same directory as the notebook
3. Run all cells in order (after installing the required packages)

---

This project was built to feel like something a data analyst would present to a business stakeholder — with clear visuals, interpretable outputs, and recommendations that can actually drive decisions.
