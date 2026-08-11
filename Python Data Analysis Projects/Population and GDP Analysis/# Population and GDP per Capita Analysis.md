# Population and GDP per Capita Analysis

## Business Question

**Is there a relationship between a country's population and its GDP per capita?**

The analysis investigates whether countries with larger populations tend to have higher GDP per capita and measures the strength of the relationship between the two variables.

## 1. Dataset

The dataset contains country-level information on:

- Country
- Population
- GDP per capita

The analysis compares population size with GDP per capita to identify patterns and relationships between the two variables.

## 2. Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 3. Data Cleaning

The analysis involved preparing the country-level data for analysis by:

- Inspecting the dataset and its variables.
- Checking the relevant population and GDP per capita fields.
- Preparing the numerical variables for correlation analysis.
- Handling data-quality issues where necessary before visualization.

## 4. Analysis

The analysis focused on measuring the relationship between:

**Population → GDP per capita**

A correlation coefficient was calculated to quantify the strength and direction of the relationship.

The resulting correlation coefficient was:

**0.78**

This indicates a strong positive correlation within the analyzed dataset.

## 5. Visualizations

A scatter plot was created using Matplotlib to visualize the relationship between population and GDP per capita.

- **X-axis:** Population
- **Y-axis:** GDP per Capita (USD)
- **Correlation:** 0.78

The scatter plot makes it possible to see the overall positive trend while also identifying countries that deviate from the general pattern.

## 6. Key Findings

- Population and GDP per capita showed a positive correlation of **0.78** in the analyzed data.
- The scatter plot indicates that higher population values were generally associated with higher GDP-per-capita values in this dataset.
- The relationship is **not perfectly linear**, meaning population alone does not explain differences in GDP per capita.
- Several observations deviate from the overall trend, suggesting that other economic and structural factors influence GDP per capita.