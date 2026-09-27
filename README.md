# Supply Chain & Logistics Performance Analysis

## 📌 Project Overview

This project analyses **sales, profitability, supplier performance, and logistics operations** using Microsoft Excel.

The analysis uses three related datasets — **Orders, Suppliers, and Shipments** — and demonstrates an end-to-end analytics workflow from raw data cleaning and validation to data modelling, KPI development, interactive dashboard creation, and business insights.

The final dashboard allows users to explore business performance using interactive filters for product category, customer region, order status, and delivery status.

---

## Project Objectives

The main objectives were to:

- Clean and transform raw supply chain data
- Identify and resolve data-quality issues
- Build relationships between multiple datasets
- Analyse sales, profit, orders, suppliers, and shipments
- Monitor delivery and logistics performance
- Create business KPIs
- Build an interactive Excel dashboard
- Generate meaningful business insights

---

## Tools Used

- Microsoft Excel
- Power Query
- Power Pivot
- DAX
- PivotTables
- PivotCharts
- Excel Data Model
- Slicers

---

## Data

The project contains three datasets:

### Orders
Contains order-level information, including product category, customer region, quantity, sales, cost, profit, and order status.

### Suppliers
Contains supplier information, including supplier name, country, lead time, and quality rating.

### Shipments
Contains logistics information including carrier, shipping mode, shipping cost, delivery dates, and delivery status.

### Data Model

The datasets were connected using:

`Suppliers[Supplier_ID] → Orders[Supplier_ID]`

`Orders[Order_ID] → Shipments[Order_ID]`

---

## Data Cleaning & Transformation

Power Query was used to prepare the raw datasets before analysis.

Key steps included:

- Handling missing and blank values
- Checking duplicate records
- Correcting data types
- Trimming and standardising text
- Standardising inconsistent categories
- Validating sales and shipping costs
- Checking date-related issues
- Creating corrected sales and shipping fields
- Calculating profit and profit margin
- Creating consistent delivery-status classifications

The cleaned datasets were then loaded into the Excel Data Model for analysis.

---

## Key KPIs

| KPI | Result |
|---|---:|
| Total Sales | £817.46M |
| Total Orders | 99,452 |
| Total Profit | £253.48M |
| Profit Margin | 31.01% |
| Average Order Value | £8,220 |
| Total Quantity Sold | 5.03M |

---












