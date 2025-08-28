# 📊 Customer Churn Exploratory Data Analysis (EDA)

## 📌 Overview
This project analyzes customer churn patterns using the **Telco Customer Churn dataset**.  
The goal is to identify key factors that contribute to customer churn and provide actionable insights for reducing churn rates.

---

## 🗂 Dataset
- **File:** `Customer Churn.csv`  
- **Target Variable:** `Churn` (Yes = customer left, No = customer stayed)  
- **Features:**  
  - Demographics (Gender, Senior Citizen, etc.)  
  - Account info (Tenure, Contract, Payment Method, etc.)  
  - Services subscribed (Internet, Online Security, Tech Support, Streaming, etc.)  

---

## 🔑 Steps Performed
1. **Data Preprocessing**
   - Checked datatypes, missing values, duplicates.  
   - Converted `SeniorCitizen` (0/1 → Yes/No).  

2. **Exploratory Data Analysis**
   - Distribution of churn vs. non-churned customers.  
   - Demographic impact (Gender, Senior Citizen).  
   - Tenure & contract type analysis.  
   - Effect of subscribed services (security, tech support, streaming).  
   - Payment method patterns.  

3. **Visualization**
   - Count plots & histograms.  
   - Stacked bar charts for churn percentages.  
   - Pie chart for churn distribution.  
   - Multi-subplot service analysis.  

---

## 📈 Key Insights
- **Churn Rate:** ~26–27% of customers left the service.  
- **Demographics:** Gender has little effect, but **Senior Citizens churn more**.  
- **Tenure:** **New customers** (low tenure) are far more likely to churn.  
- **Contracts:** **Month-to-month contracts** have the highest churn, while 1–2 year contracts have much lower churn.  
- **Services:** Customers **without Online Security, Backup, or Tech Support** are more likely to churn. Fiber optic users churn more than DSL users.  
- **Payment Method:** **Electronic check users churn the most**, while automatic payment users churn less.  

---

## 🎯 Business Recommendations
- Offer **retention discounts** for month-to-month and senior citizen customers.  
- Encourage **long-term contracts** with special offers.  
- Upsell **security & support services** to high-risk customers.  
- Promote **automatic payments** instead of electronic checks to improve retention.  

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  

---

## 📂 Project Structure
-- ├── eda.ipynb # Jupyter Notebook with full analysis
-- ├── Customer Churn.csv # Dataset
-- └── README.md # Documentation
