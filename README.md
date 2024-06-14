# Afame-Technologies

Sales Data Analysis Project

Overview

This project aims to analyze sales data to find patterns, best-selling items, and revenue indicators to assist in business decision-making. The analysis includes computing total sales, examining sales trends over time, identifying best-selling products, and creating visualizations to present the insights.

Goals

Total Sales Calculation: Determine the overall revenue.
Sales Trends Analysis: Observe sales trends over different time periods (daily, weekly, monthly, quarterly, yearly).
Best-Selling Products Identification: Identify products that generate the most revenue and those sold in the highest quantities.
Additional Insights: Provide insights into sales by region and category.

Dataset
The dataset used for this project is stored in an Excel file named ECOMM_DATA.xlsx. It contains the following columns:

Order Date
Ship Date
Sales
Quantity
Region
Category
Sub-Category
Product Name
Postal Code (with missing values)

Prerequisites
To run the analysis and visualizations, you need the following Python libraries:

pandas
matplotlib
seaborn


Analysis Steps

1. Data Loading and Cleaning
Load the dataset from the Excel file.
Convert Order Date and Ship Date columns to datetime format.
Handle missing values in the Postal Code column.
2. Calculations and Grouping
Calculate total sales and total quantity sold.
Group sales data by different time periods (daily, weekly, monthly, quarterly, yearly).
3. Visualizations
Total Sales Over Time
Create a line chart to show total sales over time.

Sales Trends by Month and Year
Create line charts to display sales trends by month and year.

Best-Selling Products by Revenue and Quantity
Create bar charts to highlight the top products by revenue and quantity.

Sales by Region
Create a pie chart to show sales distribution by region with an explode effect for better visualization.

Sales by Category and Sub-Category
Create a stacked bar chart to show sales contributions of each sub-category within the main categories.
