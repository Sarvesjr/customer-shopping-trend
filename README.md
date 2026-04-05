# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project performs an **end-to-end analysis of customer shopping behavior** using transactional data from **3,900 purchases** across multiple product categories.

The goal is to uncover **actionable insights** into customer spending patterns, product preferences, discount impact, and subscription behavior to support **data-driven business decisions**.

---

## 🎯 Objectives

* Clean and preprocess raw data using **Python (Pandas)**
* Perform structured analysis using **PostgreSQL (SQL)**
* Build an interactive dashboard using **Power BI**
* Generate business insights and recommendations

---

## 📊 Dataset Summary

* **Records:** 3,900 transactions
* **Features:** 18 columns
* **Categories:** Clothing, Accessories, Footwear, Outerwear
* **Age Range:** 18 – 70
* **Missing Values:** 37 (handled using median imputation)

---

## 🛠️ Tech Stack

* **Python:** Pandas, NumPy (Data Cleaning & EDA)
* **Database:** PostgreSQL (SQL Analysis)
* **Visualization:** Power BI
* **Connector:** SQLAlchemy + psycopg2
* **Version Control:** GitHub

---

## 🧹 Data Cleaning & Feature Engineering

* Handled missing values in `review_rating`
* Standardized column names (snake_case)
* Created:

  * `age_group` (Young Adult, Middle-Aged, Adult, Senior)
  * `purchase_frequency_days`
* Removed redundant columns (`promo_code_used`)

---

## 🧠 SQL Analysis (16 Business Questions)

### 🔹 Core Analysis

1. Revenue by Gender
2. High-Spending Discount Users
3. Top 5 Products by Rating
4. Shipping Type Comparison
5. Subscribers vs Non-Subscribers
6. Discount-Dependent Products
7. Customer Segmentation
8. Top 3 Products per Category
9. Repeat Buyers & Subscriptions
10. Revenue by Age Group

### 🔹 Advanced Analysis

11. Customer Lifetime Value (Top 10)
12. Category Revenue Contribution
13. Discount Impact on Revenue
14. Repeat Customer Revenue Contribution
15. High-Value Orders by Category
16. Churn Risk Identification

---

## 📈 Power BI Dashboard

The dashboard includes:

* KPIs:

  * Total Revenue ($233K)
  * Avg Order Value ($59.76)
  * Avg Rating (3.75★)
* Visuals:

  * Revenue by Category
  * Purchase Frequency Distribution
  * Avg Spend by Age Group
  * Payment Method Share
* 5 interactive slicers:

  * Season, Gender, Category, Subscription, Discount

---

## 🔍 Key Insights

* Clothing contributes **44.73% of total revenue**
* Male customers generate significantly higher revenue
* **79.9% customers are loyal buyers**
* Discounts do **not reduce spending significantly**
* Majority of repeat buyers are **non-subscribers**

---

## 💡 Business Recommendations

* Convert non-subscribers using targeted campaigns
* Focus on high-performing categories (Clothing & Accessories)
* Re-engage churn-risk customers
* Optimize discount strategies
* Promote express shipping to increase AOV

---

## 📂 Project Structure

```
├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── data_cleaning.ipynb
├── sql/
│   └── queries.sql
├── dashboard/
│   └── powerbi_dashboard.pbix
├── report/
│   └── Customer_Shopping_Behavior_Analysis.pdf
└── README.md
```

---


## 📌 Future Improvements

* Add machine learning for customer prediction
* Build web dashboard (Flask / Streamlit)
* Automate ETL pipeline

---

## 👨‍💻 Author

**J R Sarves Srirangan**
📅 April 2026

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
