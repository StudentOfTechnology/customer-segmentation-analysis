\# Customer Segmentation & Sales Performance Analysis (SQL + Power BI)



\## Overview

This project analyzes customer purchasing behavior to identify high-value customers, evaluate profitability, and understand the impact of discounts on business performance.



The goal is to move beyond raw data and provide actionable insights that can support better pricing, targeting, and customer strategy decisions.



\---



\## Tools Used

\- PostgreSQL

\- SQL (CTEs, CASE statements, aggregations)

\- Power BI (data modeling, DAX, visualization)



\---



\## Data Preparation



A SQL view (`customer\_analysis`) was created to transform transactional data into customer-level insights.



Key transformations include:

\- Aggregating total sales, profit, quantity, and average discount per customer

\- Segmenting customers into:

&#x20; - High Value

&#x20; - Medium Value

&#x20; - Low Value

\- Classifying customers as:

&#x20; - Profitable

&#x20; - Unprofitable



This structured dataset enables efficient analysis and dashboard reporting.



\---



\## Dashboard Features



The Power BI dashboard provides a comprehensive view of customer performance:



\- \*\*KPI Metrics\*\*

&#x20; - Total Customers

&#x20; - Total Sales

&#x20; - Total Profit



\- \*\*Customer Segmentation\*\*

&#x20; - Distribution of customers by value tier



\- \*\*Top Customers Analysis\*\*

&#x20; - Top 10 customers by sales

&#x20; - Top 10 customers by profit



\- \*\*Profitability Insights\*\*

&#x20; - Breakdown of profitable vs unprofitable customers



\- \*\*Discount vs Profit Analysis\*\*

&#x20; - Visual exploration of how discounting impacts profitability



\---



\## Key Insights



\- A small group of high-value customers contributes a disproportionate share of revenue

\- Discounting does not consistently improve profitability and may reduce margins

\- Customer profitability varies significantly, highlighting opportunities for better targeting

\- Some customers generate sales but contribute little or negative profit



\---



\## Project Structure



data/

sql/

powerbi/

screenshots/

README.md



\---



\## Screenshots



\### SQL View

!\[SQL View](screenshots/01\_customer\_analysis\_view.png)



\### Dashboard

!\[Dashboard](screenshots/02\_customer\_dashboard.png)



