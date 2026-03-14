
# SQL Data Analytics Project

## Overview
This project demonstrates practical SQL-based data analysis using sales data stored in a relational database.
The goal of the project is to explore transactional sales data and generate meaningful business insights through SQL queries.

The analysis focuses on understanding customer behavior, product performance, and overall sales trends.

The dataset and database initialization script were provided as part of a SQL analytics learning course, while the analytical SQL scripts and reports were implemented during the exercises.

---

## Project Structure

sql-data-analytics-project
│
├── datasets
│   ├── bronze
│   ├── silver
│   └── gold
│
├── scripts
│   ├── 00_init_database.sql
│   ├── 01_database_exploration.sql
│   ├── 02_dimensions_exploration.sql
│   ├── 03_date_range_exploration.sql
│   ├── 04_measures_exploration.sql
│   ├── 05_magnitude_analysis.sql
│   ├── 06_ranking_analysis.sql
│   ├── 07_change_over_time_analysis.sql
│   ├── 08_cumulative_analysis.sql
│   ├── 09_performance_analysis.sql
│   ├── 10_data_segmentation.sql
│   ├── 11_part_to_whole_analysis.sql
│   ├── 12_report_customers.sql
│   └── 13_report_products.sql
│
└── DataWarehouseAnalytics.bak

---

## Dataset
The dataset consists of CRM and ERP sales data including information about customers, products, and transactions.

Key data elements include:
- customer information
- product information
- sales transactions
- order details
- quantities and revenue

The raw dataset was provided as part of the course material.

---

## Database Tables

### Fact Table
**fact_sales**

Contains transactional sales data.

Main fields include:
- order_number
- order_date
- customer_key
- product_key
- sales_amount
- quantity

### Dimension Tables

**dim_customers**
Contains customer attributes such as customer name and demographic information.

**dim_products**
Contains product details including product name, category, subcategory, and product cost.

---

## Analysis Modules

### Database Exploration
Scripts used to understand the structure and content of the database.

Examples:
- reviewing table structures
- exploring dimensions
- identifying date ranges
- analyzing key measures

### Sales Analysis
Scripts used to analyze sales data and identify trends.

Examples include:
- magnitude analysis
- ranking products by sales
- change-over-time analysis
- cumulative revenue analysis

### Performance Analysis
Compares performance metrics such as current vs historical sales levels.

### Data Segmentation
Segments customers and products based on performance metrics.

### Part-to-Whole Analysis
Calculates contribution of products or categories to total revenue.

---

## Customer Report
The customer report aggregates key customer metrics and behaviors.

Metrics include:
- total orders
- total sales
- total quantity purchased
- total products purchased
- customer lifespan

KPIs include:
- recency (months since last order)
- average order value
- average monthly spend

Customer segmentation categories:
- VIP
- Regular
- New

---

## Product Report
The product report summarizes product performance.

Metrics include:
- total orders
- total sales
- total quantity sold
- total customers
- product lifespan

KPIs include:
- recency (months since last sale)
- average selling price
- average order revenue
- average monthly revenue

Products are segmented into:
- High Performer
- Mid Range
- Low Performer

---

## SQL Techniques Used
This project demonstrates the use of several SQL concepts:

- SELECT queries
- JOIN operations
- GROUP BY aggregations
- CASE statements
- Common Table Expressions (CTEs)
- Window functions
- ranking functions
- cumulative calculations
- segmentation logic

---

## Skills Demonstrated
- Writing analytical SQL queries
- Exploring relational datasets
- Generating business insights from transactional data
- Calculating key performance indicators
- Creating SQL-based analytical reports

---

## Tools Used
- SQL Server
- T-SQL
- Git
- GitHub

---

## Acknowledgment
This project was completed as part of a SQL Data Analytics tutorial by Baraa on YouTube.

Tutorial:
https://www.youtube.com/watch?v=2jGhQpbzHes

The dataset and database initialization script were provided in the tutorial, while the analytical SQL scripts and reports were implemented during the exercises.

---

## License
MIT License
