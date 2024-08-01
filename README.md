# DataSpark: EDA and Visualization Project

This project aims to analyze and visualize customer, sales, product, and store data using Power BI. We integrate multiple datasets, clean and prepare the data, execute SQL queries to extract insights, and develop interactive visualizations in Power BI.

## Project Overview

The main objectives of this project are:
1. **Customer Analysis**: Understand customer demographics and purchasing patterns.
2. **Sales Analysis**: Analyze overall sales performance and trends.
3. **Product Analysis**: Evaluate product popularity and profitability.
4. **Store Analysis**: Assess store performance based on sales data.
   
## Getting Started

1. Clone this repository.
2. Set up the PostgreSQL database and import the datasets.
3. Connect the database to Power BI.
4. Load the data and create visualizations using the provided SQL queries and DAX formulas.

## Prerequisites

- PostgreSQL
- Power BI
- Python (for data cleaning and preparation)

## Datasets

We used two primary datasets:
1. `global` table: Contains customer, sales, product, and store data.
2. `global1` table: Contains exchange rate data.

## Data Preparation

1. **Check for Missing Values**: Handle missing data appropriately.
2. **Convert Data Types**: Ensure correct data types for dates and numerical values.
3. **Merge Datasets**: Combine sales data with product and customer data where necessary.

## SQL Queries

We formulated and executed 15 SQL queries to extract key insights from the data. The queries addressed important business questions and supported the analysis steps mentioned above.

## Key SQL Queries

1. **Customer Analysis**
   - Customer count by city
   - Gender distribution of customers
   - Age distribution of customers
   - Average order value per customer
   - Most frequently purchased products

2. **Product Analysis**
   - Profit margin for each product
   - Most popular products by quantity sold
   - Total sales for each subcategory

3. **Sales Analysis**
   - Products generating the highest revenue
   - Stores generating the highest sales
   - Sales variation by currency
   - Top-performing product categories by sales

4. **Store Analysis**
   - Regions generating the highest sales
   - Relationship between store size (square meters) and sales

## Power BI Visualization

We connected the SQL database to Power BI and imported the data to create interactive dashboards. These dashboards provide insights into customer demographics, sales trends, product performance, and store analysis.

## Key Visualizations

1. **Customer Analysis Dashboards**
   - Gender and age distribution
   - Customer count by city
   - Purchase patterns and segmentation

2. **Sales Analysis Dashboards**
   - Overall sales performance
   - Sales by product, store, and currency
   - Seasonal trends

3. **Product Analysis Dashboards**
   - Product popularity
   - Profitability analysis
   - Category and subcategory performance

4. **Store Analysis Dashboards**
   - Store performance by sales and size
   - Geographical analysis of store sales

## Conclusion

Through this project, we gained valuable insights into customer behavior, sales trends, product performance, and store operations. The visualizations created in Power BI enabled us to identify key trends and make data-driven decisions, demonstrating the importance of integrating and analyzing data from multiple sources for comprehensive business intelligence.



