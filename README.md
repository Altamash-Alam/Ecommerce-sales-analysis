# E-Commerce Sales Analysis

SQL analysis of the Olist Brazilian e-commerce dataset to understand revenue, order trends and regional performance.

## Dataset
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) (Kaggle). About 100,000 orders from 2016 to 2018. The raw CSV files are not included in this repo because of their size.

## Tools
- MySQL (MySQL Workbench)
- Power BI (dashboard in progress)

## What I did
- Loaded 7 tables (orders, customers, order_items, order_payments, products, sellers, category_translation) into MySQL.
- Joined orders with order items and customers to calculate revenue, order counts and average order value.
- Used only delivered orders. Revenue is based on item price and does not include freight.

## SQL queries
| File | What it does |
|---|---|
| `sql/01_total_orders_revenue.sql` | Total delivered orders and revenue |
| `sql/02_avg_order_value.sql` | Average order value |
| `sql/03_monthly_revenue.sql` | Orders and revenue by month |
| `sql/04_revenue_by_state.sql` | Top 10 states by revenue |

## Results
- Delivered orders: 96,478
- Total revenue: R$ 13,221,498.11
- Average order value: R$ 137.04

## Key insights
(Write 3 or 4 points in your own words here.)

## Project status
SQL analysis is complete. Power BI dashboard is in progress.
