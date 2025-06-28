# Telco-Customer-Churn-analysis
# 📊 Telco Customer Churn – Exploratory Data Analysis (EDA)

This project explores customer churn behavior in a telecom company using Python and pandas. The goal is to understand what factors contribute to churn and prepare the dataset for further analysis or modeling.

---

## 📁 Dataset Overview

- **Total Rows:** 7,043  
- **Missing Values:** 0  
- **Duplicate Records:** 0  
- **Source File:** `CUSTOMERCHURN.csv`

---

## 📌 Key Findings

### 🧍‍♂️ Senior Citizens

- **Yes:** 1,142 customers (≈16.21%)  
- **No:** 5,901 customers (≈83.79%)

This feature was originally coded as `0` and `1` and was mapped to `"No"` and `"Yes"` for clarity.

---

### ❌ Customer Churn

- **Yes (Churned):** 1,869 customers (≈26.54%)  
- **No (Stayed):** 5,174 customers (≈73.46%)

The dataset shows that about **1 in 4** customers left the service, which is substantial and worth analyzing for retention strategies.

---

## 🔧 Data Cleaning & Preparation

- **`TotalCharges` column:**
  - Contained blank strings, which were replaced with `"0"` and converted to `float` for analysis.
- **`SeniorCitizen` column:**
  - Converted from numeric (`0`, `1`) to categorical (`"No"`, `"Yes"`).
- **No missing or duplicate data** remained after cleaning.

---

## 📚 Libraries Used

```python
pandas  
numpy  
matplotlib  
seaborn  
