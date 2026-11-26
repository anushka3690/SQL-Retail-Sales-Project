# Retail Sales Analysis with PostgreSQL

## Business objective

Use retail transaction data to answer practical questions about sales, customers, product categories, and shopping patterns. The project loads a CSV into PostgreSQL, checks and removes incomplete records, then uses SQL queries to produce decision-oriented summaries.

## Questions answered

- What are sales and order counts by product category?
- Which months have the highest average sales in each year?
- Who are the top customers by total spend?
- How do sales vary by customer gender, category, and time of day?
- How many distinct customers purchase from each category?
- What transactions meet date, category, quantity, or value criteria?

## SQL techniques

The analysis uses table creation, null checks, aggregation, `GROUP BY`, date extraction, conditional logic, common table expressions, and window functions (`RANK`) to build the reports.

## Project files

- `SQL_Retail-sales-analysis.sql` - PostgreSQL schema, data checks, and analysis queries
- `SQL_Retail-Sales-Data.csv` - sample transaction data used by the project

Run the SQL script in a PostgreSQL environment after updating the database setup to match your local configuration.
