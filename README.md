# Financial_Analysis_BI
Financial Analysis ETL & Power BI Dashboard
Project Overview
This project focuses on financial analysis and profit insights using Power BI. The dataset is processed through an ETL (Extract, Transform, Load) pipeline, and an interactive dashboard is created. The dashboard includes:

 Map Chart – Displays profit distribution across different regions.
 Bar Chart – Shows profit trends across product categories.
 Date Slicer – Enables users to filter data between January 2013 and December 2014.

Objective
To provide actionable insights into business profitability by analyzing revenue, cost, and profit across different regions and product categories.

Dataset details
Date – Transaction date
Region – Location of the sales (Country/State/City)
Revenue – Total earnings from sales
Cost – Total business expenses
Profit – Calculated as (Revenue - Cost)
Product Category – Business segment
Customer Data – Buyer details
Timeframe: Data is filtered to include transactions from January 2013 to December 2014 as per client requirements.

ETL Process in Power BI
1. Extract (Data Sources)
The data is sourced from:

Excel file

2. Transform (Data Cleaning & Processing)

Handling Missing Values – Removed and imputed missing revenue/profit data.
Data Type Conversion – Ensured numeric fields (Revenue, Profit) and datetime formats.
Data Aggregation – Grouped data by region, date, and category.
Currency Conversion – Applied exchange rates for multi-currency transactions.
Date Filtering – Only included data between January 2013 and December 2014.

4. Load (Into Power BI)
The cleaned data is loaded into Power BI for visualization and analysis.
Power BI Dashboard & Visualizations

1. Map Chart (Geographical Profit Analysis)
Location: Country/State/City

2. Bar Chart (Category-wise Profit Comparison)

Transaction Date
Configuration:
Filters data between January 1, 2013, and December 31, 2014.
Purpose: Allows users to analyze profit trends over time dynamically.
Additional Features & Enhancements

This Power BI dashboard enables financial teams to:
1) Identify high-revenue regions and underperforming areas.
2) Analyze product-wise profit trends to optimize business strategies.
3) Filter data dynamically to assess time-based financial performance.

Outcome: Data-driven decision-making for improved financial performance.

Project Files
 Power BI File (.pbix) – Contains the complete dashboard.
 Dataset (Excel/CSV) – Raw financial data for analysis.

Future Enhancements
1) Integration with Live Data Sources (SQL, APIs) for real-time insights.
2) Advanced Predictive Analysis using machine learning models.
3) Additional Visualizations (Heatmaps, Line Charts for trend analysis).

Technologies Used
Power BI – Data visualization & dashboard creation
SQL – Data extraction & processing
Excel – Initial data cleaning
DAX (Data Analysis Expressions) – Advanced calculations in Power BI
