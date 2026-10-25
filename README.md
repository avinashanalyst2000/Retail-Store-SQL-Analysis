# Retail Store SQL Analysis

## Project Overview

This project focuses on designing and analyzing a retail store database using MySQL. It demonstrates relational database concepts and SQL queries used to explore customer information, product details, orders, payments, and product reviews.

The project is intended to demonstrate practical SQL skills relevant to data analysis.

## Project Objectives

* Create a relational database for a retail store.
* Define tables and relationships between business entities.
* Insert and verify sample data.
* Retrieve and filter records using SQL.
* Perform aggregations and grouped analysis.
* Analyze relationships between customers, products, and orders using joins.
* Practice subqueries and other SQL techniques.

## Database Schema

The project contains six tables:

| Table             | Purpose                                               |
| ----------------- | ----------------------------------------------------- |
| `customers`       | Stores customer information                           |
| `products`        | Stores product details                                |
| `orders`          | Stores customer order information                     |
| `order_items`     | Stores products and quantities associated with orders |
| `payments`        | Stores payment-related information                    |
| `product_reviews` | Stores product ratings and reviews                    |

## SQL Concepts Covered

The project includes practice queries involving:

* SELECT statements
* WHERE conditions
* DISTINCT
* ORDER BY
* BETWEEN and IN
* LIKE pattern matching
* Column aliases
* String concatenation
* Date functions
* Aggregate functions
* GROUP BY and HAVING
* JOIN operations
* Subqueries
* UNION
* EXISTS
* Data verification using COUNT

## Project Files

* `SQL PROJECT.sql` — Main SQL script containing database setup, table definitions, sample data, verification queries, and analysis exercises.
* `DataInsertionQueries.sql` — Separate sample-data insertion script. Some insertion statements overlap with the main SQL script, so review the scripts before executing both.

## How to Run the Project

1. Install MySQL Server and a SQL client such as MySQL Workbench.
2. Open MySQL Workbench and connect to your local MySQL server.
3. Open `SQL PROJECT.sql`.
4. Review the script before execution.
5. Execute the database creation and table definitions.
6. Execute the sample-data insertion statements once.
7. Run the verification queries to check the data.
8. Execute the analysis queries and review the results.

**Note:** Do not execute overlapping insertion statements twice. If you use `DataInsertionQueries.sql` to populate the tables, avoid rerunning the same INSERT statements from the main script.

## Learning Outcomes

This project provides practice in relational database design, SQL query writing, data retrieval, aggregation, joins, and exploratory analysis.

## Dataset Disclaimer

The records are sample data intended for practice. Confirm that the data contains no real personal or confidential information before publishing this repository publicly.

## Future Improvements

* Add an entity-relationship diagram (ERD).
* Document important business questions and their SQL solutions.
* Include screenshots of selected query results.
* Add a summary of verified findings from the dataset.
* Improve query organisation and documentation.

## Author

Avinash Thapa

Data Analyst Portfolio Project
