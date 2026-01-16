📊 Retail Sales Analytics & Customer Segmentation Dashboard
📌Project Overview

This project delivers an end-to-end retail analytics solution that transforms raw transactional data into actionable business insights.
Using SQL, Python, and Power BI, the project analyzes sales performance, customer behavior, and purchasing patterns, and applies RFM analysis 
with K-Means clustering for customer segmentation.
The final output is an interactive Power BI dashboard designed for executive decision-making.

🎯 Business Objectives

Analyze overall sales performance and revenue trends
Identify top customers, countries, and products by revenue
Segment customers based on purchasing behavior
Enable time-based analysis using interactive slicers
Support data-driven marketing and retention strategies

🧰 Tech Stack

Database / Querying: SQL (PostgreSQL)
Data Processing & Analysis: Python (Pandas, NumPy, Scikit-learn)
Visualization & BI: Power BI (DAX, interactive dashboards)
Clustering Technique: RFM Analysis(Recency, Frequency, Monetary) is a powerful customer segmentation technique that scores customers 
based on how recently they purchased (R), how often they purchase (F), 
and how much money they spend (M) + K-Means

📂 Dataset

Online Retail transactional dataset
Key fields:
Invoice, InvoiceDate
Customer ID
Country
Quantity, Price
Total Spend
Product Description

📐 Data Analysis & Modeling

🔹 SQL Analysis
Key SQL queries were written to answer business questions such as:
Total revenue generated
Top 10 customers and countries by revenue
Revenue contribution by customer segment
Monthly sales trends
Repeat customer analysis
Average Order Value (AOV)

🔹 Customer Segmentation
Customers were segmented using:
Recency – how recently a customer purchased
Frequency – how often they purchased
Monetary – how much they spent
K-Means clustering was applied to classify customers into:
High Value Customers
Loyal Customers
At-Risk Customers
Low Value Customers

📊 Power BI Dashboard Features

KPI Cards

Total Revenue
Total Customers
Total Orders
Average Order Value (AOV)
Visualizations
Revenue trend by year
Top 10 customers by revenue
Revenue by country
Revenue contribution by customer segment
Customer distribution (RFM + K-Means donut chart)
Interactivity
Month slicer for time-based analysis
Cross-filtering across all visuals
Clean executive-style layout with light-blue theme

📌 Key DAX Measures Used

Total Revenue = SUM(OnlineRetail[Total_Spend])
Total Customers = DISTINCTCOUNT(OnlineRetail[Customer ID])
Total Orders = DISTINCTCOUNT(OnlineRetail[Invoice])
AOV =
DIVIDE(
    SUM(OnlineRetail[Total_Spend]),
    DISTINCTCOUNT(OnlineRetail[Invoice])
)

💡 Insights Generated

A small percentage of customers contribute a majority of revenue
High-value and loyal customers drive long-term business growth
Certain countries dominate overall sales performance
Seasonal trends significantly impact revenue

🚀 Outcome

This dashboard enables:
Executive-level performance monitoring
Customer targeting and retention strategies
Data-driven decision-making for sales and marketing teams



