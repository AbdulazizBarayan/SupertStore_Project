# SupertStore_Project


Project Overview
This project analyzes sales performance for a fictional retail Superstore using Power BI. The goal is to explore metrics like sales, profit, and quantity across different customer segments, product categories, regions, and shipping methods. The interactive dashboard helps identify business trends, customer behavior, and areas for improvement.

🧹 Data Cleaning & Quality Checks
Before building the dashboard, the dataset was cleaned and validated using SQL to ensure data accuracy and consistency.

Data Quality Checks Performed:
Checked for duplicate rows using the Row_ID field to confirm data uniqueness.

Verified that Order Date is always before or equal to Ship Date.

Identified and removed leading/trailing white spaces in text fields such as customer names.

Reviewed distinct values in fields like Ship Mode, Segment, Category, and Region to confirm valid entries.

Data Cleaning Steps:
Removed or confirmed duplicate entries.

Trimmed unnecessary spaces from text fields.

Standardized and converted date formats.

Ensured all column data types were correct and renamed fields where needed for clarity.

📐 Dashboard Layout & Visuals
The Power BI dashboard includes a balanced combination of summary metrics and detailed breakdowns, designed for both high-level and exploratory analysis.

KPI Cards:
Total Sales – displays overall revenue.

Total Profit – shows total earnings after discounts.

Total Quantity – represents the total number of items sold.

Visual Charts:
Line Chart – tracks monthly sales trends over time.

Bar Chart – shows sales distribution across product categories.

Pie Chart – visualizes sales by customer segments.

Slicers for Interactivity:
Region – allows filtering data by geographic areas.

Ship Mode – lets users view data based on different shipping methods.

🧠 Key Insights Enabled
Understand how sales and quantity change over time.

Compare performance between customer segments and product categories.

Identify which regions and shipping methods are most effective.

Use filters to focus analysis on specific business areas.

📂 Data Source
Sample Superstore dataset (CSV format)

⚙️ Tools Used
SQL Server for data validation and transformation

Power BI for data modeling, analysis, and dashboard creation
