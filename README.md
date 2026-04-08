# Vendor_Performance_Analysis
## Overview
This project focuses on analyzing vendor performance using sales, purchase, and inventory data.
It helps identify top-performing vendors, low-performing vendors, and areas where capital is stuck in unsold inventory.

## Objectives
* Analyze vendor-wise sales and profitability
* Identify high and low performing vendors
* Track unsold inventory and capital
* Generate actionable business insights
  
## Tech Stack
* **Python** (Data processing & analysis)
* **SQL (SQLite)** (Database management)
* **Pandas** (Data manipulation)
* **Power BI** (Interactive dashboard & visualization)

## Project Structure

```
├── data/
│   ├── sales.csv
│   ├── purchases.csv
│   ├── vendor_invoice.csv
│   ├── begin_inventory.csv
│   ├── end_inventory.csv
│   └── purchase_prices.csv
│
├── scripts/
│   ├── ingestion_db.py
│   ├── get_vendor_summary.py
│
├── notebooks/
│   ├── Exploratory Data Analysis.ipynb
│   ├── Vendor Performance Analysis.ipynb
│
├── database/
│   └── inventory.db
│
├── output/
│   └── vendor_sales_summary.csv
│
├── dashboard/
│   └── vendor_sales_dashboard.pbix
```
## Key Metrics
* Total Sales
* Total Purchase
* Gross Profit
* Profit Margin (%)
* Unsold Capital
* Stock Turnover

## Dashboard Highlights
* Top Vendors by Sales
* Low Performing Vendors
* Profit Margin Analysis
* Purchase Contribution %
* Brand-wise & Product-wise Insights
  
## Key Insights
* Some vendors generate high revenue but low profit margins
* Unsold inventory contributes significantly to capital blockage
* A few vendors dominate overall sales contribution

## Conclusion
This project demonstrates how data analytics can be used to evaluate vendor performance, optimize inventory, and support better business decisions.

## If you found this useful, consider giving it a star!

