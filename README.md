# Power-BI : Global Superstore Analysis
📌 Project Overview
This project focuses on analyzing sales and profitability trends of a global retail dataset using Power BI. The dataset, sourced from Kaggle, contains order details from multiple regions worldwide.

The primary goal was to clean the data, build meaningful KPIs, and develop an interactive dashboard to uncover insights on regional sales, top-performing salespersons, and product profitability.

📊 Dataset Details
The project is based on three datasets:

Order Table (Fact Table)

51,290 rows, 24 columns
Contains detailed order transactions across different markets.
Returns Table (Fact Table)

1,174 rows, 3 columns
Lists orders that were returned by customers.
People Table (Dimension Table)

14 rows, 2 columns
Maps salespersons to their respective regions.
🔍 Project Objectives & Responsibilities
✅ Data Cleaning & Preprocessing:

Removed inconsistencies, handled missing values, and formatted data for analysis.
✅ Data Modeling & Relationships:

Established correct relationships between Orders, Returns, and People tables.
Ensured proper filter flow for accurate insights.
✅ KPI Development & Analysis:

Calculated key metrics such as total sales, profit, profit margin, YoY and MoM growth rates, and running totals using DAX functions.
Created interactive drill-through analysis for product performance at category and sub-category levels.
✅ Trend Analysis & Insights Extraction:

Researched sales and profit trends across different markets.
Analyzed salesperson performance over time (Month-over-Month & Year-over-Year).
📈 Key Insights & Findings
📍 Highest Sales Market:

APAC had the highest total sales ($3.59M), 22.1% more than the EU market ($2.94M).
📍 Most Profitable Market:
APAC led with $436K in profit, 16.2% more than EU ($375K profit).
📍 Top Salesperson Performance:
Anna Andreadi was the top-performing salesperson with $2.8M in sales and $650K in profit.
📍 Year-End Sales & Profit Growth (December 2013):
Sales increased by +37.52% YoY but dropped -4.39% MoM.
Profit grew +110.47% YoY and +7.44% MoM.
📍 Top Customer Segment & Product Category:
Consumers contributed the most revenue.
Technology products were the highest revenue-generating category.
🛠 Tools & Technologies Used
Power BI – Data visualization & dashboard development
Excel – Data cleaning & preprocessing
DAX (Data Analysis Expressions) – For calculated measures and time intelligence
📊 Dashboard Features
Filter & Slicers: Users can filter data by region, year, and product category.
Drill-Through Analysis: Navigate from category-level data to detailed subcategory and product-level insights.
Interactive KPI Cards: Show YoY and MoM comparisons.
Profitability Analysis: Identify high-margin products and regions.
