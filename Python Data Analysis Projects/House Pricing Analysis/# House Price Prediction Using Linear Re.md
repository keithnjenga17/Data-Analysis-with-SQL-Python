# House Price Prediction Using Linear Regression

## **Business Question**

Can property and location-related features be used to predict the **price of a residential property per unit area**, and how accurately can a linear regression model make these predictions?

## **1. Dataset**

The project uses the `house_price_prediction_data.csv` dataset.

The dataset contains information about properties, including:

* Transaction year and date
* House age
* Distance to the nearest MRT station
* Number of convenience stores
* Geographic coordinates
* House price per unit area — **target variable**

The dataset was loaded into a Pandas DataFrame and inspected for its structure, missing values, and duplicate records.

## **2. Tools**

* **Python** – Data analysis and machine learning
* **Pandas** – Data loading and manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Data preprocessing, model development, and evaluation
* **Joblib** – Saving and loading the trained machine-learning model
* **Jupyter Notebook** – Development environment

Key machine-learning techniques used:

* `StandardScaler`
* `train_test_split`
* `LinearRegression`
* `R² Score`
* `Mean Squared Error (MSE)`
* `Cross-validation`
* `Learning Curves`

## **3. Data Cleaning**

The dataset was prepared through several preprocessing steps:

* Checked the dataset for **missing values**.
* Checked the dataset dimensions using its **shape**.
* Checked for **duplicate records**.
* Created a copy of the original DataFrame before making modifications.
* Removed potential outliers by excluding observations where the house price per unit area was **115 or higher**.
* Removed the `No` column because it functions as an identifier rather than a predictive feature.
* Processed the transaction date column by separating the year component.
* Shuffled the dataset using Scikit-learn's `shuffle()` function with `random_state=42` to reduce potential bias caused by the original ordering of the observations.

## **4. Analysis**

The analysis focused on understanding relationships between property characteristics and house prices before developing a predictive model.

### Exploratory Analysis

The following relationships were investigated:

1. **House age vs. house price**

   * A scatter plot was used to examine the relationship between house age and price per unit area.

2. **Number of convenience stores vs. house price**

   * A Seaborn bar plot was used to examine whether the number of nearby convenience stores was associated with house price.

3. **House price distribution**

   * A histogram was created to examine the distribution of the target variable.
   * The mean house price per unit area was calculated and displayed on the distribution plot.
   * The distribution was also inspected for potential outliers.

### Machine-Learning Analysis

The cleaned dataset was divided into:

* **X** – predictor/features
* **y** – house price per unit area

The data was then split into:

* **90% training data**
* **10% testing data**

A **Linear Regression** model was selected and trained using the standardized feature variables.

The model was evaluated using:

* **R² Score** – measures how well the model explains variation in house prices.
* **Mean Squared Error (MSE)** – measures the average squared difference between actual and predicted prices.

To assess how the model performs on unseen data, **10-fold cross-validation** was also performed.

A **learning curve** was generated to compare training and validation performance at different training-set sizes.

## **5. Visualizations**

The project includes several visualizations:

### House Age vs. Price

A scatter plot was used to investigate the relationship between **house age** and **house price per unit area**.

### House Price vs. Convenience Stores

A bar plot was used to examine the relationship between the **number of convenience stores** and house price.

### House Price Distribution

A histogram was used to examine the distribution of the target variable, with a line representing the **mean house price per unit area**.

### Learning Curve

A learning curve was used to compare **training and validation R² scores** as the training dataset increased.

This helped assess how the model's performance changes with additional training data.

## **6. Key Findings**

* The dataset required basic quality checks for **missing values and duplicate records** before modeling.
* Exploratory analysis was used to investigate potential relationships between property characteristics and house prices.
* Potential high-price outliers were removed before model training.
* The dataset was shuffled to reduce potential bias resulting from the original ordering of the observations.
* Feature variables were standardized using **StandardScaler** before fitting the linear regression model.
* The Linear Regression model was evaluated using both **R² Score and Mean Squared Error**.
* **10-fold cross-validation** was used to obtain a more robust assessment of model performance on unseen data.
* The learning curve provided additional insight into the relationship between training-set size and model performance.
* The trained regression model was saved using **Joblib**, allowing it to be loaded later and used to generate predictions.

## **Project Outcome**

The project demonstrates an end-to-end **machine-learning workflow for house-price prediction**, from data inspection and cleaning through exploratory analysis, feature preprocessing, model training, evaluation, cross-validation, and model persistence.

The final trained model can be saved and loaded for making predictions on new property data.
