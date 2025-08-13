# 🛒 Power BI Retail Sales & Cost Analysis Dashboard

## 📌 Project Overview
This project showcases an **end-to-end Power BI report** built using a retail dataset to analyze **sales performance, store operations, and cost targets**.  
The report provides **interactive dashboards** for tracking revenue, store performance, and wage-to-sales efficiency across multiple U.S. states.

---

## 🎯 Objective
To design and develop a **Retail Sales & Cost Analysis dashboard** enabling business stakeholders to:
- Monitor **total sales, gross sales, and departmental performance**.
- Compare store types and locations for operational insights.
- Track **costs, wages, and rent** against set targets.
- Enable **interactive filtering** for deeper business insights.

---

## 🛠 Tools & Technologies
- **Power BI** – Dashboard creation, DAX measures, and visualizations  
- **Power Query** – Data cleaning, transformation, and modeling  
- **DAX** – Calculated columns, measures, and KPI logic  
- **Retail Dataset** – Contains store-level sales, costs, wages, and rent data  

---

## 📊 Key Features
1. **Sales Analysis Dashboard**
   - KPI Cards for **Total Sales**, **Total Gross Sales**, and **Total Sales by Department**.
   - Department slicer for Clothing, Electronics, Garage, Kitchen, and Other categories.
   - Sales breakdown by:
     - Store Location & Department (Sankey-style flow chart)
     - Store Type & Department (stacked column chart)
     - Geographic map visualization of store performance.
   
2. **Cost & Target Dashboard**
   - KPI Card for **Sales Target Tracking** with variance percentage.
   - Date slicer for custom time period analysis.
   - Wages vs Sales table with **conditional formatting** to highlight over/under target performance.
   - Scatter chart mapping **Total Rent vs Store Size** for cost efficiency insights.

---

## 📌 Steps Involved
1. **Data Acquisition**
   - Imported retail dataset into Power BI.
   - Verified data types and relationships.

2. **Data Cleaning & Transformation (Power Query)**
   - Removed nulls and duplicates.
   - Created normalized dimension tables for Department, StoreType, and Date.

3. **Data Modeling**
   - Established relationships between fact and dimension tables.
   - Implemented **Star Schema** for performance optimization.

4. **DAX Calculations**
   - Created **KPI measures** for Total Sales, Gross Sales, and Target Achievement.
   - Built CALCULATE-based measures for department-specific sales.
   - Developed variance measures for **Target vs Actual**.

5. **Report Design**
   - Designed **Sales** and **Cost & Target** dashboards.
   - Applied slicers, filters, and drill-throughs for interactivity.
   - Used consistent color themes for brand alignment.

6. **Final Touches**
   - Added navigation buttons between report pages.
   - Enhanced visuals with custom formatting and labels.

---


---

## 💡 Key Insights
- **Clothing** category leads in total sales across **CORE stores**.
- Certain states like **West Virginia and Washington** outperform in sales despite higher wages.
- Digital stores have lower rent but also smaller sales volumes compared to core stores.

---

