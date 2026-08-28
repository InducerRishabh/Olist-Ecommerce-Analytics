\# Olist E-Commerce Sales \& Customer Analytics



\## Project Overview



This project analyzes the Olist Brazilian E-Commerce dataset to understand sales performance, customer behavior, product performance, and delivery operations.



The objective is to transform raw e-commerce data into actionable business insights using SQL, Python, DuckDB, and an interactive Streamlit dashboard.



\## Business Questions



\- How is revenue changing over time?

\- Which product categories generate the most revenue?

\- What is the average order value?

\- What percentage of customers make repeat purchases?

\- How does delivery performance vary across regions?

\- Does late delivery have an impact on customer review scores?

\- Which customer segments contribute the most revenue?

\- Which payment methods are most commonly used?



\## Dataset



The analysis uses the Olist Brazilian E-Commerce dataset containing information about:



\- Orders

\- Customers

\- Products

\- Sellers

\- Payments

\- Reviews

\- Geolocation

\- Product categories



The dataset contains approximately 100K orders across multiple related tables.



\## Tools \& Technologies



\- Python

\- SQL

\- DuckDB

\- Pandas

\- Streamlit

\- Plotly

\- Jupyter Notebook



\## Analysis Performed



\### Sales Analysis



Analyzed:



\- Total revenue

\- Total orders

\- Average Order Value (AOV)

\- Monthly revenue

\- Month-over-month growth

\- Product category performance



\### Customer Analysis



Analyzed:



\- Total customers

\- Repeat purchase rate

\- Customer lifetime value

\- Customer segments

\- Cohort retention



\### Delivery Analysis



Analyzed:



\- Average delivery time

\- Late delivery rate

\- Regional delivery performance

\- Relationship between delivery status and review scores



\### Payment Analysis



Analyzed:



\- Payment method distribution

\- Revenue by payment type

\- Average number of installments



\## Key SQL Concepts



\- INNER JOIN

\- LEFT JOIN

\- CTEs

\- GROUP BY

\- CASE WHEN

\- HAVING

\- DATE\_TRUNC

\- DATE\_DIFF

\- LAG

\- Window Functions

\- Aggregations



\## Key Insights



The analysis highlights differences in:



\- Revenue contribution across product categories

\- Customer repeat-purchase behavior

\- Delivery performance across regions

\- Customer satisfaction between on-time and late deliveries

\- Revenue contribution from different customer segments



\## Dashboard



The project includes an interactive Streamlit dashboard for exploring sales, customer, product, payment, and delivery metrics.



!\[Dashboard](./screenshots/dashboard.png)



\## Project Structure



```text

Olist-Ecommerce-Analytics/

│

├── analysis.ipynb

├── app.py

├── db.py

├── download\_data.py

├── load\_to\_duckdb.py

├── queries.sql

├── README.md

│

└── screenshots/

&#x20;   └── dashboard.png

