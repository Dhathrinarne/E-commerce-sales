# E-Commerce Sales Analysis Using PostgreSQL
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Database-orange?style=for-the-badge&logo=databricks&logoColor=white)
![pgAdmin](https://img.shields.io/badge/pgAdmin-4A90D9?style=for-the-badge&logo=postgresql&logoColor=white)

## Project Overview
This project analyzes e-commerce sales data using PostgreSQL. It explores customer purchasing patterns, product performance, and monthly revenue through SQL queries.

## Objectives
- Analyze customer purchasing behavior.
- Identify top-performing products.
- Calculate total and monthly revenue.
- Practice SQL concepts used in Data Analyst roles.

## Tools Used
- PostgreSQL
- pgAdmin 4
- SQL

## Database Schema

The project consists of three tables:

1. **Customers** – Customer ID, customer name, and city.
2. **Products** – Product ID, product name, category, and price.
3. **Orders** – Order ID, customer ID, product ID, quantity, and order date.

## SQL Concepts Covered
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- GROUP BY and aggregate functions (SUM, COUNT, AVG)
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions (ROW_NUMBER)
- Date functions and revenue analysis

## Business Analysis
1. Monthly revenue analysis to identify the highest-performing month.
2. Total business revenue calculation.

## Key Findings
- Total business revenue: ₹1,76,000.
- January 2026 generated the highest revenue of ₹90,000.
- Laptop generated the highest product revenue of ₹1,00,000.
- Repeat customers included Rahul and Priya.

## Project Files
- `ecommerce_sales_analysis.sql` – SQL queries and analysis.
- `screenshots/` – Query execution results.

## How to Run
1. Install PostgreSQL and pgAdmin 4.
2. Create a database named `ecommerce_sales`.
3. Open Query Tool in pgAdmin.
4. Execute the SQL script section by section.

## Author
Data Analyst Portfolio Project
