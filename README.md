# Zepto Inventory Analysis Using SQL

## Project Overview

This project uses PostgreSQL to explore and analyze Zepto product inventory data. It focuses on data quality, product pricing, discount patterns, stock availability, and category-level inventory metrics.

## Objectives

* Explore the product inventory dataset.
* Identify missing values and duplicate product names.
* Clean invalid pricing records.
* Analyze discounts and out-of-stock products.
* Estimate inventory value and total inventory weight.
* Compare product value using price-per-gram calculations.

## Tools & Technologies

* PostgreSQL
* pgAdmin 4
* SQL

## Project Structure

* `sql/zepto_analysis.sql` — table creation, data cleaning, and analysis queries.
* `data/zepto_inventory.csv` — dataset, if included.
* `screenshots/` — query output screenshots, if included.

## SQL Concepts Used

* SELECT, WHERE, DISTINCT, ORDER BY, LIMIT
* GROUP BY and HAVING
* COUNT, SUM, AVG, ROUND
* UPDATE and DELETE
* CASE statements
* NULL-value checks
* Primary keys and table creation

## Business Questions

1. Which products offer the highest discount percentages?
2. Which high-MRP products are out of stock?
3. What is the estimated inventory value by category?
4. Which products have an MRP above ₹500 and discounts below 10%?
5. Which categories have the highest average discounts?
6. Which products offer the lowest price per gram?
7. How can products be grouped by weight?
8. What is the total inventory weight by category?

## How to Run the Project

1. Install PostgreSQL and open pgAdmin 4.
2. Create or select a database.
3. Import the dataset into a table named `zepto`, matching the SQL schema.
4. Open `zepto_analysis.sql` in Query Tool.
5. Review the queries and execute them in the appropriate order.

**Note:** The script drops and recreates the `zepto` table. Back up any existing data before running it. The script also assumes prices are initially stored in paise before converting them to rupees.

## Key Findings

Add your actual findings after running the queries, such as the top discounted products, highest-discount categories, and inventory value by category.

## Author

Tanu Verma

Data Analytics | SQL | Python | Excel | Power BI

