# 📡 Telecom Customer & 📊 Revenue Analysis 

## 📌  Project Overview
This project is a MySQL-based SQL portfolio showcasing real-world business analysis queries across customer behavior, revenue, churn, and product performance.
The goal of this project is to demonstrate how SQL can be used to extract meaningful insights from relational databases and support data-driven decision-making.
The queries are designed at an intermediate to advanced level, reflecting scenarios commonly faced by data analysts in telecom, e-commerce, or subscription-based businesses.

## 🎯 Objectives
  - Analyze customer activity, spending, and usage behavior
  - Identify revenue trends and top-performing products
  - Measure churn, retention, and customer lifetime value (CLV)
  - Evaluate product performance and sales trends
  - Demonstrate strong SQL querying and analytical thinking

## 🗂 Dataset Description
The project uses a relational database structure containing multiple business entities such as:
  - **Customers** – customer profile, age, location, activation date
  - **Orders** – order details, order date, quantities
  - **Products** – product details, pricing, and data plan
  - **customers_usage** – usage_id, customer_id, month, data_used_gb, call_minutes

## 🛠 SQL Skills Demonstrated
**This project highlights the following SQL skills:**
  - INNER JOIN, LEFT JOIN
  - GROUP BY, HAVING
  - Aggregate functions (SUM, AVG, COUNT)
  - Date functions (MONTH, YEAR, DATE_SUB)
  - Window functions (RANK, ROW_NUMBER)
  - Subqueries & CTEs
  - Conditional logic (CASE WHEN)
  - Business KPIs (Churn, CLV, AOV)

## 📈 Business Analysis Questions 

### SEC-1. Customer Analysis
1. List all active customers with plan and location details
2. Identify customers who never placed an order
3. Find top 10 customers by total spending
4. Detect churned customers (inactive for last 90 days)
5. Segment customers into High, Medium, and Low usage categories

### SEC-2. Revenue & Sales Analysis
1. Calculate monthly revenue for the last 12 months
2. Identify top 5 best-selling products by quantity and revenue
3. Find products with zero sales
4. Compute Average Order Value (AOV) month-wise
5. Determine top 5 revenue-generating cities

### SEC-3. Churn & Retention
1. Calculate monthly churn rate
2. Estimate Customer Lifetime Value (CLV)

### SEC-4.Product Performance
1. Rank products within each category by revenue
2. Calculate product-wise pricing, orders, and revenue contribution
3. Identify products with declining month-over-month sales

## 📁 Project Structure
```
mysql-portfolio/
│
├── dataset/
│   ├── customers.sql
│   ├── orders.sql
│   ├── products.sql
│   └── customer_usage.sql
│
├── queries/
│   ├── customer_analysis.sql
│   ├── revenue_sales.sql
│   ├── churn_retention.sql
│   └── product_performance.sql
│
├── README.md
```

## ▶️ How to Run This Project

1. Install **MySQL Server**
2. Create a new database
3. Import dataset tables from the dataset/ folder
4. Execute SQL scripts from the queries/ folder
5. Review outputs for business insights

## 🔑 Key Insights
  - A small percentage of customers contribute a large share of total revenue
  - High-usage customers show stronger retention patterns
  - Certain products generate revenue but suffer declining sales trends
  - Customer churn can be detected early using inactivity signals
  - City-level revenue analysis helps identify strong regional markets

## 🚀 Conclusion
This project demonstrates how SQL can transform raw transactional data into actionable business insights.
It reflects real-world analytics tasks and strengthens skills required for Data Analyst / Business Analyst roles.












