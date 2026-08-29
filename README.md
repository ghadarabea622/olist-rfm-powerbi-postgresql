# Olist RFM Customer Analysis | PostgreSQL & Power BI

## Project Overview

This project analyzes customer purchasing behavior using the Brazilian Olist e-commerce dataset.

The main objective was to build an RFM (Recency, Frequency, Monetary) customer segmentation model and create an interactive Power BI dashboard that helps identify valuable customers, inactive customers, and customer groups that require attention.

## Tools & Technologies

- PostgreSQL
- SQL
- Power BI
- Power Query
- DAX
- Git & GitHub

## Dataset

The project includes seven main datasets:

- Customers
- Orders
- Order Items
- Payments
- Products
- Reviews
- Sellers

The datasets were loaded into PostgreSQL and connected directly to Power BI for analysis and visualization.

## RFM Analysis

Customers were analyzed based on three key metrics:

- **Recency:** How recently a customer placed an order
- **Frequency:** How often a customer purchased
- **Monetary:** How much a customer spent

Customers were then classified into segments including:

- Champions
- Loyal Customers
- Potential Loyalists
- Need Attention
- At Risk
- Lost Customers

## Dashboard KPIs

The dashboard provides the following key metrics:

- **Total Customers:** 93K+
- **Total Orders:** 99K+
- **Total Revenue:** R$ 15.42M
- **Average Customer Value:** R$ 165.17

## Dashboard Analysis

The Power BI dashboard includes:

- Customer distribution by RFM segment
- Revenue by customer segment
- Customers by recency group
- Customers by purchase frequency
- Customers by spending level
- R Score distribution
- Detailed customer-level RFM table
- Interactive customer segment filter

## Data Model

The Power BI data model connects:

- Customers → Orders
- Orders → Order Items
- Orders → Payments
- Orders → Reviews
- Products → Order Items
- Sellers → Order Items
- Customer RFM → Customers

Relationships were designed using appropriate one-to-many relationships and single-direction filtering.

## Key Insights

- A large proportion of customers purchased only once.
- Potential Loyalists represent one of the largest customer groups.
- Customers with higher recency values represent opportunities for re-engagement campaigns.
- A relatively small group of customers contributes significantly higher monetary value.
- RFM segmentation can support targeted marketing and customer retention strategies.

## Skills Demonstrated

- Relational data modeling
- PostgreSQL database integration
- SQL-based data analysis
- Customer segmentation
- RFM analysis
- DAX measures
- Power Query
- Power BI dashboard development
- Data visualization
- Business insight generation

## Project File

The complete Power BI report is available in:

`Olist_RFM_Analysis.pbix`

## Author

**Ghada Rabie Wafdy**

Data Engineering & Data Analytics
