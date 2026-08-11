# Customer Service Performance Analysis Dashboard

## Business Question

How effectively is the customer service team handling calls, and what factors influence call success, failure, and abandonment?

The analysis evaluates call outcomes, agent performance, customer characteristics, products discussed, call duration, and abandonment reasons to identify opportunities for improving customer service operations.

## 1. Dataset

The dataset contains **200,000 customer service call records** covering the period from **January 1, 2024 to December 31, 2024**.

Key fields include:

- Call ID
- Date
- Agent
- Agent Rating
- Product Discussed
- Call Duration
- Call Outcome
- Customer Age
- Customer Gender
- State
- Customer Income Bracket
- Time of Day
- Follow-Up Call Required
- Repeat Customer
- Reason for Call Abandonment

### Call Outcomes

Calls are classified into three outcomes:

- Success
- Failure
- Abandoned

The dataset contains:

- **83,519 successful calls**
- **71,837 failed calls**
- **44,644 abandoned calls**

## 2. Tools

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Excel Dashboard
- Slicers/Filters
- Data Cleaning and Transformation
- Excel formulas and calculations

## 3. Data Cleaning

The data preparation process included:

- Converting the date field from Excel serial values into usable dates.
- Creating an **Agent Full Name** field by combining agent first and last names.
- Inspecting missing values across the dataset.
- Identifying missing values associated with abandoned calls.
- Standardizing call outcome categories.
- Reviewing product and customer attributes for analysis.
- Preparing the data for Pivot Table and dashboard analysis.

Missing values in fields such as **Product Discussed, Agent Rating, and Call Duration** were primarily associated with abandoned calls.

## 4. Analysis

### Call Outcome Analysis

The analysis examined the distribution of calls across the three outcomes.

| Call Outcome | Calls | Percentage |
|---|---:|---:|
| Success | 83,519 | 41.76% |
| Failure | 71,837 | 35.92% |
| Abandoned | 44,644 | 22.32% |
| **Total** | **200,000** | **100%** |

Among calls that were not abandoned, approximately **53.76% were successful**.

### Agent Performance

Agent performance was evaluated using:

- Number of calls handled
- Call success rate
- Average agent rating
- Average call duration

The analysis identified substantial differences in success rates between agents.

For example:

- **Samuel Smith** had the highest observed success rate at approximately **90.55%**.
- **Monique Lawrence** recorded approximately **90.27%**.
- **Olivia Lyons** recorded approximately **90.05%**.
- Several agents recorded success rates close to **20%**.

This variation makes agent-level performance an important area for management investigation.

### Product Analysis

Calls involved five main products:

- Loans — 50,173 calls
- Internet Package — 49,988 calls
- Electronics — 25,868 calls
- Travel Package — 21,700 calls
- Insurance — 7,627 calls

Among completed calls, success rates were relatively similar across products, ranging from approximately **53.36% to 54.10%**.

### Call Abandonment Analysis

Abandoned calls were analyzed according to the recorded reason.

The main recorded reasons included:

- Long Wait Time
- Agent Not Available
- Technical Issues
- Customer Hung Up

**Long Wait Time was by far the largest recorded abandonment reason**, accounting for approximately **94.44% of categorized abandonment reasons** when the two differently capitalized "Long Wait Time" entries are combined.

This indicates that reducing customer waiting time could be an important operational improvement area.

### Call Duration

Average call duration for non-abandoned calls was approximately:

**16.91 minutes**

Average duration was also compared across agents to identify differences in handling time.

### Customer Analysis

Call outcomes were compared across:

- Customer gender
- Income bracket
- Repeat-customer status
- Time of day

These customer characteristics showed relatively similar call-outcome distributions in the analyzed dataset.

For example, success rates were approximately:

- Male customers: **41.79%**
- Female customers: **41.69%**

Similarly, success rates across morning, afternoon, and evening calls were very similar.

## 5. Visualizations

The Excel dashboard provides an interactive view of customer service performance using:

### KPI Cards

Key metrics include:

- Total Calls
- Successful Calls
- Failed Calls
- Abandoned Calls

### Call Outcome Analysis

Visualizations compare:

- Successful calls
- Failed calls
- Abandoned calls

This provides an overview of overall call-center performance.

### Agent Performance

Agent-level analysis compares:

- Number of calls
- Call success
- Average agent rating
- Average call duration

### Product Analysis

Charts compare call activity across:

- Loans
- Internet Package
- Electronics
- Travel Package
- Insurance

### Abandonment Analysis

Visualizations identify the main reasons customers abandoned calls, highlighting waiting time as the dominant issue.

### Time Analysis

Call activity can be analyzed across:

- Months
- Time of day

This allows management to identify patterns in call volume and outcomes.

### Interactive Filtering

The dashboard uses Excel filtering/slicer functionality to allow users to explore the data by relevant dimensions.

## 6. Key Findings

- The dataset contains **200,000 customer service calls** during 2024.
- **41.76% of all calls were successful**, while **35.92% failed** and **22.32% were abandoned**.
- Among calls that were not abandoned, the success rate was approximately **53.76%**.
- Agent performance varied significantly, with some agents achieving approximately **90% success rates while others were around 20%**.
- **Long Wait Time was the dominant recorded reason for call abandonment**, accounting for approximately 94% of categorized abandonment reasons when duplicate capitalization is combined.
- Loans and Internet Packages were the two most frequently discussed products.
- Product-level success rates were relatively consistent, suggesting that product type alone does not explain the large differences in overall call outcomes.
- Customer gender, income bracket, repeat-customer status, and time of day showed relatively small differences in success rates.
- The average duration of non-abandoned calls was approximately **16.91 minutes**.

## Business Recommendations

Based on the analysis:

1. **Investigate long waiting times** as the primary operational cause of abandoned calls.
2. **Investigate the large differences in agent success rates** to identify differences in training, call allocation, processes, or data-recording patterns.
3. **Use agent performance metrics together**, rather than success rate alone, by considering call volume, ratings, and average handling time.
4. **Monitor abandonment rates regularly** to determine whether improvements in staffing and response times reduce lost customer interactions.
5. **Continue monitoring product-level performance** to identify whether changes in product mix affect customer service outcomes.