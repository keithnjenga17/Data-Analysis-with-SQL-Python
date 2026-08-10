##Project Overview
Insurance companies need to understand which customer segments generate the highest claim frequency, highest claim severity, and lowest risk exposure. Poor claim analysis leads to inaccurate pricing, weak fraud detection, and reduced profitability.

This project analyzes car insurance claims data using SQL and Python to identify:
High-risk customer groups
Claim patterns by driver profile
Relationships between demographics and claim amounts
Claim frequency by vehicle type and usage
Data quality issues affecting reporting accuracy

The analysis combines data cleaning, transformation, aggregation, window functions, and visualization techniques to simulate real-world insurance analytics workflows.

##Business Questions Solved
1. Data Quality & Duplicate Detection
Identified duplicate customer IDs
Removed duplicate records using window functions
Standardized inconsistent date formats
Cleaned categorical variables containing corrupted prefixes (z_)
Converted currency fields into numeric format for analysis
2. Claims Frequency Analysis
Determined how many customers filed claims
Measured claim distribution across customer categories
Identified longest streak of non-claim customers
3. Risk Segmentation
Compared claim behavior between:
Drivers with children
Drivers without children
Commercial vs private vehicle users
Male vs female customers
4. Vehicle Risk Analysis
Identified car types with:
Highest flagged claims
Lowest flagged claims
Analyzed average claim amount by:
Occupation
Vehicle type
5. Financial Exposure Analysis
Measured total claim amounts across customer segments
Compared current claims against historical claims
Evaluated claim exposure relative to home and vehicle asset values

##Technical Skills Demonstrated
##SQL Skills
Common Table Expressions (CTEs)
Recursive logic
Window functions:
ROW_NUMBER()
RANK()
Aggregations:
SUM()
AVG()
COUNT()
Conditional logic using CASE WHEN
Data cleaning using:
REPLACE()
CAST()
SUBSTR()
Date transformation and formatting
Duplicate removal techniques
Multi-step analytical pipelines

##Python Skills
Data ingestion with pandas
SQLite database integration
SQL query execution inside Jupyter Notebook
Data visualization using matplotlib
DataFrame manipulation
Database connection management

##Tools & Technologies
Python
SQLite
Pandas
Matplotlib
Jupyter Notebook (.ipynb)

##Analytical Approach

Step 1 Data Preparation
The raw dataset contained:
Duplicate IDs
Inconsistent date formats
Non-standard categorical labels
Currency fields stored as text
I cleaned and standardized the dataset before analysis to ensure reliable outputs.

Step 2 Exploratory Analysis
I investigated:
Claim distributions
Customer demographics
Vehicle categories
Historical claim behavior
Claim severity patterns

Step 3 Risk Segmentation
I grouped customers into risk categories using:
Family structure
Education level
Vehicle usage
Occupation
Asset ownership
This mirrors how insurers segment customers for underwriting and pricing decisions.

Step 4  Business Insight Generation
The analysis focused on surfacing insights useful for:
Pricing strategy
Fraud monitoring
Customer risk profiling
Claims reserve planning
Loss prevention strategy

##Key Insights
Data Quality Findings
Duplicate customer IDs existed in the dataset and were successfully removed
Multiple columns required extensive cleaning before analysis
Several financial fields were incorrectly stored as text
Claims Behavior Insights
Drivers with Children Generated Significant Claim Exposure
Customers with kid drivers contributed a notable share of total claims and claim amounts, suggesting increased household driving risk.
Vehicle Type Strongly Influenced Claim Frequency

Some car categories consistently produced:
Higher flagged claim counts
Larger cumulative claim amounts
This indicates that vehicle class is a major underwriting variable.
Occupation Correlated with Claim Severity
Certain occupations produced significantly higher average claim amounts within specific car types, highlighting behavioral and income-based risk patterns.
Gender-Based Claim Distribution Differences
Male and female customers showed different total claim contributions when filtering for financially qualified vehicle owners.
Educated Drivers Showed Distinct Usage Patterns

Drivers with higher education levels displayed different claim distributions between:
Commercial usage
Private usage
This can support targeted policy pricing models.
Long Non-Claim Streaks Exist

The project identified long sequences of customers with zero claim flags, which can support:
Loyalty discounts
Low-risk customer segmentation
Predictive insurance scoring
Visualization Highlights

##The project includes:
Horizontal bar charts for claim distribution by car type
Pie charts comparing gender-based claim proportions
Percentage-based annotations for fast business interpretation
These visualizations help communicate insights to non-technical stakeholders.