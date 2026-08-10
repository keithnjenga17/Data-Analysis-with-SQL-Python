##Project Overview
Elite athletics organizations, sports analysts, and performance coaches rely on historical race data to evaluate athlete dominance, compare national performance trends, and identify improvements in long-distance running over time.

This project analyzes long-distance runner statistics using SQL and Python to uncover:
The most accomplished runners across major competitions
Countries producing the strongest marathon athletes
Performance trends across years
Fastest athletes by race category
Changes in elite marathon performance over time

The analysis demonstrates practical business-style analytics workflows including ranking analysis, time-based comparisons, aggregation, and performance benchmarking.

##Business Problem
Sports organizations and analysts need to answer critical questions such as:
Which athletes consistently dominate international competitions?
Which countries produce the highest-performing marathon runners?
How has marathon performance evolved over time?
Which race categories have the most competitive athletes?
What trends can be identified from historical runner performance data?

Without structured analysis, it becomes difficult to:
Evaluate athlete performance objectively
Benchmark elite competitors
Identify national athletic strengths
Measure improvements in endurance sports over time

##Technical Skills Demonstrated
SQL Skills
Common Table Expressions (CTEs)
Window Functions:
DENSE_RANK()
ROW_NUMBER()
Aggregations:
SUM()
AVG()
MIN()
COUNT()
View creation
Multi-step analytical queries
Conditional filtering
Time conversion and formatting
Ranking and leaderboard analysis

##Python Skills
CSV ingestion with pandas
SQLite database integration
Query execution in Jupyter Notebook
Data pipeline creation
Error handling using try-except
Tools & Technologies
Python
SQLite
Pandas
Jupyter Notebook (.ipynb)

##Analytical Approach
Step 1 Data Loading
The dataset was imported into SQLite using Python and Pandas to create a structured analytical environment for querying runner statistics.

Step 2  Performance Ranking Analysis
I ranked athletes based on:
Olympic medals
World records
Championship success
This helped identify the most dominant runners across multiple achievement metrics.

Step 3 National Performance Benchmarking

The analysis evaluated:
Which countries produced the most successful marathon runners
Total medal counts by nationality
Number of elite athletes per country
This simulated country-level sports performance benchmarking.

Step 4 Race Performance Analysis
I compared:
Fastest marathon times
Fastest 5000m times
Best yearly marathon performances
This allowed direct comparison of elite athlete performance across race categories and years.

Step 5 Historical Trend Analysis
Average winning marathon times before and after 2014 were analyzed to identify:
Improvements in endurance performance
Competitive evolution in marathon racing
Performance acceleration trends
##Key Insights
Elite Runner Dominance
The ranking analysis identified a small group of athletes consistently dominating through:
Olympic success
Championship victories
World record achievements
This highlights the concentration of elite performance at the highest competition level.
Certain Countries Produce More Elite Marathon Athletes

Some nationalities consistently generated:

Higher medal counts
More elite marathon winners
This suggests stronger long-distance running systems, athlete development pipelines, and endurance training cultures.
Marathon Performance Improved Over Time
The comparison of average winning marathon times showed measurable improvement in post-2014 results, indicating:

Better athlete conditioning
Improved race strategy
Advancements in sports science and training
Fastest Athletes Differ by Race Category

The analysis revealed that dominance in:
5000m races
Marathon races
does not always overlap, emphasizing specialization within endurance sports.
Consistent Top Performers Emerged Across Multiple Year
Using yearly ranking analysis, the project identified athletes who repeatedly achieved top marathon results across different seasons.
This supports longitudinal athlete performance tracking.

##Example Business Questions Solved
Athlete Ranking
Who are the top-performing long-distance runners globally?
Country Benchmarking
Which nationality has produced the most successful marathon athletes?
Race Analysis
Who recorded the fastest times in Marathon and 5000m races?
Historical Trends
Did elite marathon finishing times improve after 2014?
Competitive Consistency
Which runners repeatedly ranked first across years?