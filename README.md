# Procurement & Supplier Performance Analytics Dashboard

## Project Overview

This project involves the development of an interactive **Procurement Analytics Dashboard in Microsoft Excel**, using SAP-style procurement data to evaluate purchasing activities, supplier performance, material spending, and delivery efficiency.

**Excel Workbook:** [View / Download the Excel Dashboard on Kaggle](https://www.kaggle.com/datasets/kazzyagu/procurement-performance-analytics-dashboard)

The goal was to transform raw procurement records into actionable business insights that could help management monitor expenditure, identify supplier risks, track outstanding orders, and improve procurement decision-making.

The dashboard was designed around practical business questions that procurement and operations teams need to answer.

## Business Objectives

The analysis focused on five key areas:

1. **Procurement Overview:** How much are we spending, how much have we ordered, and what is our outstanding financial exposure?
2. **Material Analysis:** Which materials and categories account for the highest purchasing expenditure?
3. **Supplier Analysis:** Which suppliers account for the largest share of procurement spending, and where is financial exposure concentrated?
4. **Delivery Performance:** Are suppliers delivering orders on time and in full?
5. **Management Decision Support:** What areas require attention, and where should management prioritize improvement efforts?

## Tools & Technologies

- **Microsoft Excel** – Dashboard development and reporting
- **Power Query** – Data cleaning and transformation
- **Power Pivot** – Data modelling and relationship management
- **DAX** – Measures, calculated metrics, and analytical calculations
- **PivotTables & PivotCharts** – Data analysis and visualization
- **Excel Slicers & Timelines** – Interactive filtering
- **VBA** – Dashboard reset functionality and user interaction

## Dashboard Modules

The project consists of four interconnected dashboard pages.

### 1. Procurement Overview

Provides a high-level summary of procurement activities and overall performance.

Key metrics:
- Total Purchasing Spend
- Total Ordered Quantity
- Delivery Completion Rate
- Late Delivery Rate
- Outstanding Financial Exposure
- Outstanding Quantity
- Goods Received Quantity

### 2. Materials Analysis

Examines procurement expenditure across materials and material categories.

Key analyses:
- Purchasing Spend by Material Category
- Top Five Materials by Purchasing Spend
- Material Category Spending Trends
- Material Spend Concentration
- Average Purchase Order Value

### 3. Supplier Analysis

Evaluates supplier spending patterns, purchasing concentration, and outstanding financial exposure.

Key analyses:
- Top Five Suppliers by Purchasing Spend
- Supplier Spending Trends
- Supplier Spend Concentration
- Supplier Delivery Performance
- Outstanding Exposure by Supplier
- Supplier Purchasing Patterns

### 4. Delivery Performance

Assesses supplier delivery reliability and the extent to which ordered quantities have been fulfilled.

Key analyses:
- On-Time Delivery Performance
- Late Delivery Rate
- Delivery Performance Trends
- Delivery Performance by Plant
- Ordered Quantity vs. Goods Received
- Delivery Completion by Material Category
- Outstanding Quantity by Material Category

## Key Findings & Business Insights

The analysis revealed several areas requiring management attention.

| Performance Indicator | Result |
|---|---:|
| Total Purchasing Spend | $21.83M |
| Total Ordered Quantity | 30,616 |
| Total Goods Received | 21,817 |
| Delivery Completion Rate | 71.26% |
| Outstanding Quantity | 8,799 |
| On-Time Delivery Rate | 5.81% |
| Late Delivery Rate | 94.19% |
| Outstanding Financial Exposure | $6.71M |
| Outstanding Exposure as % of Spend | 30.72% |
| Total Suppliers | 18 |
| Total Purchase Orders | 210 |

### Major Business Insights

**1. Significant Outstanding Financial Exposure**

Approximately $6.71M, representing 30.72% of total purchasing spend, remains outstanding. This highlights the need for closer monitoring of unfulfilled purchase orders and associated financial commitments.

**2. Poor Supplier Delivery Timeliness**

The overall late delivery rate stands at 94.19%, while only 5.81% of deliveries were classified as on time. This indicates a substantial delivery reliability problem requiring supplier performance reviews and stronger delivery monitoring.

**3. Low Delivery Completion**

Only 71.26% of ordered quantities have been received, leaving 8,799 units outstanding. This creates potential operational and material availability challenges.

**4. Supplier Spending Concentration**

The five largest suppliers account for approximately 47.55% of total purchasing expenditure, highlighting the importance of monitoring supplier concentration and dependency.

**5. Concentration of Outstanding Exposure**

The five suppliers with the highest outstanding exposure account for approximately $4.04M, or 60.2% of total outstanding exposure. Pioneer Safety Systems has the highest individual outstanding financial exposure at approximately $1.93M.

**6. Material Spending Concentration**

Instrumentation is the largest purchasing category, accounting for approximately $7.84M or 35.94% of total procurement expenditure.

## Data Preparation & Analytical Approach

The project followed a structured data analytics workflow:

1. **Data Preparation:** Imported and transformed procurement records using Power Query.
2. **Data Modelling:** Loaded the prepared data into the Excel Data Model using Power Pivot.
3. **Metric Development:** Created DAX measures to calculate procurement spending, delivery completion, supplier performance, and outstanding exposure.
4. **Exploratory Analysis:** Used PivotTables and PivotCharts to investigate purchasing patterns, supplier concentration, and delivery performance.
5. **Dashboard Development:** Built four interactive dashboard pages with slicers and timelines.
6. **Automation:** Implemented VBA functionality to reset dashboard filters and improve usability.

## Business Value

The dashboard demonstrates how procurement data can be used to support:

- Better visibility into purchasing expenditure.
- Identification of high-spending suppliers and materials.
- Monitoring of outstanding purchase orders and financial exposure.
- Supplier performance evaluation.
- Identification of delivery bottlenecks.
- More informed procurement and operational decisions.

## Project Outcome

This project demonstrates the application of Excel-based data analytics to a practical procurement management scenario, combining data transformation, data modelling, DAX calculations, interactive visualization, and business interpretation.

**The objective was not just to build a dashboard, but to turn procurement data into information that management can use to make better decisions.**

---

**Author:** Kc Agu  
**Tools:** Microsoft Excel | Power Query | Power Pivot | DAX | VBA  
**Domain:** Procurement Analytics | Supplier Performance | Operational Analytics
