# Online Retail Sales & Customer Analytics

End-to-end business analytics project using **Python, MySQL, RFM segmentation, and Power BI** to analyze more than 1 million online retail transactions.

<img src="Online retail sales & customer analytics.jpg" width="700">

## Project Overview

This project analyzes retail transactions from 2009–2011 to understand:

- Revenue performance over time
- Country-level sales
- Top-performing products
- Customer behavior
- Cancellations and net revenue
- RFM customer segments

## Key Results

- Gross Revenue: **£20.48M**
- Net Revenue: **£19.01M**
- Total Orders: **40K**
- Identified Customers: **5.9K**
- Average Order Value: **£510.92**
- United Kingdom contributed about **85% of total revenue**
- Strong seasonal revenue peaks appeared toward the end of the year

## Customer Segmentation

Customers were segmented using **RFM analysis**:

- Champions
- Loyal Customers
- Potential Loyalists
- Regular Customers
- At Risk
- Lost Customers

The analysis showed that high-value customers contribute a large share of customer revenue, while the At Risk segment contains previously valuable customers who may be suitable for re-engagement.

## Tools

- **Python / Pandas** — cleaning, EDA, RFM segmentation
- **MySQL** — aggregations, joins, CTEs, window functions
- **Power BI** — data modeling, DAX, slicers, interactive dashboard
- **Matplotlib** — exploratory visualizations

## Data Preparation

Key preprocessing steps included:

- Combining two yearly datasets
- Removing exact duplicates
- Separating sales, cancellations, and operational adjustments
- Investigating negative quantities and unusual transactions
- Calculating gross and net revenue
- Standardizing customer IDs
- Creating customer-level RFM metrics

# Dashboard
The dashboard includes:
- KPI cards
- Monthly revenue trend
- Revenue by country
- Top products by revenue
- Customers by segment
- Interactive slicers for year, country, and customer segment
