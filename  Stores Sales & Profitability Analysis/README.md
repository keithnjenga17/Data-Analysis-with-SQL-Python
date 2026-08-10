##Project Overview
This project analyzes superstore sales data using SQL, SQLite, and Python to uncover insights related to product performance, customer profitability, sales growth, discount impact, and regional sales trends.

The analysis focuses on:
customer profitability,
sales growth trends,
product performance,
discount impact on revenue,
and operational data quality.

##Business Problem
Retail businesses need to understand:
which products and customers drive profitability,
how discounts affect revenue,
which regions underperform,
and how sales trends evolve over time.

This project uses transactional retail data to support data-driven decision-making in sales, marketing, and inventory management.

##Technical Skills Demonstrated
Skill	-Application
Python	-Data analysis and visualization
SQLite	-Relational database querying
Pandas	-Data ingestion and preprocessing
Matplotlib	-Sales trend visualization
SQL Window Functions	-Customer and product ranking
Recursive SQL   -Cumulative sales tracking
Data Cleaning	-Date standardization and whitespace handling

##Analysis Performed
The project explored:
product distribution across categories,
sales growth in furniture products,
profitability of technology products,
top-performing customers by profit margin,
impact of discounts on revenue,
state-level sales growth trends,
and products with the highest cumulative sales.

##SQL Skills Demonstrated
DENSE_RANK()
Window functions
Recursive CTEs
Common Table Expressions (CTEs)
CASE WHEN
STRFTIME()
NULLIF()
Aggregate functions
Data cleaning with TRIM() and REPLACE()
Multi-table joins

##Analytical Thinking Demonstrated
Standardized inconsistent date formats to enable accurate time-series analysis.
Cleaned product naming inconsistencies to improve reporting reliability.
Applied ranking functions to identify high-value customers and underperforming regions.
Evaluated the financial impact of discounts using adjusted sales calculations.
Used cumulative sales analysis to track long-term product performance trends.

##Key Insights
Furniture sales showed measurable year-over-year growth between 2015 and 2016.
Certain technology products generated significantly lower profits despite strong sales activity.
A small group of customers contributed disproportionately high profit margins.
Discounts had a noticeable impact on overall revenue performance.
Some states experienced weak or negative year-over-year sales growth.
Product-level cumulative sales analysis identified key revenue-driving products.

##Data Cleaning & Engineering
The project included:
converting inconsistent date formats into SQLite-compatible dates,
removing leading and trailing whitespace in product names,
validating missing values,
and preparing relational datasets for advanced analysis.

These preprocessing steps improved analytical accuracy and database consistency.

##Data Visualization
A bar chart was created using Matplotlib to compare furniture sales performance between 2015 and 2016.
The visualization highlighted year-over-year sales growth trends.