##Project Overview
This project analyzes UEFA Champions League player, goal, and match data using SQL, SQLite, and Python to uncover insights related to goal-scoring patterns, player performance, age analysis, and match statistics.

The analysis focuses on:
top goal scorers,
goal distribution patterns,
age-related scoring trends,
and performance differences across player profiles.

##Business Problem
Football analysts and scouting teams need data-driven insights to better understand:
player scoring behavior,
team attacking performance,
age-performance relationships,
and match contribution trends.

This project uses relational football datasets to support performance analysis and player evaluation.

##Technical Skills Demonstrated
Skill	-Application
Python	-Data ingestion and analysis
SQLite	-Relational database querying
Pandas	-Data loading and preprocessing
SQL Window Functions	-Ranking player performance
Data Cleaning	-Date standardization and null handling
Query Optimization	-Index creation for faster joins

##Analysis Performed
The project explored:
goal type distribution,
top goal scorers by team,
first-half vs second-half scoring patterns,
header goal trends among forwards,
and age-group scoring analysis during the 2021–2022 season.
SQL Skills Demonstrated
ROW_NUMBER()
Common Table Expressions (CTEs)
Aggregate functions
CASE WHEN
JULIANDAY()
Data cleaning with UPDATE
Index creation
Multi-table joins
Performance optimization
Analytical Thinking Demonstrated
Applied indexing to improve query performance on large relational joins.
Standardized inconsistent date formats for accurate age calculations.
Used window functions to rank top scorers within teams.
Segmented players by age and physical attributes to evaluate scoring behavior.
Combined match, player, and goal datasets to produce performance-based insights.

##Key Insights
Right-footed and left-footed shots accounted for the majority of goals scored.
Top scorers contributed significantly to overall team attacking output.
Goal distribution varied between first and second halves of matches.
Taller forwards showed stronger performance in aerial goal scoring situations.
Players aged 26–30 contributed a substantial share of goals during the 2021–2022 season.

##Data Engineering & Cleaning
The project included:
converting inconsistent date formats into SQLite-compatible dates,
removing invalid records,
handling null values,
and preparing relational datasets for analytical querying.

These preprocessing steps improved query reliability and analytical accuracy.