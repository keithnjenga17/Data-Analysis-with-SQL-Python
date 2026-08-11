# Sales & Profitability Analysis

## Business Question

What are the key drivers of sales revenue and profitability, and how do product mix, customer characteristics, sales representatives, locations, payment methods, pricing, and time influence business performance?

The analysis evaluates sales and profitability across multiple business dimensions to identify the strongest revenue and profit contributors and highlight areas that require further investigation.

## 1. Dataset

The dataset contains **12,000 sales transactions** covering the period from **January 1, 2024 to December 31, 2024**.

Each transaction contains information about:

- Transaction date
- Buyer
- Buyer location
- Buyer date of birth
- Payment method
- Quantity purchased
- Product
- Sales representative
- Gender
- Product cost
- Unit price
- Revenue
- COGS
- Profit
- Age group
- Price range
- Weekday
- Weekday/Weekend classification
- Quarter

### Dataset Coverage

The dataset contains:

- **12,000 transactions**
- **9,060 unique customers**
- **10 products**
- **10 buyer locations**
- **8 sales representatives**
- **4 payment methods**
- **5 age groups**
- **4 quarters**

### Overall Financial Performance

| KPI | Result |
|---|---:|
| Quantity Purchased | 3,050,309 |
| Revenue | 61,567,883 |
| COGS | 34,783,050 |
| Profit | 26,784,833 |
| Profit Margin | 43.50% |

## 2. Tools

- Microsoft Excel
- Excel Tables
- Pivot Tables
- Pivot Charts
- Excel formulas
- Data Cleaning
- Data Analysis
- Data Visualization
- Dashboard Development

## 3. Data Cleaning

The data preparation process included:

- Reviewing transaction records for completeness.
- Converting transaction dates and customer birth dates into usable date formats.
- Creating an age field from customer date of birth.
- Creating age groups for demographic analysis.
- Creating a combined customer name field.
- Creating revenue, COGS, and profit measures.
- Creating a price-range classification.
- Creating weekday and weekday/weekend classifications.
- Creating quarterly classifications.
- Connecting product codes with product names, costs, and unit prices.
- Preparing the dataset for Pivot Table and dashboard analysis.

## 4. Analysis

### Overall Profitability

The business generated:

- **61.57 million in revenue**
- **34.78 million in COGS**
- **26.78 million in profit**
- **43.50% profit margin**

This indicates that the analyzed sales portfolio generated a substantial gross profit relative to its cost base.

### Product Performance

Revenue was highly concentrated among several products.

| Product | Revenue | Profit |
|---|---:|---:|
| Shortbread | 13,973,760 | 10,868,480 |
| Vanilla Wafers | 11,579,220 | 5,789,610 |
| Ginger Snaps | 8,983,660 | 4,491,830 |
| Oatmeal Cookies | 6,606,313 | 1,148,924 |
| Caramel Biscuits | 6,562,820 | 1,193,240 |

**Shortbread was the strongest product**, generating approximately **13.97 million in revenue** and **10.87 million in profit**.

It contributed approximately **22.7% of total revenue** and was the largest contributor to overall profit.

### Sales Representative Performance

Sales performance varied considerably across representatives.

| Sales Representative | Revenue | Profit |
|---|---:|---:|
| Travis Doyle | 10,880,651 | 4,777,896 |
| Joseph Hill | 10,539,847 | 4,629,281 |
| April Watkins | 9,402,955 | 3,987,214 |
| Susan Dean | 8,667,028 | 3,812,100 |
| Sara Robertson | 7,697,702 | 3,368,343 |
| Katie Stanton | 6,935,990 | 3,053,760 |
| Tracy Lee | 5,889,857 | 2,455,523 |
| Elizabeth Guerrero | 1,553,853 | 700,716 |

**Travis Doyle generated the highest revenue and profit**, while Elizabeth Guerrero recorded the lowest sales contribution.

The large difference between representatives suggests that sales volume, territory allocation, customer portfolios, or sales effectiveness could be investigated further.

### Location Performance

Revenue varied across the ten buyer locations.

The strongest locations were:

1. **San Antonio — 7.34M**
2. **San Jose — 6.34M**
3. **Philadelphia — 6.32M**
4. **Houston — 6.18M**
5. **Dallas — 6.13M**

San Antonio was the strongest location, while Chicago generated the lowest revenue at approximately **5.67M**.

### Customer Age Analysis

The **60–74 age group** generated the highest revenue:

- Revenue: **14.84M**
- Profit: **6.66M**

This was closely followed by customers aged **30–44**, who generated approximately **14.80M** in revenue.

The **75–89 age group** generated the lowest revenue at approximately **5.57M**.

### Payment Method Analysis

Revenue was relatively evenly distributed across payment methods.

