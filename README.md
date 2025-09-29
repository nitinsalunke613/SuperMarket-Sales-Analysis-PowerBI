# 🛒 SuperMarket Sales Analysis (Power BI Project)
## 📌 Project Overview

This project focuses on analyzing supermarket sales performance, customer behavior, and profitability trends using Power BI. The goal was to build a complete end-to-end Business Intelligence (BI) solution – from connecting and shaping raw data to creating a robust data model, designing DAX measures, and developing interactive dashboards that provide actionable insights.

## 🔑 Key Steps
1. Data Preparation & Transformation

Connected multiple CSV files: Customers, Products, Stores, Regions, Calendar, Returns, and Transactions (1997 & 1998).

Cleaned and transformed data using Power Query:

Created calculated columns such as full_name, birth_year, has_children, discount_price, full_address, and area_code.

Handled null values and ensured correct data types.

Enhanced Calendar table with derived fields like Start of Week, Month, Quarter, and Year.

2. Data Modeling

Built a star schema data model:

Transaction_Data linked to Customers, Products, Stores, and Calendar.

Return_Data linked to Products, Stores, and Calendar.

Stores connected to Regions (snowflake schema).

Ensured one-to-many relationships with proper filter direction for optimized performance.

3. DAX Calculations

Created calculated columns: Customer Age, Priority, Price Tier, Years Since Remodel, etc.

Built measures for business insights:

Sales Metrics: Quantity Sold, Total Revenue, Total Profit, Profit Margin, Return Rate.

Time Intelligence: YTD Revenue, 60-Day Revenue, Last Month Transactions, Revenue Target.

Comparative Metrics: % Weekend Transactions, Unique Products, etc.

4. Interactive Reporting

Developed a Power BI dashboard named Topline Performance featuring:

📊 Matrix Visual – Transactions, Profit, Margin, and Returns by Product Brand with conditional formatting.

📌 KPI Cards – Current Month Transactions, Profit, and Returns vs. last month.

🗺️ Map & Treemap Visuals – Geographical insights on transactions by Country, State, and City.

📈 Revenue Trend Analysis – Weekly revenue chart filtered for 1998.

🎯 Gauge Chart – Revenue vs. Target tracking.

Drill-down and filter functionality for deeper exploration.

## 🎯 Business Insights

Identified top-performing product brands and their profitability.

Measured return rates to evaluate product quality and customer satisfaction.

Analyzed geographic sales performance across countries and regions.

Tracked monthly revenue growth vs. targets and previous month benchmarks.

Highlighted impact of weekend transactions on overall sales.

## 🛠️ Tools & Technologies

Power BI Desktop

Power Query (M language) for ETL

DAX (Data Analysis Expressions) for measures and calculated columns

Data Visualization – Maps, KPIs, Matrix, Treemap, Gauge, and Column Charts

## 📊 Dashboard Image
![SuperMarket_Report](https://github.com/user-attachments/assets/4403ab85-1b33-4e27-b9ce-55b3a14c1193)
