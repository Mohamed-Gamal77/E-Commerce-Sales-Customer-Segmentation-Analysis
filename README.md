# E-Commerce Sales & Customer Segmentation

## Project Overview
This project analyzes e-commerce transactional data to evaluate Sales performance, Customer behavior, Revenue Distribution.
the objective is to extract actionable business insights and support decision-making through data analysis and interactive dashboards.

## Dashboards Preview

### Main Dashboard
![Main Dashboard](screenshots/Main%20Dashboard.png)

### RFM Dashboard
![RFM Dashboard](screenshots/RFM%20Dashboard.png)

## Dataset Description
- Transaction-level e-commerce data
- Includes customer, country, and revenue information
- The original dataset contained approximately **540K transactions**, which was reduced to **500K high-quality records** after data cleaning

## Key Columns
- InvoiceDate
- CustomerID
- Invoice
- Quantity
- Price
- Revenue

## Data Cleaning & Preparation
The dataset was cleaned and validated to ensure analytical accuracy.
This process addressed missing customer identifiers, invalid transactions, and inconsistent date formats.

## Sales Performance

### Revenue by Country
Revenue is highly concentrated in THE UK.
The top 10 countries generate the majority of total revenue, indicating geographic concentration and opportunities for focused market expansion.

### Revenue Trend Over Time
Monthly revenue shows a generally stable trend with seasonal fluctuations.
This consistency supports predictable sales behavior and better planning.

## Customer Segmentation (RFM Analysis)
Customers were segmented using Recency, Frequency, and Monetary (RFM) analysis to identify high-value and at-risk customers.

### Key Segments:

**Champions**
Most valuable customers with frequent and recent purchases, contributing the highest share of revenue.

**Loyal Customers**
Consistent buyers with strong engagement, ideal for retention and upselling strategies.

**Can't Lose Them**
High-spending customers with declining activity, representing a critical reactivation opportunity.

**At Risk**
Previously active customers showing signs of churn.

**Potential Loyalists**
Recent customers with strong growth potential.

## Recommendations
- Prioritize retention strategies for Champions and Loyal Customers.
- Launch re-engagement campaigns for Can't Lose Them and At Risk segments.
- Focus marketing efforts on top-performing countries while testing new markets.
- Track customer behavior over time to detect early churn signals.

## Tools & Technologies

- Python (Pandas)
- SQL
- Power BI

- Jupyter Notebook
