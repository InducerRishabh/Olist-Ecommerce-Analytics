# Olist E-Commerce Sales & Customer Analytics

## Project Overview

This project analyzes the Olist Brazilian E-Commerce dataset to understand sales performance, customer behavior, product performance, and delivery operations.

The objective is to transform raw e-commerce data into actionable business insights using SQL, Python, DuckDB, and an interactive Streamlit dashboard.

## Business Questions

- How is revenue changing over time?
- Which product categories generate the most revenue?
- What is the average order value?
- What percentage of customers make repeat purchases?
- How does delivery performance vary across regions?
- Does late delivery have an impact on customer review scores?
- Which customer segments contribute the most revenue?
- Which payment methods are most commonly used?

## Dataset

The analysis uses the Olist Brazilian E-Commerce dataset containing information about:

- Orders
- Customers
- Products
- Sellers
- Payments
- Reviews
- Geolocation
- Product categories

The dataset contains approximately 100K orders across multiple related tables.

## Tools & Technologies

- Python
- SQL
- DuckDB
- Pandas
- Streamlit
- Plotly
- Jupyter Notebook

## Analysis Performed

### 1. Sales Analysis

Analyzed:

- Total revenue
- Total orders
- Average Order Value (AOV)
- Monthly revenue
- Month-over-month growth
- Product category performance

### 2. Customer Analysis

Analyzed:

- Total customers
- Repeat purchase rate
- Customer lifetime value
- Customer segmentation
- Monthly cohort retention

### 3. Delivery Analysis

Analyzed:

- Average delivery time
- Late delivery rate
- Regional delivery performance
- Relationship between delivery status and review scores

### 4. Payment Analysis

Analyzed:

- Payment method distribution
- Revenue by payment type
- Average number of installments

## Key SQL Concepts

The project demonstrates practical SQL techniques including:

- INNER JOIN
- LEFT JOIN
- Common Table Expressions (CTEs)
- GROUP BY
- CASE WHEN
- HAVING
- DATE_TRUNC
- DATE_DIFF
- LAG
- Window Functions
- Aggregations

## Key Findings

Some notable findings from the analysis include:

- Total revenue analyzed was approximately **R$15.4M** across **96K+ delivered orders**.
- The average order value was approximately **R$159.86**.
- The overall repeat purchase rate was approximately **3.0%**, indicating that most customers made a single purchase.
- On-time orders had a substantially higher average review score than late orders.
- Delivery performance varies significantly across Brazilian states.
- Revenue contribution differs considerably across product categories.
- Customer segments show meaningful differences in average customer spending and total revenue contribution.

## Dashboard

The project includes an interactive Streamlit dashboard covering:

- Revenue KPIs
- Monthly revenue trends
- Month-over-month growth
- Top product categories
- Delivery performance
- Regional fulfillment
- Cohort retention
- Payment methods
- Customer lifetime value
- Category-based product exploration

### Dashboard Preview

![Olist E-Commerce Dashboard](./screenshots/dashboard.png)

## Project Structure

```text
Olist-Ecommerce-Analytics/
│
├── analysis.ipynb
├── app.py
├── db.py
├── download_data.py
├── load_to_duckdb.py
├── queries.sql
├── README.md
│
└── screenshots/
    └── dashboard.png
