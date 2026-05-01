# AdventureWorks Business Intelligence Dashboard (Power BI)

## Project Overview
This project was developed as part of a Business Intelligence Analyst role simulation at AdventureWorks, a global manufacturing company specializing in cycling equipment and accessories.

The objective was to transform raw CSV data into a structured data model and build an interactive Power BI dashboard to track KPIs, analyze trends, and support business decision-making.

---

## Business Objective
- Track key performance indicators (Revenue, Profit, Orders, Return Rate)  
- Compare regional sales performance  
- Analyze product-level trends  
- Identify high-value customers  

---

## Tools and Technologies
- Microsoft Power BI Desktop  
- Power Query (Data Transformation)  
- Data Modeling (Star Schema)  
- DAX (Calculated Columns and Measures)  

---

## Dataset
- Source: AdventureWorks raw CSV files  
- Tables: Sales, Returns, Products, Customers, Territories  
- Time Period: 2020 – 2022  

---

## Data Preparation
- Connected multiple CSV files in Power BI  
- Cleaned and transformed data using Power Query  
- Built relationships between tables  
- Created calculated measures for KPIs  

---

# DASHBOARD REPORTS

## 1. Executive Dashboard

### Key Metrics
- Revenue: 24.9M  
- Profit: 10.5M  
- Orders: 25.3K  
- Return Rate: 2.2% :contentReference[oaicite:0]{index=0}  

### Insights
- Revenue shows strong upward growth trend from 2020 to 2022  
- Accessories generate the highest number of orders (17K)  
- Bikes and Clothing follow with 13.9K and 7K orders respectively :contentReference[oaicite:1]{index=1}  

### Visualization
![Executive Dashboard](exec_dashboard.png)

---

## 2. Regional Analysis (Map)

### Objective
Analyze sales distribution across global regions.

### Insights
- North America shows the highest sales concentration  
- Europe and Pacific regions contribute moderate sales  
- Geographic visualization highlights regional performance differences  

### Visualization
![Map](map.png)

---

## 3. Product Details Report

### Objective
Analyze product performance and target comparison.

### Insights
- Water Bottle (30 oz) recorded 404 orders  
- Revenue vs Target: $4,067 achieved against $4,292 target  
- Profit vs Target: $2,546 against $2,687 target  
- Adjusted profit increased by over 230% during the selected period :contentReference[oaicite:2]{index=2}  

### Visualization
![Product Details](product_details.png)

---

## 4. Customer Details Report

### Objective
Analyze customer behavior and identify high-value customers.

### Insights
- Total Unique Customers: 17.4K  
- Revenue per Customer: $1,431  
- Top Customer: Mr. Maurice Shan ($12.4K revenue)  
- Weekly customer trend shows steady growth over time :contentReference[oaicite:3]{index=3}  

### Visualization
![Customer Details](customer_details.png)

---

## 5. Q&A Report

### Objective
Enable natural language queries to explore data insights.

### Insights
- Users can ask questions directly (e.g., "Top products by revenue")  
- Provides quick and interactive data exploration  

### Visualization
![Q&A](qna.png)

---

## 6. Decomposition Tree Analysis

### Objective
Break down total orders into categories and subcategories.

### Insights
- Total Orders: 25,164  
- Accessories contribute the highest share (16,983 orders)  
- Tires and Tubes is the top-performing subcategory  
- Detailed drill-down reveals product-level performance :contentReference[oaicite:4]{index=4}  

### Visualization
![Decomposition Tree](decomposition_tree.png)

---

## Analysis Performed
- Built a relational data model across multiple datasets  
- Created DAX measures for KPIs and comparisons  
- Designed interactive dashboards with slicers and filters  
- Analyzed trends across time, products, regions, and customers  

---

## Key Insights
- Revenue and profit show consistent growth over time  
- Accessories and Bikes are the top-performing categories  
- Regional performance varies significantly  
- High-value customers contribute a major portion of revenue  

---

## How to Use
1. Download the `.pbix` file  
2. Open in Power BI Desktop  
3. Interact with filters and visuals  

---

## Project Files
- AdventureWorks_Dashboard.pbix  
- exec_dashboard.png  
- map.png  
- product_details.png  
- customer_details.png  
- qna.png  
- decomposition_tree.png  

---

## What I Learned
- End-to-end BI dashboard development  
- Data modeling and relationship building  
- Writing DAX measures  
- Designing professional dashboards  

---

## About
Power BI project focused on transforming raw sales data into actionable business insights using data modeling and visualization techniques.

---