| Payment Method | Revenue |
|---|---:|
| Debit Card | 15.62M |
| Mobile Payment | 15.46M |
| Credit Card | 15.25M |
| Cash | 15.24M |

Debit Card generated the highest revenue, but the difference between payment methods was relatively small.

This suggests that revenue was not heavily dependent on one particular payment method.

### Pricing Analysis

The analysis classified products into two price ranges:

- Expensive
- Less Expensive

Approximately **89.46% of revenue came from products classified as Expensive**, while approximately **10.54% came from Less Expensive products**.

This indicates a strong concentration of revenue toward the higher-priced products in the dataset.

### Weekday vs Weekend Performance

Revenue was strongly concentrated on weekdays.

| Period | Revenue | Contribution |
|---|---:|---:|
| Weekday | 44.69M | 72.59% |
| Weekend | 16.88M | 27.41% |

Approximately **72.6% of revenue was generated on weekdays**.

This could have implications for sales staffing, inventory planning, and promotional scheduling.

### Quarterly Performance

Revenue was highest in Q1 and declined across the year.

| Quarter | Revenue | Contribution |
|---|---:|---:|
| Q1 | 22.09M | 35.88% |
| Q2 | 21.58M | 35.05% |
| Q3 | 11.58M | 18.81% |
| Q4 | 6.32M | 10.26% |

Q1 and Q2 together generated approximately **70.9% of total revenue**.

The substantial decline during Q3 and Q4 is an important pattern requiring further investigation.

### Monthly Sales Trend

The strongest months based on revenue were:

- January — **7.88M**
- July — **7.59M**
- March — **7.57M**
- May — **7.43M**
- June — **7.21M**

The weakest months were:

- September — **1.97M**
- December — **1.97M**
- November — **2.03M**
- August — **2.02M**

The analysis shows a substantial decline in monthly revenue beginning in August.

## 5. Visualizations

The Excel workbook supports analysis through:

### KPI Dashboard

Key performance indicators include:

- Quantity Purchased
- COGS
- Revenue
- Profit
- Profit Margin

### Product Profitability

Charts compare profit and revenue across individual products to identify the strongest contributors.

### Revenue by Age Group

A demographic visualization compares revenue across customer age groups.

### Revenue by Payment Method

A visualization compares revenue generated through:

- Cash
- Credit Card
- Debit Card
- Mobile Payment

### Revenue by Location

Revenue is compared across the ten buyer locations.

### Customer Analysis

Top customers are identified based on their revenue contribution.

### Sales Representative Analysis

Sales representatives are ranked based on profit and revenue contribution.

### Pricing Analysis

Revenue is compared between Expensive and Less Expensive products.

### Time-Based Analysis

Revenue is analyzed by:

- Month
- Weekday
- Weekday vs Weekend
- Quarter

The workbook also includes month-over-month and percentage contribution analysis.

## 6. Key Findings

- The business generated **61.57M in revenue and 26.78M in profit**, producing a **43.50% profit margin**.
- **Shortbread was the strongest product**, generating 13.97M in revenue and 10.87M in profit.
- Revenue was highly concentrated among the higher-priced products, with **89.46% of revenue coming from the Expensive price range**.
- **Travis Doyle was the highest-performing sales representative**, generating 10.88M in revenue and 4.78M in profit.
- **San Antonio was the strongest location**, generating approximately 7.34M in revenue.
- Customers aged **60–74 generated the highest revenue**, at approximately 14.84M.
- Revenue was relatively evenly distributed across payment methods, with Debit Card generating the highest revenue at approximately 15.62M.
- **72.59% of revenue was generated on weekdays**, compared with 27.41% on weekends.
- Q1 and Q2 accounted for approximately **70.9% of annual revenue**.
- Revenue declined substantially during Q3 and Q4, with Q4 contributing only **10.26% of annual revenue**.
- The large performance differences between sales representatives suggest an opportunity to investigate sales effectiveness, customer allocation, territory potential, and sales practices.

## Business Recommendations

1. **Protect the performance of Shortbread** because it is the largest contributor to both revenue and profit.

2. **Investigate the Q3 and Q4 revenue decline** to determine whether the pattern is caused by seasonality, inventory availability, customer demand, sales activity, or another operational factor.

3. **Analyze the performance gap between sales representatives** to identify practices used by high performers that could be replicated across the sales team.

4. **Investigate San Antonio's stronger performance** to determine whether customer demographics, product mix, sales coverage, or pricing explain its higher revenue.

5. **Use weekday demand patterns when planning sales resources**, since most revenue is generated during weekdays.

6. **Monitor revenue concentration among expensive products** to understand the risks associated with relying heavily on higher-priced products.

7. **Develop targeted strategies for lower-performing locations and sales representatives** rather than applying the same sales strategy across the entire business.