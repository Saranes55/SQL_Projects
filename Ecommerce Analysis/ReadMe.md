# 🛒 E-Commerce Analysis

## 📌 Project Overview

- This project demonstrates practical SQL skills using MySQL through a complete e-commerce data analysis portfolio.
- It focuses on real-world business questions such as sales performance, customer behavior, revenue trends, and retention analysis.
- All analysis is done using ONLY MySQL queries, making this project ideal for Data Analyst / Business Analyst roles.

## 🎯 Objectives
  -	Analyze sales and revenue performance
  -	Understand customer purchasing behavior
  -	Identify top-performing products and cities
  -	Perform time-based analysis (monthly, daily trends)
  -	Apply advanced SQL concepts used in real jobs

## 🧩 Dataset Description
**The project uses four core e-commerce tables:**
## 1️⃣ Customers Table (ecom_customers)
Contains customer demographic information. - customer_id - customer_name - email - city - signup_date

## 2️⃣ Products Table (ecom_products)
Contains product details. - product_id - product_name - category - price

## 3️⃣ Orders Table (ecom_orders)
Contains order-level information. - order_id - customer_id - order_date - order_status

## 4️⃣ Order Items Table (ecom_order_items)
Contains item-level order details. - order_item_id - order_id - product_id - quantity - price

## 🛠 SQL Skills Demonstrated
**This project covers all essential SQL concepts:**
   -	✅ JOINS (INNER, LEFT)
   -	✅ GROUP BY & Aggregations
   -	✅ WINDOW FUNCTIONS (RANK, ROW_NUMBER, LAG)
   -	✅ CTEs (WITH clause)
   -	✅ SUBQUERIES
   -	✅ DATE FUNCTIONS
   -	✅ CASE STATEMENTS

## 📊 Business Questions Answered
**Some key questions answered in this project:**
   -	Top 5 best-selling products by revenue and quantity
   -	Monthly revenue trends and growth rate
   -	Customer segmentation based on spending
   -	Churn rate calculation
   -	Repeat vs one-time customers
   -	City-wise revenue performance
   -	Average order value (AOV) analysis
   	
(Complete list available inside the /queries folder)

## Project Structure

```
ecommerce-sql-portfolio/
│
├── data/
│   ├── ecom_customers.csv
│   ├── ecom_products.csv
│   ├── ecom_orders.csv
│   └── ecom_order_items.csv
│
├── schema/
│   └── create_tables.sql
│
├── queries/
│   ├── 01_joins + group_by.sql
│   ├── 02_date_function.sql
│   ├── 03_aggragation + case_statements.sql
│   ├── 04_subqueries.sql
│   ├── 05_window_functions.sql
│   ├── 06_cte_analysis.sql
│   └── 07_advanced_business_queries.sql
│
├── insights/
│   └── key_findings.md
│
├── visuals/
│   └── charts_screenshots.png
│
└── README.md
```



## 🚀 How to Run This Project
   1.	Import CSV files into MySQL
   2.	Execute schema/create_tables.sql
   3.	Run queries from the queries/ folder in order
   4.	Review insights and results

## 📈 Key Insights (Sample)
   -	A small percentage of customers contribute the majority of revenue
   -	Sales peak during specific months indicating seasonality
   -	Certain cities generate significantly higher AOV
   -	Repeat customers have higher lifetime value




