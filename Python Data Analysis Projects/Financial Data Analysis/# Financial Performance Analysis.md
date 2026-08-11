# Financial Performance Analysis

## Business Question

How is the business performing financially over time, and what patterns can be identified in revenue, expenses, profit, and profit margins?

The analysis examines monthly and quarterly financial performance to identify revenue trends, changes in profitability, and periods of higher expenses.

## 1. Dataset

The project uses financial data stored in:

`financial_data.csv`

The dataset contains monthly financial information including:

- Date
- Revenue
- Expenses
- Profit

The analysis covers financial performance from 2022 through 2023.

## 2. Tools

- Python
- Pandas
- Matplotlib

## 3. Data Cleaning

The following data preparation steps were performed:

- Loaded the financial dataset using Pandas.
- Inspected the initial records to understand the structure of the dataset.
- Converted the `Date` column from a string to a datetime format using `pd.to_datetime()`.
- Extracted the month name from the `Date` column to support monthly analysis.
- Created a `Profit Margin` column using profit as a percentage of revenue.
- Converted the dates into quarterly periods to support quarter-level revenue analysis.

## 4. Analysis

The analysis focused on several areas of financial performance.

### Average Monthly Financial Performance

Calculated the average monthly:

- Revenue
- Expenses
- Profit

The results were:

- **Average monthly revenue:** $35,200
- **Average monthly expenses:** $15,425
- **Average monthly profit:** $19,775

### Profit Margin Analysis

Profit margin was calculated using:

`Profit Margin = (Profit / Revenue) × 100`

The profit margin was then analyzed over time to identify changes in profitability.

### Revenue Performance

The difference between the highest and lowest monthly revenue was calculated.

- **Highest-revenue month:** August
- **Lowest-revenue month:** March
- **Difference:** $48,000

### Expense Analysis

The analysis identified the months in which expenses exceeded **$10,000**.

### Quarterly Revenue Analysis

Revenue was aggregated by quarter to examine changes in financial performance over time.

Quarterly revenue was:

- **2022 Q1:** $45,000
- **2022 Q2:** $65,000
- **2022 Q3:** $97,000
- **2022 Q4:** $112,000
- **2023 Q1:** $126,000
- **2023 Q2:** $150,000
- **2023 Q3:** $109,000

Revenue in the final quarter of 2022 was:

**$112,000**

### Quarter-to-Quarter Revenue Change

The percentage change in quarterly revenue was calculated using Pandas `pct_change()`.

The analysis showed that revenue increased from 2022 Q1 through 2023 Q2 before declining in 2023 Q3.

## 5. Visualizations

### Profit Margin Over Time

A Matplotlib line plot was created to visualize changes in profit margin over time.

The visualization helps identify periods of improving or declining profitability.

## 6. Key Findings

- Average monthly revenue was **$35,200**, while average monthly expenses were **$15,425**, resulting in an average monthly profit of **$19,775**.
- **August** recorded the highest monthly revenue, while **March** recorded the lowest.
- The difference between the highest and lowest monthly revenue was **$48,000**.
- Revenue increased consistently from **$45,000 in 2022 Q1** to **$150,000 in 2023 Q2**.
- Revenue in **2022 Q4 was $112,000**.
- Quarterly revenue growth was strongest between **2022 Q2 and 2022 Q3**, increasing by approximately **49.2%**.
- Revenue declined by approximately **27.3%** from **2023 Q2 to 2023 Q3**.
- The profit-margin trend provides an additional measure of financial performance beyond revenue alone.