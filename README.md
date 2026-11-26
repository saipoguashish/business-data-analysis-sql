# Business Data Analysis using SQL

## Project Overview
Performed end-to-end exploratory data analysis on a 4-table relational retail dataset (`customers`, `orders`, `order_items`, and `products`) using SQLite to uncover revenue drivers, product profitability, and customer purchasing trends.

## Database Schema
![Database Schema](schema_diagram.png)

* **`customers`**: Customer demographics and regional segmentation (`customer_id` PK)
* **`orders`**: Transaction headers, dates, sales channels, and payment methods (`order_id` PK, `customer_id` FK)
* **`order_items`**: Line-item quantities, net sales, costs, and profit (`order_id` FK, `product_id` FK)
* **`products`**: Product catalog, categories, brands, and ratings (`product_id` PK)

## Skills Demonstrated
* **Data Retrieval & Filtering**: Used `SELECT`, `WHERE`, and `ORDER BY` to isolate high-value transactions.
* **Data Aggregation**: Applied `SUM()`, `COUNT()`, `AVG()`, and `GROUP BY` to summarize sales performance.
* **Relational Joins**: Combined 4 normalized tables using multi-table `JOIN` operations.
* **Trend Analysis**: Extracted monthly revenue and profit trajectories to identify seasonal shifts.

## Key Business Insights
*(Replace these placeholders with numbers from your SQLite Online results)*
* **Top Performing Category**: [Category Name] generated the highest profit at $[Amount].
* **Leading Sales Channel**: [Online/In-Store] accounted for [X]% of total orders with an average order value of $[Amount].
* **Regional Growth**: [Region Name] led overall net sales, driven primarily by [Product Category].

## Files in this Repository
* `business_analysis.sql` – Complete SQL script containing all business analysis queries.
* `schema_diagram.png` – Entity-Relationship (ER) diagram of the 4-table database.
# business-data-analysis-sql
xploratory business data analysis using SQL across a 4-table retail dataset.
