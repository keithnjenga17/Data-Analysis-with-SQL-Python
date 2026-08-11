# Time Series Analysis: Price Movement and Trends

## Business Question

How does the value of the dataset change over time, and what daily, hourly, and short-term trends can be identified through time-series analysis?

The analysis examines value movements over time and uses aggregation and rolling averages to identify patterns that may not be immediately visible in the raw observations.

## 1. Dataset

The project uses a time-series dataset stored in:

`time_series_data.csv`

The dataset contains:

- `date` — date and time of each observation
- `value` — numerical value recorded at each observation

The analysis treats the date as a time-series index to examine changes across days and hours.

## 2. Tools

- Python
- Pandas
- Matplotlib

## 3. Data Cleaning

The following data preparation steps were performed:

- Loaded the dataset using Pandas.
- Inspected the data types of the dataset.
- Created a copy of the original DataFrame for analysis.
- Converted the `date` column to datetime format.
- Set the `date` column as the DataFrame index.
- Prepared the time-series data for resampling and time-based analysis.

## 4. Analysis

### Daily Maximum Values

The dataset was resampled to daily intervals using Pandas `resample()` and the maximum value for each day was calculated.

This provides a daily view of the highest recorded value and helps identify changes in daily peaks.

### Value Movement Over Time

The original values were analyzed chronologically to examine how the value changed throughout the observation period.

### Hourly Analysis

The data was grouped by the hour of the day and the mean value for each hour was calculated.

This helps identify whether values tend to be higher or lower at particular times of the day.

### Rolling Average

A rolling average with a window size of 3 was calculated.

The rolling average was compared with the original values to smooth short-term fluctuations and make the underlying trend easier to observe.

## 5. Visualizations

The analysis includes the following visualizations:

- **Line plot** — shows value movement over time.
- **Bar plot** — compares the mean value across hours of the day.
- **Line plot with rolling average** — compares the original values with the 3-period rolling average.

## 6. Key Findings

- The analysis demonstrates how time-series data can be aggregated into daily intervals to examine daily maximum values.
- Value movement varies over time, with the line plot providing a view of changes throughout the observation period.
- Hourly aggregation allows differences in average values across the 24 hours of the day to be identified.
- The 3-period rolling average smooths short-term fluctuations and makes the underlying trend easier to interpret.
- Comparing the original series with the rolling average provides a clearer view of overall movement while reducing the effect of individual fluctuations.