# Retail Sales and Profitability Analysis

## **Business Question**

How can retail sales data be analyzed to identify profitable products, understand product-level costs, and evaluate the relationship between revenue, costs, and profit?

## **1. Dataset**

The project uses a retail sales dataset named `retail_shop_data.csv`.

The dataset contains product-level information including:

* Product ID
* Product Name
* Price
* Cost
* Quantity
* Total sales/revenue

The dataset was loaded into a Pandas DataFrame for analysis.

## **2. Tools**

* **Python** – Data analysis
* **Pandas** – Data cleaning, manipulation, filtering, grouping, and aggregation
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Development environment

Key Pandas techniques used:

* `groupby()`
* `loc[]`
* `iloc[]`
* `query()`
* `sort_values()`
* `rename()`

## **3. Data Cleaning**

The dataset was prepared through the following steps:

* Loaded the CSV file into a Pandas DataFrame.
* Inspected the first five rows of the dataset.
* Checked the number of **rows and columns**.
* Checked for duplicate product names.
* Renamed columns to make them more descriptive:

  * `Total` → `Revenue`
  * `Price` → `Price Per Product`
  * `Cost` → `Cost Per Product`
* Created a **Costs** column by multiplying cost per product by quantity.
* Created a **Profit** column by subtracting total costs from revenue.
* Created a Boolean `Filter` column to identify products with profit greater than `$15`.

## **4. Analysis**

The analysis focused on understanding product-level revenue, costs, and profitability.

### Profitability Analysis

A profit calculation was performed for each product using:

```python
Profit = Revenue - Costs
```

Products were then filtered to identify those generating more than `$15` in profit.

### Product Comparison

The analysis compared profitability between:

* **Jackets and Sneakers**
* The most profitable and least profitable products
* Individual products such as **Sunglasses** and **Hoodie**

Product costs were also grouped and aggregated using `groupby()`.

### Profit Ranking

Products were sorted according to their profit to identify:

* The **least profitable products**
* The **most profitable product**

### Revenue and Cost Relationship

A scatter plot was created to examine the relationship between **Revenue** and **Costs** across products and to investigate whether a noticeable correlation exists between the two variables.

## **5. Visualizations**

### Sales, Costs and Profit

A stacked bar chart was created to compare **sales/revenue, costs, and profit** across the least profitable products.

This visualization provides a product-level view of how revenue is distributed between costs and profit.

### Revenue vs. Costs

A Seaborn scatter plot was created to examine the relationship between:

* **Revenue**
* **Costs**

Each point represents a product record, allowing potential relationships between sales and costs to be visually identified.

## **6. Key Findings**

* The analysis demonstrates how retail transaction data can be transformed into useful **product-level profitability metrics**.
* Total product costs were calculated by combining **cost per product with quantity sold**.
* Profit was calculated by subtracting total costs from revenue.
* Products generating more than `$15` in profit were identified using a Boolean filtering approach.
* Product-level aggregation was used to compare profitability and costs across different products.
* The analysis identified the **most and least profitable products** by sorting products according to their calculated profit.
* Specific products, including **Sunglasses, Hoodie, Jacket, and Sneakers**, were analyzed individually.
* The revenue-versus-cost scatter plot provides a way to assess whether higher revenue is associated with higher costs.


## **Project Outcome**

The project demonstrates an end-to-end **retail profitability analysis workflow**, using Python to clean and transform sales data, calculate costs and profit, compare product performance, identify profitable and less-profitable products, and visualize relationships between revenue and costs.
