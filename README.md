# 📊 Telco Customer Churn Analysis Dashboard

![Dashboard Preview](dashboard-preview.png)

## 📌 Overview

This project analyzes customer churn for a telecom company to understand **why customers leave** and **which factors are most associated with churn**. Raw data was sourced from Kaggle, cleaned and processed in Google Colab, and visualized as an interactive dashboard in Power BI.

## 🧰 Tools & Technologies

| Stage | Tool |
|---|---|
| Data Source | Kaggle |
| Data Cleaning & Preprocessing | Google Colab (Python, Pandas) |
| Dashboard & Visualization | Power BI |

## 🔄 Project Workflow

1. **Data Collection** — Downloaded the Telco Customer Churn dataset from Kaggle.
2. **Data Cleaning** — Cleaned and prepared the data in Google Colab:
   - Handled missing/null values
   - Fixed data types (e.g., `TotalCharges` converted to numeric)
   - Removed duplicates
   - Standardized categorical values
   - Exported the cleaned dataset as CSV for Power BI
3. **Dashboard Design** — Built an interactive dashboard in Power BI to visualize churn patterns.
4. **Insights** — Identified key drivers of churn using visuals and KPIs.

## 📈 Dashboard Features

- **KPI Cards** — Total Customers, Churned Customers, and Churn Rate at a glance
- **Churn by Contract Type** — Compares churn across month-to-month, one-year, and two-year contracts
- **Churn by Internet Service** — Donut chart showing churn share across Fiber optic, DSL, and No internet service
- **Churn by Payment Method** — Treemap breakdown of churn by payment type
- **Churn Trend by Tenure** — Line chart showing how churn count changes with customer tenure
- **Monthly Charges vs Total Charges** — Scatter plot showing the relationship between monthly and total charges for churned customers

## 🔑 Key Insights

- Customers on **month-to-month contracts** churn at a much higher rate than those on longer-term contracts.
- **Fiber optic** internet service users show a higher churn share compared to DSL users.
- Churn is highest among customers with **low tenure**, dropping sharply as tenure increases — indicating early-stage customers are at greater risk.
- Customers paying via **electronic check** show a notably higher churn count than other payment methods.

## 📁 Dataset

- **Source:** [Kaggle – Telco Customer Churn](https://www.kaggle.com/)
- **Records:** 7,043 customers
- **Target Variable:** `Churn` (Yes/No)

## 🚀 How to Use

1. Download the cleaned dataset / raw dataset from Kaggle.
2. Open the `.ipynb` notebook in Google Colab to review the data cleaning steps.
3. Open the `.pbix` file in Power BI Desktop to explore the dashboard interactively.

## 🙋 About

This project was built as part of a data analyst portfolio to demonstrate skills in data cleaning (Python/Pandas), and dashboard/report building (Power BI).

---
⭐ Feel free to fork this project or reach out if you have suggestions for improvement!
