# NIKE Sales Intelligence | Power BI Dashboard

An interactive Power BI project exploring sales performance, product profitability, retailer contribution, geographic performance and business insights using a synthetic retail dataset.

> **Disclaimer:** This is an independent educational portfolio project. The dataset is synthetic and does not represent actual Nike sales, financial results or company performance. This project is not affiliated with or endorsed by Nike.

## Project Overview

The objective is to transform retail sales data into an interactive business intelligence report that helps users explore performance across products, retailers, geographies and time.

## Dashboard Pages

1. **Executive Overview** — Overall sales performance, KPIs and monthly trends.
2. **Product Analysis** — Product revenue, profitability and sales volume.
3. **Retailer Analysis** — Retailer contribution, orders and profitability.
4. **Geography Analysis** — State-level sales and profit performance.
5. **Business Insights** — Decomposition tree, sales and profit trends, product contribution and key influencers.

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data modelling and visualization

## Key Measures

- Total Sales
- Total Profit
- Total Units Sold
- Total Orders
- Profit Margin
- Average Order Value

## Dataset

The practice dataset contains six worksheets:

- FactOrders
- DimProduct
- DimRetailer
- DimGeography
- DimDate
- ReadMe_DataDictionary

The dataset contains 6,500 fictional orders and covers January 2023 to December 2025.

All financial and cost values are simulated for learning and demonstration.

## Data Model

The project uses a dimensional model with FactOrders connected to the Product, Retailer, Geography and Date dimension tables.

## Repository Structure

```text
NIKE-Sales-Intelligence/
├── Dashboard/
├── Dataset/
├── Screenshots/
└── README.md
```

## Learning Outcomes

- Data cleaning and transformation using Power Query
- Building relationships in a dimensional data model
- Creating DAX measures
- Designing interactive dashboards
- Applying filters, slicers and page navigation
- Developing business insights from sales data

## Author

Independent Power BI portfolio project.
