# Technical Workflow

## 1. Data Sources

The dashboard integrates multiple source files covering sales, products, stores, locations, and store-related costs.

### Source Files

- `sales2017_raw.csv` — Raw sales data for 2017
- `sales2018.csv` — Sales data for 2018
- `sales2019.csv` — Sales data for 2019
- `producthierarchy.csv` — Product hierarchy and product classification
- `store_cities.csv` — Store and geographic information
- `Store costs.xlsx` — Store-related cost information

---

## 2. Data Preparation

The source data is prepared before being used for dashboard analysis.

Typical preparation activities include:

- Reviewing source data structure and data types
- Identifying missing or inconsistent values
- Checking duplicate records
- Standardizing column formats
- Validating dates and numeric fields
- Preparing data for integration
- Ensuring consistent fields across yearly sales datasets

---

## 3. Data Transformation

Power Query is used to prepare and transform the source data.

The transformation workflow includes:

1. Importing CSV and Excel data
2. Reviewing column names and data types
3. Cleaning and standardizing source fields
4. Transforming sales data into an analysis-ready structure
5. Combining yearly sales data where appropriate
6. Preparing product and store reference data
7. Integrating geographic and cost information
8. Validating the transformed datasets

---

## 4. Data Modeling

The transformed datasets are organized into a Power BI data model.

The model is designed to connect:

- Sales transactions
- Product information
- Store information
- Geographic information
- Store costs

The objective is to create a structured analytical model that supports filtering, aggregation, KPI calculations, and cross-analysis.

---

## 5. DAX and Measures

DAX is used to create analytical measures and calculated metrics.

Measures are designed to support areas such as:

- Sales performance
- Product performance
- Geographic performance
- Store performance
- Logistics and cost analysis
- KPI reporting
- Time-based analysis

The use of measures allows calculations to respond dynamically to filters and user selections.

---

## 6. KPI Development

The dashboard uses KPI-based analysis to monitor business performance.

Key analytical areas include:

- Sales performance
- Product/category performance
- Geographic performance
- Store performance
- Logistics costs
- Cost-related indicators
- Time-based performance trends

---

## 7. Dashboard Development

The Power BI dashboard is designed to provide an interactive analytical experience.

The visualization layer converts the underlying data model and DAX measures into business-facing reports.

The dashboard focuses on:

- Executive-level KPIs
- Sales trends
- Product analysis
- Geographic analysis
- Store analysis
- Logistics and cost analysis

---

## 8. Interactive Features

Interactive Power BI functionality can be used to explore the data dynamically.

Examples include:

- Filters and slicers
- Cross-filtering
- Drill-down analysis
- Date-based analysis
- Product-level analysis
- Geographic filtering
- Store-level analysis
- Interactive KPI exploration

---

## 9. Analytical Workflow

The overall technical workflow is:

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
        ↓
Recommendations
