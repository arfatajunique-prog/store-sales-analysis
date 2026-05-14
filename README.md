# Store Sales Analysis

## Overview

This repository contains a Power BI dashboard for analyzing an e-commerce store's sales performance.
The dashboard uses the provided datasets to visualize revenue, profit, product categories, and geographic trends.

## Files

* `E-commerce Sales Dashboard.pbix` — Power BI report file
* `dataset/Details.csv` — transaction-level sales data
* `dataset/Orders.csv` — order metadata and customer location data

## How to use

1. Install Microsoft Power BI Desktop.
2. Open `E-commerce Sales Dashboard.pbix` in Power BI.
3. Use the built-in filters and slicers to explore sales by category, payment mode, region, and customer orders.

## Data

* `Details.csv`: `Order ID`, `Amount`, `Profit`, `Quantity`, `Category`, `Sub-Category`, `PaymentMode`
* `Orders.csv`: `Order ID`, `Order Date`, `CustomerName`, `State`, `City`

## Additional documentation

* `analysis-summary.md` — coded summary of dataset insights and recommendations
* `DATA_DICTIONARY.md` — definitions for each dataset field

## Tools

* Microsoft Power BI Desktop

## Notes

* The dashboard is owned and maintained by me.
* If you want to refresh the data in the report, use the CSV files in the `dataset/` folder.

## Badges

![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

