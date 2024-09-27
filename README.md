# Superstore Sales Analysis with MySQL and Power BI
## Overview
This project involves the analysis of Superstore sales data (2015-2018) using MySQL for querying and analysis, followed by visualization in Power BI. The analysis focuses on key business metrics such as delivery times, sales trends, customer behavior, and product performance. The final insights are visualized using a multi-page dashboard in Power BI, allowing for interactive filtering and detailed insights into sales performance across different regions, products, and customer segments.

## Key Features:
## SQL Queries:

Used MySQL to perform data exploration and analysis. Key queries included calculating:
Percentage of orders shipped on the same day.
Top 3 customers by total order value.
Top 5 products with the highest average sales per day.
Customer ranking by average order value.
City-wise highest and lowest order customers.
Most demanded sub-category in the West region.
Orders with the highest number of items and total sales.
Segment more likely to ship via First Class.
City with the least contribution to total revenue.
Average delivery time.
Segments placing the most and largest individual orders by state.
Customers ordering on 3 consecutive days with a minimum order value.
Longest streak of increasing daily sales.
Power BI Dashboard:
Connected MySQL to Power BI to create a three-page dashboard for deeper insights:

## Page 1: Sales by Region:
Visualized total sales on a map with a city breakdown.
Displayed top 5 and bottom 5 states by sales.
Count of same-day deliveries and monthly sales trends using line charts.
Summary cards showing total sales, total orders, number of products, customer count, average delivery time, and same-day orders.
Applied filters by state, region, and category for in-depth analysis.
## Page 2: Sales by Product:
Created DAX measures to display the most sold products and their sales amount.
Showed top 5 and bottom 5 categories and products.
Product-wise and category-wise sales breakdown for better decision-making.
## Page 3: Sales by Customers:
Displayed top 5 and bottom 5 customers, region-wise customer counts, and top cities with the highest customer counts.
A map showing the customer count distribution.
Created a measure to identify the top customer name and count of customers, displayed on line charts.

## Tools & Technologies Used:
MySQL: For data querying and analysis.
Power BI: For visualization and creating interactive dashboards.
DAX (Data Analysis Expressions): For creating custom measures and calculated columns.

## Project Insights:
The analysis provided several actionable insights, such as identifying cities and states with low sales, top-performing products, and customer behavior patterns. The Power BI dashboard allowed users to interact with filters and explore the data from various angles, improving business decision-making in terms of sales strategy, product focus, and delivery efficiency.
