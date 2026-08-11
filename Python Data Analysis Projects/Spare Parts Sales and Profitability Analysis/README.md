# Spare Parts Sales & Profitability Analysis

## Business Question

How can sales and profitability data be used to understand spare-parts performance and identify the most and least profitable products?

## 1. Dataset

The project uses a spare-parts sales dataset containing information on:

- Spare-part type
- Quantity sold
- Unit cost
- Sale price
- Date
- Total revenue

## 2. Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 3. Data Cleaning

- Checked data types.
- Checked for missing values.
- Checked for duplicate records.
- Cleaned the `total_revenue` column by removing currency symbols and commas.
- Converted `total_revenue` to a numerical data type.
- Converted the `date` column to datetime format.
- Created total cost and profit columns.

## 4. Analysis

- Analyzed the distribution of total sales.
- Compared revenue across spare-part categories.
- Calculated profitability by product.
- Identified the most and least profitable spare parts.
- Analyzed quantities sold by product.
- Examined revenue trends over time.
- Investigated the relationship between sale price and total revenue.

## 5. Visualizations

- Histogram
- Boxplot
- Scatter plot
- 3D scatter plot
- Pairplot
- Bar chart
- Line chart
- Regression plot

## 6. Key Findings

- Timing Belt was the most profitable spare part.
- Air Filter was the least profitable spare part.
- The difference in total profit between the two products was 1,556.
- Removing Air Filter would reduce total calculated profit by approximately 5.77%.