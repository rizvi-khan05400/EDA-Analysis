📊 Customer Churn Analysis (EDA)
📌 Overview

This project explores the Telco Customer Churn dataset to understand the factors that contribute to customer churn (whether customers leave the company). The analysis includes data preprocessing, visualization, and extraction of business insights.

🗂 Dataset

Source: Customer Churn.csv

Target Variable: Churn (Yes/No)

🔑 Key Steps

Data Loading & Cleaning

Checked missing values, data types, and applied preprocessing.

Converted categorical variables where needed (e.g., SeniorCitizen → Yes/No).

Exploratory Data Analysis

Distribution of churned vs. non-churned customers.

Demographic impact (Gender, Senior Citizen).

Service subscriptions (Phone, Internet, OnlineSecurity, TechSupport, etc.).

Contract type and tenure.

Payment method patterns.

Visualization

Count plots, histograms, pie charts.

Stacked bar charts for churn percentages.

Multi-subplot comparison across services.

📈 Findings & Insights

Overall Churn Rate: ~26–27% of customers left.

Demographics: Gender has little effect, but senior citizens churn more.

Tenure: New customers (short tenure) are more likely to churn.

Contracts: Month-to-month contracts have the highest churn; long-term contracts are safer.

Services: Lack of online security/backup/tech support increases churn risk. Fiber optic users churn more than DSL.

Payment Method: Electronic check users churn the most; auto-pay customers churn less.

🎯 Business Recommendations

Provide retention offers for month-to-month and senior citizen customers.

Promote long-term contracts with discounts.

Upsell support and security services to reduce churn.

Encourage automatic payments instead of electronic checks.

⚙️ Tech Stack

Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

📂 Project Structure
├── eda.ipynb         # Main notebook with analysis
├── Customer Churn.csv # Dataset
└── README.md         # Project documentation
