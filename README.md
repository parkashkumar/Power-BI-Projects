# Sales Performance & Logistics Analytics Dashboard

An interactive Power BI dashboard designed to analyze sales performance, revenue, product categories, geographic performance, and logistics costs across multiple years.

The project demonstrates an end-to-end Business Intelligence workflow, from raw data preparation and Power Query transformation to data modeling, DAX measures, KPI development, interactive visualization, and business insights.

---

## Dashboard Preview

### Executive Overview

![Dashboard Overview](00_Overview.png.png)

### Sales Analysis

![Sales Analysis](02_Sales_Analysis.png.png)

### Cost & Logistics Analysis

![Cost & Logistics Analysis](03_Cost_Logistics_Analysis.png.png)

### Revenue Analysis by Category

![Revenue by Category](04_Revenue_AnalysisBy%20category.png.png)

### Sales by Region and Date

![Sales by Region and Date](04_Sales%20by%20region,%20date_Analysis.png.png)

### Interactive Product Tooltip

![Product Tooltip](Tooltips%20feature%20by%20product.png)

---

## Business Objectives

The dashboard was developed to provide an interactive view of business performance and answer key analytical questions, including:

- How are sales performing over time?
- Which products and categories generate the highest revenue?
- Which regions and stores contribute most to sales?
- How do logistics and store costs affect performance?
- How does performance change across different periods?
- Which products or locations require further investigation?

---

## Key Analytical Areas

### Sales Performance

Analysis of sales trends and performance across different periods, products, stores, and regions.

### Product & Category Analysis

Evaluation of product-level and category-level revenue performance to identify high-performing areas.

### Geographic Performance

Analysis of sales across regions and locations to understand geographic performance patterns.

### Logistics & Cost Analysis

Analysis of store and logistics-related costs alongside sales performance.

### Time-Based Analysis

Interactive analysis of performance across multiple years and reporting periods.

---

## Data Sources

The dashboard integrates multiple data sources:

| Source | Description |
|---|---|
| `sales2017_raw.csv` | Sales data for 2017 |
| `sales2018.csv` | Sales data for 2018 |
| `sales2019.csv` | Sales data for 2019 |
| `producthierarchy.csv` | Product hierarchy information |
| `store_cities.csv` | Store and geographic information |
| `Store costs.xlsx` | Store-related cost information |

---

## Technical Workflow

```text
Raw CSV / Excel Data
        ↓
Data Profiling
        ↓
Data Cleaning
        ↓
Power Query Transformation
        ↓
Data Integration
        ↓
Data Modeling
        ↓
Relationships
        ↓
DAX Measures
        ↓
KPI Development
        ↓
Dashboard Development
        ↓
Interactive Analysis
        ↓
Business Insights
