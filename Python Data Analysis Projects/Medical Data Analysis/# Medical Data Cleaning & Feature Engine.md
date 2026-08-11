# Medical Data Cleaning & Feature Engineering Analysis

## Business Question

How can medical patient data be cleaned, transformed, and restructured using Python and Pandas to create a more useful dataset for further analysis?

The project focuses on preparing patient-level medical data by examining BMI, creating a complete name field, separating age from the Gender field, and restructuring the dataset into a clearer format.

## 1. Dataset

The project uses a medical dataset stored in:

`medical_data.csv`

The dataset contains patient-level information including:

- First Name
- Last Name
- First Letter
- BMI
- Gender
- Condition

The `Gender` column initially contains both gender and age information, requiring additional transformation to create a separate `Age` column.

## 2. Tools

- Python
- Pandas

## 3. Data Cleaning

The following data-cleaning and transformation steps were performed:

- Loaded the medical dataset using Pandas.
- Inspected the first five rows using `head()`.
- Used `info()` to examine the dataset structure and data types.
- Calculated the first and third quartiles of the `BMI` column.
- Determined the IQR range for BMI.
- Created a copy of the original DataFrame before performing transformations.
- Combined the `First Name` and `Last Name` columns into a new `Name` column.
- Removed the original `First Name` and `Last Name` columns.
- Reordered the DataFrame columns for improved organization.
- Separated the `Gender` and `Age` information that was combined in the original `Gender` column.
- Created a dedicated `Age` column.
- Reordered the columns so that `Condition` appears as the final column.

## 4. Analysis

### BMI IQR Analysis

The first and third quartiles of the `BMI` column were calculated using Pandas `quantile()`.

The IQR range was then determined by identifying the values at the 25th and 75th percentiles.

### Name Feature Engineering

The separate `First Name` and `Last Name` columns were combined into a single `Name` column.

This creates a more convenient field for identifying patients.

### Age Feature Engineering

The original `Gender` column contained both gender and age information.

The column was split into two separate fields:

- `Gender`
- `Age`

This transformed the original combined field into two usable analytical variables.

### Dataset Restructuring

Unnecessary columns were removed and the remaining columns were reordered to create a cleaner and more logically structured DataFrame.

The final column structure was:

`Name, First Letter, BMI, Gender, Age, Condition`

## 5. Visualizations

No data visualizations were created in this project.

The project focuses on **data inspection, cleaning, feature engineering, and DataFrame restructuring using Pandas**.

## 6. Key Findings

- The dataset required restructuring before it could be used effectively for further medical data analysis.
- The BMI distribution was examined using the 25th and 75th percentiles to establish the IQR range.
- Separate first and last name fields were successfully combined into a single `Name` feature.
- The original `Gender` column contained both gender and age information, which was separated into distinct `Gender` and `Age` columns.
- Removing redundant columns and reorganizing the remaining fields produced a cleaner and more analysis-ready dataset.
- The project demonstrates practical use of Pandas for **data cleaning, feature engineering, string manipulation, and DataFrame restructuring**.