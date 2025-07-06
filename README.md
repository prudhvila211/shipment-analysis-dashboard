# 📦 Shipment Analysis Dashboard – Power BI Project

*By Challagundla Pavani Prudhvila*

## 📁 Project Overview

This Power BI project provides an interactive and insightful dashboard for analyzing shipment data. It was developed as part of my self-learning journey to strengthen my skills in data modeling, DAX, and data visualization. The goal was to build a robust reporting solution that tracks shipment performance across locations, product categories, and sales personnel over time.

📁[Download powerBi Dashboard(.pbix)] (https://github.com/prudhvila211/shipment-analysis-dashboard/raw/refs/heads/main/chocolate.pbix)



## 🧱 Data Model Design

A star schema was implemented to ensure performance and clarity. The central fact table (Shipments) was connected to multiple dimension tables:

- *Shipments (Fact Table):* Order status, shipment date, product ID, sales ID, region, cost, boxes, and amount  
- *Products:* Product ID, Product Name, Category, Cost per Box  
- *People (Sales):* Salesperson ID, Name, Picture  
- *Locations:* Geographic ID, Region, Geo  
- *Calendar:* Date, Month, Year, Weekday (for time-based analysis)  

This model allows flexible slicing and aggregation of shipment data across multiple dimensions.



## 📊 Dashboard Highlights

The Power BI dashboard includes:

- Shipment Volume and Cost Breakdown  
- Regional and Product Category Analysis  
- Salesperson Performance Tracker  
- Time-series Filtering with a Calendar Table  
- Box and Amount Metrics by Status (Completed, In Transit, Cancelled)  

Dynamic filters enable users to interact with the report and drill down into specific time periods, regions, or product lines.


## 🛠 Tools & Technologies Used

- Power BI Desktop  
- DAX (Data Analysis Expressions)  
- Star Schema Data Modeling  
- Excel/CSV (Data Source)
- ## 🎯 Key Learnings

- How to structure an effective star schema for BI reporting  
- Writing basic to intermediate DAX measures  
- Using slicers and visuals to enhance user interactivity  
- Creating KPI cards, bar/line charts, donut charts, and matrix views  
- Designing a clean, functional layout that tells a story


