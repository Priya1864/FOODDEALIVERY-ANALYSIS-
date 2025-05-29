# Food Delivery Orders Analysis - SQL Project

## Overview

This project contains a sample SQL dataset simulating food delivery orders across multiple cuisines and restaurants. It includes detailed order records with customer information, order timestamps, restaurant outlets, cuisine types, order status, and promotional codes used.

The SQL scripts provide queries to analyze the dataset for business insights such as:

- Top performing restaurants by cuisine
- Daily new customer acquisition trends
- Customer order frequency and retention analysis
- Identifying customers inactive for the last 7 days but acquired earlier
- Promo code usage and customer segmentation

## Dataset Details

- **Table**: `orders`
- **Columns**:
  - `Order_id` (VARCHAR): Unique identifier for each order
  - `Customer_code` (VARCHAR): Unique customer ID
  - `Placed_at` (TIMESTAMP): Date and time when the order was placed
  - `Restaurant_id` (VARCHAR): Outlet identifier
  - `Cuisine` (VARCHAR): Cuisine type (e.g., Lebanese, Italian, American)
  - `Order_status` (VARCHAR): Status of the order (e.g., Delivered, Cancelled)
  - `Promo_code_Name` (VARCHAR): Promotional code applied on the order (nullable)

## Prerequisites

- A SQL database environment such as PostgreSQL, MySQL, or any relational database that supports standard SQL.
- Basic knowledge of SQL querying and database setup.
- Tools like DBeaver, pgAdmin, or MySQL Workbench to execute SQL scripts.

## How to Run

1. Create the `orders` table by running the provided SQL `CREATE TABLE` script.
2. Insert the sample data using the SQL `INSERT` statements.
3. Execute the provided analysis queries in your SQL environment.
4. Review the results for insights on customer behavior, restaurant performance, and promo usage.
5. Modify or extend queries for your specific use cases.

## Key SQL Queries

- **Top Restaurants by Cuisine:**  
  Rank and list the top 2 or 3 outlets for each cuisine based on order counts.

- **Daily New Customer Count:**  
  Calculate the number of customers placing their first-ever order on each day.

- **Single Order Customers in January 2025:**  
  Identify customers acquired in January 2025 who placed only one order that month and no other orders afterwards.

- **Customers with No Orders in Last 7 Days:**  
  Find customers who have not placed orders in the last 7 days but were acquired one month prior, including their first order promo code.

## Technologies Used

- SQL (compatible with PostgreSQL, MySQL, or similar relational databases)

## Project Goals

- Practice complex SQL queries using window functions, CTEs, filtering, and aggregation.
- Perform customer acquisition and retention analysis.
- Analyze promotional campaign impacts.
- Generate actionable insights from food delivery order data.

## Contribution

Feel free to fork the repository, submit issues or pull requests for improvements, additional queries, or dataset expansions.

## License

This project is open source and available under the MIT License.

---

*Created by [PRIYA]*  
*Contact: PRIYAPRIYA72884@GMAIL.com*

