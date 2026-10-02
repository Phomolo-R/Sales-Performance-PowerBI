
Sales Performance Analytics Dashboard | Power BI
Project Overview

This project presents an interactive Sales Performance Analytics Dashboard developed using Microsoft Power BI. The dashboard transforms raw sales data into meaningful business insights by analysing revenue, profitability, customer segments, regional performance, and product trends.

The objective of this project is to demonstrate how business intelligence tools can be used to clean data, build data models, create DAX measures, and design interactive dashboards that support data-driven decision-making.

Business Problem

Businesses generate thousands of sales transactions, making it difficult to manually identify trends and make informed decisions.

This dashboard helps answer key business questions such as:

How much revenue has the business generated?
Which products generate the highest sales?
Which regions perform the best?
Which customer segments contribute the most revenue?
How profitable is the business?
Dataset

Dataset: Sample Superstore Sales Dataset

The dataset contains transactional sales information, including:

Order Date
Ship Date
Customer Information
Product Information
Sales
Quantity
Discount
Profit
Region
Category
Sub-Category
Tools & Technologies
Microsoft Power BI
Power Query
DAX (Data Analysis Expressions)
CSV Dataset
Data Preparation

The dataset was cleaned using Power Query.

The following transformations were performed:

Converted Order Date into a valid date format.
Converted Ship Date into a valid date format.
Corrected numerical data types.
Changed Postal Code to Text.
Created a Profit Status column to classify records as Profit or Loss.
Prepared the dataset for dashboard reporting.
DAX Measures

The following measures were created:

Total Sales
Total Sales =
SUM(Sales_Data[Sales])
Total Profit
Total Profit =
SUM(Sales_Data[Profit])
Total Orders
Total Orders =
DISTINCTCOUNT(Sales_Data[Order ID])
Total Quantity
Total Quantity =
SUM(Sales_Data[Quantity])
Profit Margin
Profit Margin =
DIVIDE([Total Profit],[Total Sales],0)
Dashboard Features
Executive Dashboard

The dashboard contains the following interactive visuals:

KPI Cards
Total Sales
Total Profit
Total Orders
Total Quantity
Profit Margin
Monthly Sales Trend
Sales by Category
Sales by Region
Sales by Customer Segment
Top 10 Products by Sales
Interactive Slicers
Year
Region
Category
Segment
Dashboard Results
KPI	Value
Total Sales	2.30M
Total Profit	286.40K
Total Orders	5K
Total Quantity	38K
Profit Margin	12.47%
Key Insights
The dashboard provides a clear overview of business performance through executive KPIs.
Sales performance can be analysed across multiple years using the monthly trend analysis.
Product categories contribute differently to overall revenue.
Regional analysis highlights geographical differences in sales performance.
Customer segment analysis identifies which customer groups generate the most revenue.
Product-level analysis highlights the highest-performing products based on total sales.
Skills Demonstrated

This project demonstrates the following skills:

Data Cleaning
Data Transformation
Power Query
Data Modelling
DAX Calculations
Business Intelligence Reporting
Interactive Dashboard Design
Data Visualisation
Business Analysis
