# 🛍️ E-Commerce Sales Dashboard – Power BI Project



## 📊 Project Overview

This project is an **E-Commerce Sales Dashboard** built using **Power BI**, designed to provide an interactive and insightful analysis of business performance.  
The dashboard showcases key metrics such as **Year-To-Date (YTD) Sales**, **Profit**, **Quantity**, **Profit Margin**, and **Sales Trends** by category, region, and shipment type.

---

## 🧠 Objectives

- Analyze **overall sales performance** and **profit trends**.
- Compare **YTD vs PYTD** (Previous Year-To-Date) metrics.
- Identify **top and bottom performing products**.
- Understand **regional performance** and **shipment type distribution**.
- Provide data-driven insights for **strategic business decisions**.

---

## ⚙️ Data Workflow

### 1. **Data Sources**
- Raw e-commerce sales data (CSV/Excel files)
- Cleaned and transformed data in **SQL**
- Final dataset imported into **Power BI**

### 2. **Data Cleaning & Preparation**
Performed in **Excel** and **SQL**:
- Removed duplicates and null values  
- Standardized data types (dates, numbers, text)
- Created relationships between fact and dimension tables  
- Used **CTEs, Window Functions, and String Functions** in SQL for preprocessing

### 3. **Data Modeling in Power BI**
- Established relationships between tables (Sales, Customer, Product, Category)
- Defined **Star Schema** model for optimized performance
- Used **Calculated Columns** and **Measures** for KPIs

---

## 🧮 DAX Functions Used

Implemented **Advanced DAX** for time intelligence and dynamic calculations:

| Function | Purpose |
|-----------|----------|
| `TOTALYTD()` | Calculates Year-To-Date Sales/Profit |
| `SAMEPERIODLASTYEAR()` | Compares current period to last year |
| `DATEADD()` | Shifts time periods for trend analysis |
| `VAR` and `RETURN` | Simplifies complex measures using variables |
| `CALCULATE()` | Applies context-based filters |
| `DIVIDE()` | Handles safe division for ratio calculations |
| `IF()`, `SWITCH()` | Conditional logic for measures |

---

## 📈 Key Metrics & KPIs

| KPI | Description |
|-----|--------------|
| **YTD Sales** | Total sales achieved so far this year |
| **YTD Profit** | Profit generated for the current year |
| **YTD Quantity** | Number of units sold year-to-date |
| **YTD Profit Margin** | Profit percentage based on YTD Sales |
| **YoY Growth** | Year-over-Year sales comparison |

---

## 🗺️ Dashboard Features

- **Sales by Category**: Furniture, Technology, and Office Supplies  
- **Top 5 & Bottom 5 Products by Sales**  
- **YTD Sales by Region & Shipment Type**  
- **Sales Map by States (Geo Visualization)**  
- **Interactive filters** by Segment (Consumer, Corporate, Home Office)  
- **Dynamic visuals** with color-coded trend indicators  

---

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| **Microsoft Excel** | Initial data cleaning and inspection |
| **SQL (PostgreSQL)** | Advanced data transformation |
| **Power BI Desktop** | Data modeling, DAX, and dashboard creation |
| **GitHub** | Version control and portfolio showcasing |

---

## 🎯 Insights Derived

- **Office Supplies** category had the **highest sales** but a **negative YoY trend (-4.67%)**.  
- **Technology** category showed **steady growth (+1.20%)**.  
- **West Region** contributed the **largest share (31.7%)** to total sales.  
- **Standard Class** shipments formed **over 60%** of total deliveries.  
- **Top-performing product:** *Easy-Staple Paper*.  

---

## 🧩 Future Enhancements

- Add **dynamic date slicers** for better time-based filtering.  
- Integrate **Power BI Service refresh scheduling** for live updates.  
- Automate data ingestion using **Power Automate or Azure Data Factory**.  
- Build **Power BI report page tooltips** for detailed insights.

---



