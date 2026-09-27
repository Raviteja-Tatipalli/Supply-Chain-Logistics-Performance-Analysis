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
Contains logistics information, including carrier, shipping mode, shipping cost, delivery dates, and delivery status.

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

## Dashboard Visualisations

The final dashboard contains eight analytical visuals:

1. Sales by Product Category
2. Profit by Product Category
3. Delivery Status Distribution
4. Shipping Cost by Shipping Mode
5. Orders by Region
6. Shipments by Carrier
7. Supplier Quality Performance
8. Monthly Sales Trend

### Interactive Filters

The dashboard includes four slicers:

- Product Category
- Customer Region
- Order Status
- Delivery Status

These allow users to dynamically explore different areas of business and logistics performance.

---

## 💡 Key Business Insights

- The business generated approximately **£817.46M in sales** and **£253.48M in profit** across 99,452 orders.

- Sales and profit are relatively evenly distributed across product categories, indicating a balanced product portfolio.

- Approximately **64.83% of shipments were delivered on time**, while **34.66% were delayed**, making delivery performance an important area for further investigation.

- Standard shipping accounted for the largest total shipping expenditure at approximately **£2.03M**.

- Shipment volumes are distributed relatively evenly across DHL, DPD, Royal Mail, UPS, and FedEx, reducing reliance on a single carrier by volume.

- Regional order volumes are also relatively balanced, although approximately **698 orders have an Unknown region**, indicating a small data-quality improvement opportunity.

- Sales increased slightly from approximately **£407.4M in 2024 to £410.1M in 2025**.

- Supplier quality ratings vary across suppliers, allowing lower-performing suppliers to be identified for further investigation.

---

## 💼 Business Recommendations

Based on the analysis:

- Investigate delayed shipments by carrier, supplier, shipping mode, and region.
- Monitor supplier quality and lead-time performance.
- Compare shipping cost per shipment rather than total shipping cost alone.
- Improve customer-region data quality.
- Continue monitoring category profitability and monthly sales trends.
- Use the interactive dashboard to identify operational performance issues.

---

## 📸 Dashboard

![Supply Chain & Logistics Performance Dashboard](images/Supply Chain Dashboard%20(1).png)

---

## 🔄 Project Workflow

**Raw Data → Data Quality Assessment → Power Query Cleaning → Validation → Data Model → DAX Measures → PivotTables → PivotCharts → Interactive Dashboard → Business Insights**

---

## 🎯 Skills Demonstrated

- Data Cleaning & Transformation
- Power Query
- Data Validation
- Data Modelling
- Power Pivot
- DAX
- PivotTables & PivotCharts
- KPI Development
- Dashboard Design
- Data Visualisation
- Business Analysis
- Supply Chain & Logistics Analytics

---

## 📌 Conclusion

This project demonstrates an **end-to-end Excel analytics workflow**, transforming raw supply chain data into an interactive business dashboard.

The analysis shows relatively balanced sales and profitability across product categories and regions, while highlighting **delivery delays as a key operational area for further investigation and improvement**.






