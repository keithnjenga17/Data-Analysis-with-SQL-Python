# Financial Performance Dashboard

## Business Question

How is the business performing across sales, profitability, transactions, units sold, and discounts, and what patterns can be identified across time, customer segments, and discount levels?

The Power BI dashboard provides an interactive view of financial performance, allowing users to evaluate key performance indicators and compare profitability across different business dimensions.

## 1. Dataset

The dashboard is built using a financial dataset represented by the `financials` table.

Key fields used in the analysis include:

- Country
- Segment
- Units Sold
- Discount Band
- Sales and financial measures
- Calendar-related fields such as Month, Weekday, and Year

The report also uses a dedicated `Calendar` table for time-based analysis and an `All Measures` table containing the report's calculated measures.

The dashboard excludes Canada, France, Germany, and Mexico from the displayed analysis through report-level visual filtering.

## 2. Tools

- Power BI
- Power Query
- DAX
- Data Modeling
- Interactive Power BI Visualizations

## 3. Data Cleaning

The Power BI report uses a structured data model containing:

- A financial data table
- A dedicated Calendar table for time analysis
- An All Measures table for centralized calculations

The report uses the Calendar table to support analysis by:

- Month
- Weekday
- Year

Financial measures are also organized separately in the `All Measures` table, supporting consistent calculations across the dashboard.

## 4. Analysis

The dashboard analyzes financial performance using several key measures.

### Sales and Financial Performance

The report tracks:

- Gross Sales
- Net Sales
- COGS
- Total Profit
- Total Discount

These measures provide a view of revenue generation, costs, discounts, and profitability.

### Operational Performance

The dashboard also measures:

- Total Transactions
- Units Sold

These metrics provide insight into sales activity and product volume.

### Profitability Over Time

Profit is analyzed across different time dimensions, including:

- Month
- Weekday
- Year

The dashboard separates positive and negative profit values to make changes in profitability easier to identify.

### Segment Analysis

Total profit is compared across customer/business segments to identify which segments contribute most to overall profitability.

### Discount Analysis

Profit is also analyzed across different discount bands to evaluate how discount levels relate to profitability.

### Country Filtering

A country slicer is included in the dashboard, allowing users to interactively filter the analysis by country.

## 5. Visualizations

The dashboard includes several interactive Power BI visualizations.

### KPI Cards

Key performance indicators are displayed using cards for metrics including:

- Transactions
- COGS
- Gross Sales
- Net Sales
- Units Sold
- Total Discount
- Total Profit

### Profit Trend

An area chart is used to analyze positive and negative profit across months.

### Profit by Weekday

A column chart compares total profit across weekdays.

### Profit by Year

A donut chart compares total profit across years.

### Profit by Segment

A bar chart ranks business/customer segments according to total profit.

### Profit by Discount Band

A column chart compares total profit across different discount bands.

### Country Filter

An interactive country slicer allows users to filter the dashboard and investigate financial performance for individual countries.

## 6. Key Findings

The dashboard provides several dimensions through which financial performance can be evaluated:

- **Net Sales, Gross Sales, COGS, and Total Profit** provide a comprehensive view of financial performance.
- **Transactions and Units Sold** provide measures of sales activity and volume.
- Profitability can be compared across **months, weekdays, and years** to identify temporal patterns.
- **Customer/business segments** can be ranked according to their contribution to total profit.
- Profit can be evaluated across different **discount bands**, providing insight into the relationship between discounting and profitability.
- The interactive **country slicer** allows users to investigate how financial performance changes when different countries are selected.
- Separating positive and negative profit values makes it easier to identify periods of stronger and weaker financial performance.