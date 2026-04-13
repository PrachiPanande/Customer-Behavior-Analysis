# 🛍️ Customer Shopping Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue?logo=postgresql)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data (~3,900 records) to uncover insights into purchasing patterns, customer segments, and revenue drivers.

The objective is to help businesses make **data-driven decisions** to improve customer engagement, optimize marketing strategies, and increase revenue.

---

## 🎯 Business Problem

A retail company wants to better understand:

- Customer purchasing patterns  
- Product preferences across categories  
- Factors influencing buying decisions (discounts, reviews, subscriptions)  

**Key Question:**  
How can customer data be leveraged to improve sales, engagement, and long-term loyalty?

---

## 🗂️ Dataset Summary

| Metric | Value |
|--------|------|
| Rows | 3,900 |
| Columns | 18 |
| Missing Values | 37 (Review Rating) |

### Key Features
- Demographics: Age, Gender, Location, Subscription Status  
- Purchase Info: Category, Item Purchased, Purchase Amount  
- Behavior: Discounts, Reviews, Shipping Type, Frequency  

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy)  
- PostgreSQL  
- Power BI  

---

## 🔄 Project Workflow

### 1. Data Cleaning (Python)
- Handled missing values in `review_rating`  
- Standardized column names (snake_case)  
- Created:
  - age_group  
  - purchase_frequency_days  
- Removed redundant columns  

---

### 2. Data Analysis (SQL)

Key questions answered:

- Revenue by gender  
- High-spending discount users  
- Top-rated products  
- Shipping type comparison  
- Subscriber vs non-subscriber analysis  
- Customer segmentation  
- Revenue by age group  

File: `Customer behavior.sql`

---

## 📊 Dashboard

### Key Metrics
- Total Customers: 3.9K  
- Avg Purchase: $59.76  
- Avg Rating: 3.75  

---

### Insights
- Clothing generates highest revenue  
- Majority are non-subscribers  
- Young & middle-aged customers dominate revenue  

---

### Filters
- Gender  
- Category  
- Subscription Status  
- Shipping Type  

---

## 📈 Key Insights
- ~73% customers are non-subscribers  
- Discounts influence purchasing behavior  
- Subscribers show higher engagement  
- Revenue is concentrated in top categories  

---

## 💡 Business Recommendations
- Promote subscription plans  
- Build loyalty programs  
- Optimize discount strategies  
- Highlight top-performing products  
- Use targeted marketing  

---

## 📁 Repository Structure
project-root/
- ├── data/
- │ └── customer_shopping_behavior.csv
- ├── sql/
- │ └── Customer behavior.sql
- ├── notebooks/
- │ └── data_cleaning.ipynb
- ├── dashboard/
- │ └── Customer_Behavior.pbix
- └── README.md

  
---

## 🚀 How to Run
- git clone https://github.com/your-username/customer-behavior-analysis.git

  
Steps:
1. Run Python preprocessing  
2. Load data into PostgreSQL  
3. Execute SQL queries  
4. Open Power BI dashboard  

---

## 📌 Future Improvements

- Add machine learning models  
- Automate ETL pipeline  
- Deploy dashboard online  



