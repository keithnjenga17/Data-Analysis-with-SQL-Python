# Flower Dataset — Machine Learning Data Preprocessing

## **Business Question**

How can a flower dataset be prepared and transformed into a machine-learning-ready format so that a model can predict the **flower type** based on its available features?

## **1. Dataset**

The project uses a CSV dataset named `flower_dataset.csv`.

The dataset contains flower observations, including:

* Flower features used as **predictor variables**
* `flower_type` as the **target variable**

The dataset was loaded into a Pandas DataFrame and inspected using `head()`.

## **2. Tools**

* **Python** – Machine-learning data preparation
* **Pandas** – Data loading and manipulation
* **Scikit-learn** – Data preprocessing and train-test splitting
* **Jupyter Notebook** – Development environment

Key Scikit-learn techniques used:

* `LabelEncoder`
* `train_test_split`
* `StandardScaler`

## **3. Data Cleaning**

The dataset was prepared for machine learning through the following steps:

* Loaded the CSV dataset into a Pandas DataFrame.
* Created a copy of the original DataFrame to preserve the source data.
* Converted the categorical `flower_type` target variable into numerical values using **LabelEncoder**.
* Separated the dataset into:

  * **X** – predictor/features
  * **y** – target variable (`flower_type`)
* Split the dataset into training and testing sets using an **80/20 split**.
* Set `random_state=42` to ensure that the same observations are consistently assigned to the training and test sets.
* Standardized the feature variables using **StandardScaler**.

## **4. Analysis**

The project focused on preparing the dataset for a **supervised classification model**.

The analysis followed these steps:

1. Identified `flower_type` as the target variable.
2. Encoded the categorical target into numerical values.
3. Separated the predictors (`X`) from the target (`y`).
4. Divided the data into training and testing datasets.
5. Used **80% of the data for training** and **20% for testing**.
6. Standardized the feature values using `StandardScaler`.
7. Applied the scaling parameters learned from the training data to the test data.

Standardization ensures that the numerical features are placed on a comparable scale before being used to train a machine-learning model.

## **5. Visualizations**

The current notebook does **not contain visualizations**.

Potential visualizations that could be added include:

* Distribution of the flower features
* Feature comparison by `flower_type`
* Scatter plots showing relationships between flower features
* Class distribution of the different flower types

These visualizations could help identify patterns and relationships between the predictor variables and flower type before building a classification model.

## **6. Key Findings**

* The `flower_type` variable is a categorical target and therefore needed to be converted into numerical form before machine-learning processing.
* **LabelEncoder** was used to transform the flower categories into numerical labels.
* The dataset was separated into predictor variables (`X`) and the target variable (`y`).
* An **80/20 train-test split** was implemented to separate data used for training from data used for testing.
* `random_state=42` ensures reproducibility of the train-test split.
* **StandardScaler** was used to standardize the predictor variables.
* The preprocessing pipeline successfully transformed the raw dataset into a format suitable for training a supervised machine-learning classification model.

## **Project Outcome**

The project demonstrates the fundamental **data-preprocessing workflow for supervised machine learning**, taking a raw flower dataset and preparing it for classification by encoding the target variable, separating predictors from the target, splitting the data into training and testing sets, and standardizing the features.

The prepared dataset can subsequently be used to train and evaluate a **classification model for predicting flower type**.
