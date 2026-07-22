# retail_sales_dataset
Retail Sales Data Analysis using MySQL. This project analyzes retail sales data to generate business insights on revenue, profit, customer behavior, and product performance. It includes data validation, CTEs, Views, Indexes, and Window Functions (LAG, DENSE_RANK) to perform advanced SQL analysis and reporting.

# 🛍️ Retail Sales Data Analysis Using MySQL

## 📌 Project Overview

This project focuses on analyzing a retail sales dataset using **MySQL** to extract meaningful business insights. The objective is to demonstrate practical SQL skills by performing data exploration, cleaning, aggregation, and advanced analytical queries that help understand customer behavior, sales performance, profitability, and overall business trends.

The project is designed as a portfolio project to showcase SQL concepts commonly used in data analysis and business intelligence.

---

# 🎯 Objectives

* Analyze retail sales data using SQL.
* Perform data cleaning and validation.
* Generate business insights from transactional data.
* Identify top-performing products and customers.
* Analyze revenue, profit, and sales trends.
* Practice advanced SQL concepts used in real-world projects.

---

# 🗄️ Database Structure

The project uses a single table named **`retail_sales`** containing transaction-level information.

### Columns

| Column           | Description                            |
| ---------------- | -------------------------------------- |
| order_id         | Unique order identifier                |
| order_date       | Date of purchase                       |
| order_time       | Time of purchase                       |
| customer_id      | Customer identifier                    |
| gender           | Customer gender                        |
| age              | Customer age                           |
| product_category | Product category                       |
| quantity         | Quantity purchased                     |
| unit_price       | Price per unit                         |
| cost             | Cost of the product                    |
| total_revenue    | Revenue generated from the transaction |

---

# 📊 SQL Concepts Used

This project covers a wide range of SQL concepts, including:

* Database Creation
* Table Creation
* Data Validation
* Data Cleaning
* Aggregate Functions
* GROUP BY
* ORDER BY
* DISTINCT
* LIMIT
* CASE Statements
* Date & Time Functions
* Indexes
* Views
* Common Table Expressions (CTEs)
* Window Functions

  * LAG()
  * DENSE_RANK()
  * SUM() OVER()
* Business KPI Analysis

---

# 📈 Business Questions Solved

The project answers several real-world business questions, including:

### Basic Analysis

* Total number of sales
* Total number of customers
* Total product categories
* Orders by category
* Orders by gender
* Total revenue

### Intermediate Analysis

* Revenue by product category
* Highest selling category
* Average revenue per order
* Top 5 highest spending customers
* High-value transactions
* Sales on a specific date
* Category-specific sales analysis

### Advanced Analysis

* Total profit by category
* Most profitable category
* Revenue contribution by age group
* Orders by time of day
* Monthly revenue analysis
* Monthly revenue growth
* Profit margin analysis
* Category contribution percentage
* Top customers in each product category
* Business KPI summary

---

# 🚀 Advanced SQL Features

## ✅ Common Table Expressions (CTEs)

Used to simplify complex queries such as monthly sales analysis and customer ranking.

## ✅ Window Functions

Implemented advanced analytical functions including:

* **LAG()** to compare monthly revenue with the previous month.
* **DENSE_RANK()** to rank customers within each product category.
* **SUM() OVER()** to calculate category contribution percentages.

## ✅ Views

Created reusable SQL views for profit and profit margin calculations.

## ✅ Indexes

Indexes were created on frequently searched columns to improve query performance.

---

# 📌 Key Insights Generated

* Identified the highest revenue-generating product categories.
* Ranked the top customers based on total spending.
* Measured monthly sales growth.
* Calculated profit margins across product categories.
* Analyzed customer purchasing patterns.
* Generated business KPIs for management reporting.

---

# 💻 Technologies Used

* MySQL
* MySQL Workbench
* SQL

---

# 📂 Project Structure

```text
Retail-Sales-Data-Analysis/
│
├── Retail_Sales_Analysis.sql
├── Retail_Sales_Dataset.csv
├── README.md
└── screenshots/
    ├── database_schema.png
    ├── dataset_preview.png
    ├── revenue_by_category.png
    ├── top_customers.png
    ├── monthly_growth.png
    └── project_summary.png
```

---

# 📷 Suggested Screenshots

* Database schema
* Dataset preview
* Revenue by product category
* Top 5 customers
* Monthly revenue growth
* KPI summary

---

# 🎓 Learning Outcomes

Through this project, I gained hands-on experience in:

* Writing efficient SQL queries
* Solving real-world business problems using SQL
* Performing sales and customer analytics
* Working with CTEs and Window Functions
* Creating Views and Indexes
* Improving SQL query organization and readability

---

# 📬 Conclusion

This project demonstrates how SQL can be used to transform raw retail sales data into meaningful business insights. It strengthened my understanding of SQL fundamentals and advanced analytical techniques while providing practical experience with real-world data analysis scenarios.

I plan to continue building more database and analytics projects while expanding my knowledge of SQL, backend development, and data engineering.
