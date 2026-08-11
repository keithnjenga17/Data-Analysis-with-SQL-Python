# Sales Performance & Budget Analysis Dashboard

## Business Question

How is sales performance tracking against budget, and which salespeople, managers, supervisors, and sales channels are contributing most to revenue and sales volume?

The Power BI dashboard provides an interactive view of sales performance, allowing users to compare actual revenue with budget, analyze sales activity, and evaluate individual salesperson performance.

## 1. Dataset

The Power BI report is built around a sales data model containing multiple related tables:

- **Fact_Table** — contains the core sales transactions and sales-related information.
- **FactTableBudget** — contains budget information used to compare planned and actual performance.
- **Dim_Salesperson** — contains salesperson, manager, and supervisor information.
- **Dim_Product** — provides product-related dimensions.
- **Calendar** — supports time-based analysis using year, quarter, and month.
- **Measure Table** — contains the main DAX measures used throughout the dashboard.

Key fields and measures include:

- Revenue
- Budget
- Quantity Sold
- Transactions
- Salesperson
- Manager
- Supervisor
- Sales Channel
- Year
- Quarter
- Month
- % of Revenue
- % of Quarter

## 2. Tools

- Power BI
- DAX
- Power Query
- Data Modeling
- Power BI Interactive Visualizations

## 3. Data Cleaning & Preparation

The report uses a structured Power BI data model to prepare the sales data for analysis.

Key preparation activities include:

- Organizing sales information into fact and dimension tables.
- Separating budget data from transactional sales data.
- Creating a dedicated Calendar table for time-based analysis.
- Establishing dimensions for salespeople, managers, supervisors, and products.
- Creating DAX measures for revenue, quantity sold, transactions, budget, rankings, and percentage-based performance metrics.
- Creating interactive parameter tables that allow users to change ranking and analysis selections.

## 4. Analysis

### Revenue Performance

Total revenue is used as a primary measure of sales performance.

The dashboard enables revenue to be analyzed by:

- Salesperson
- Manager
- Sales channel
- Time period

### Revenue vs Budget

Actual revenue is compared with total budget across:

- Year
- Quarter
- Month

This allows users to monitor whether sales performance is tracking against planned targets.

### Salesperson Performance

Salespeople are ranked according to their performance.

The dashboard includes an interactive ranking component that allows users to evaluate salesperson performance based on the selected ranking criteria.

### Sales Channel Performance

Revenue is analyzed across different sales channels to identify the channels contributing most to overall sales.

### Sales Volume

The dashboard tracks total quantity sold and number of transactions, providing additional measures of sales activity beyond revenue.

### Sales Contribution

Percentage measures are used to evaluate:

- Individual contribution to total revenue
- Contribution to quarterly performance

This provides a more detailed view of salesperson and organizational performance.

## 5. Visualizations

The dashboard contains several interactive Power BI visuals.

### KPI Cards

Key performance indicators include:

- Total Revenue
- Total Quantity Sold
- Total Transactions

### Revenue by Manager

A donut chart displays revenue distribution across managers.

### Revenue by Channel

A donut chart compares revenue across sales channels.

### Revenue vs Total Budget

A combined line and column chart compares:

- Total Revenue
- Total Budget

across the calendar hierarchy of:

- Year
- Quarter
- Month

This provides a direct view of actual performance against planned performance over time.

### Salesperson Ranking

A ranked bar chart compares salesperson performance and allows the ranking view to be dynamically adjusted.

### Sales Performance Table

A detailed matrix provides performance information across:

- Supervisor
- Salesperson
- Total Revenue
- % of Revenue
- Total Quantity Sold
- % of Quarter

### Interactive Controls

The dashboard includes slicers/parameters that allow users to dynamically select:

- Ranking options
- Ranking type
- Salesperson ranking criteria

## 6. Key Findings

The dashboard is designed to identify the following business insights:

- **Revenue performance can be evaluated against budget** across different periods, making it possible to identify periods of stronger or weaker performance.
- **Salespeople can be ranked and compared** to identify high- and low-performing contributors.
- **Manager and supervisor performance can be evaluated** through revenue contribution.
- **Sales channels can be compared** based on their contribution to total revenue.
- **Quantity sold and transaction volume** provide additional context for understanding revenue performance.
- **Percentage-of-revenue metrics** help identify how individual salespeople contribute to overall business revenue.
- **Quarterly contribution metrics** provide insight into salesperson performance within specific reporting periods.

## Business Value

The dashboard provides management with an interactive tool for monitoring sales performance, comparing actual revenue against budget, evaluating salesperson performance, and identifying areas requiring further investigation.

The combination of KPI tracking, budget variance analysis, salesperson ranking, channel analysis, and time-based reporting supports data-driven sales performance management.