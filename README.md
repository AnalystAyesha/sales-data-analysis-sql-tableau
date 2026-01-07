# Sales Data Analysis using SQL and Tableau

## Table of Contents
- Project Overview
- Data Source
- Tools Used
- Data Cleaning & Preparation
- Exploratory Data Analysis (EDA)
- Data Analysis
- Results & Findings
- Recommendations
- References

## Project Overview
This project focuses on analyzing sales data to understand overall revenue performance, sales quantity trends, market-wise distribution, and top-performing customers and products.  
SQL was used for data extraction and initial analysis, and Tableau Desktop was used to build an interactive dashboard for visualizing insights.

## Data Source
- Sales data stored in an SQL database
- Multiple related tables containing sales, customer, product, and market information
- Data was extracted using SQL queries and joins before loading into Tableau

## Tools Used
- SQL – Data extraction, joins, and initial analysis  
- Tableau Desktop – Data visualization and dashboard creation  

## Data Cleaning & Preparation
Before visualizing the data in Tableau, the following steps were performed:
- Verified table structure and column consistency in SQL
- Used joins to combine relevant tables
- Checked for missing and inconsistent values
- Ensured correct data types for dates, revenue, and quantity fields
- Prepared the final dataset for smooth loading into Tableau Desktop

## Exploratory Data Analysis (EDA)
Initial exploration was done to understand:
- Overall revenue and sales quantity
- Revenue distribution across different markets
- Monthly and yearly sales trends
- Top customers and products contributing to revenue

This helped in deciding the most suitable visualizations for the dashboard.

## Data Analysis
The Tableau dashboard consists of individual sheets, each representing one visual:
- Total Revenue KPI
- Sales Quantity KPI
- Revenue by Markets
- Sales Quantity by Markets
- Top 5 Customers by Revenue
- Top 5 Products by Revenue
- Revenue Trend by Year (Line Chart)
- Year-wise and Month-wise filters for interactive analysis

All visuals are connected to allow dynamic filtering and better insights.

## Results & Findings
- Certain markets contribute significantly higher revenue compared to others
- A small group of customers and products generate a major share of total revenue
- Revenue shows noticeable variation across months and years
- Sales quantity and revenue do not always increase proportionally across markets

## Recommendations
- Focus marketing and sales efforts on high-revenue markets
- Strengthen relationships with top customers
- Optimize inventory planning based on top-selling products
- Analyze low-performing markets for potential improvement opportunities

## References
- Tableau Desktop Documentation
- SQL Documentation
- Project dataset provided for analysis
