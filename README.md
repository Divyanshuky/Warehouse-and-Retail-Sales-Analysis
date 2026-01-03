# Warehouse-and-Retail-Sales-Analysis
This project analyzes warehouse and retail sales data from Montgomery County’s open data portal. The goal was to practice data cleaning, filtering, aggregation, and visualization using Pandas and Matplotlib.
Dataset

Source: Montgomery County Open Data
Monthly sales data including:
Retail sales
Warehouse sales
Item types (Wine, Beer, Liquor)
Suppliers
Time (Year, Month)

Key Steps
Cleaned missing and duplicate records
Converted columns to appropriate numeric types
Filtered inactive (zero-sales) records
Created a TOTAL_SALES metric

Aggregated sales by:
Month
Year
Item type
Supplier

Visualized trends using bar and line charts

Key Insights
Total sales vary significantly across years and months
Wine contributes the highest total sales among item types
A small number of suppliers account for a large share of total sales
Warehouse and retail sales show different distribution patterns

Limitations
Zero-sales records were removed, which may bias totals upward
No price or profit data available
Analysis focused on aggregation, not statistical inference

Tools Used
Python
Pandas
Matplotlib
Google Colab
