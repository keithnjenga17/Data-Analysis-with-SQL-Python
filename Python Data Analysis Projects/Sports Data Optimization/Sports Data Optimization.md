# Sports Data Cleaning and Optimization Analysis

## Business Question

How can Pandas be used to inspect, optimize, clean, filter, and export sports data efficiently?

The analysis focuses on improving the structure and memory efficiency of a sports dataset while creating a filtered dataset containing players who committed more than six fouls.

## 1. Dataset

The project uses a sports dataset stored in:

`sports_data.csv`

The dataset contains player-level information, including:

- Player Name
- Sport
- Team
- Fouls
- Yellow Cards
- Other player performance information

The analysis focuses on understanding the structure of the dataset, optimizing its data types, and filtering players based on the number of fouls committed.

## 2. Tools

- Python
- Pandas

## 3. Data Cleaning

The following data preparation and optimization steps were performed:

- Loaded the sports dataset using Pandas.
- Inspected the first five rows to confirm that the dataset loaded correctly.
- Identified columns with an `object` data type.
- Checked the memory usage of the original DataFrame using `memory_usage(deep=True)`.
- Converted the `Name`, `Sport`, and `Team` columns from `object` to `category` data types.
- Compared the memory usage before and after converting columns to categorical data types.
- Renamed the `Yellow` column to `Yellow Cards` to make the column name more descriptive.
- Created a filtered DataFrame containing players who committed more than six fouls.
- Reset the index of the filtered DataFrame.

## 4. Analysis

The analysis focused on four main areas:

### Data Type Analysis

The data types of the columns were inspected to identify columns stored as `object` data types.

The analysis identified:

- `Name`
- `Sport`
- `Team`

as object-type columns.

### Memory Optimization

The memory usage of the original DataFrame was calculated using:

`df.memory_usage(deep=True)`

The `Name`, `Sport`, and `Team` columns were then converted from `object` to `category` data types.

The memory usage of the optimized DataFrame was subsequently calculated to compare the effect of the conversion.

### Data Filtering

The Pandas `query()` method was used to create a subset containing only players who committed more than six fouls.

### Data Export

The resulting filtered DataFrame was exported as:

`sports_data_modified.csv`

## 5. Visualizations

No data visualizations were created in this project.

The project focuses primarily on **data inspection, data-type optimization, memory usage, filtering, and data export using Pandas**.

## 6. Key Findings

- The dataset contained three columns stored as `object` data types: `Name`, `Sport`, and `Team`.
- Converting these columns to the `category` data type provided a more memory-efficient representation of the data.
- The `Yellow` column was renamed to `Yellow Cards` to improve clarity and readability.
- Pandas `query()` was used to efficiently identify players who committed more than six fouls.
- The filtered dataset was successfully exported to `sports_data_modified.csv`.
- The project demonstrates how appropriate Pandas data types can improve memory efficiency when working with categorical data.