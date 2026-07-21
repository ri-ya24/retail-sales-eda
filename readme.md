# Retail Sales Exploratory Data Analysis (EDA)

## Objective
This project analyzes a retail sales dataset to identify sales trends, clean and preprocess data, visualize key metrics, and generate business insights using Python.

The goal is to understand sales performance, customer behaviour, and patterns that can support data-driven business decisions.

## Tools & Libraries Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib

## Dataset
The dataset (`Superstore Sales Dataset.csv`) contains 9,800 retail transaction records with information such as:

- Order Date
- Ship Date
- Customer Segment
- Region
- State
- Category
- Sub-Category
- Product Name
- Sales
## Project Workflow
The following steps were performed during the analysis:

- Data loading and initial exploration
- Data cleaning and preprocessing
- Handling missing values and duplicate records
- Converting Sales data into numeric format
- Category-wise sales analysis
- Region-wise sales comparison
- State and product performance analysis
- Monthly sales trend analysis
- Customer segment analysis
- Sales distribution and outlier analysis
## Key Analysis Performed

### Category-wise Sales Analysis
Analyzed sales contribution from different product categories to identify the highest revenue-generating categories.

### Region-wise Sales Analysis
Compared sales performance across different regions to understand regional contribution.

### Top 10 States by Sales
Identified states generating the highest sales revenue.

### Top 10 Products by Sales
Analyzed products contributing significantly to overall sales.

### Monthly Sales Trend
Studied monthly sales patterns to identify fluctuations and seasonal trends.

### Customer Segment Analysis
Compared sales among different customer segments:
- Consumer
- Corporate
- Home Office

### Sales Distribution Analysis
Analyzed transaction value distribution and identified potential outliers in sales data.
# Key Insights
- Furniture generated the highest total sales among all categories, followed by Technology and Office Supplies.
- The West region led in total sales, followed by the East region.
- California and Texas emerged as the top-performing states.
- The Consumer segment contributed the largest share of total sales.
- Monthly sales trends showed fluctuations and seasonal patterns.
- Some transactions had unusually high sales values, representing characteristics of the source dataset.

## Note on Data
Some Sales values in this dataset are unusually high compared to typical retail transactions. This reflects a characteristic of the source data itself rather than an error introduced during cleaning.

## Conclusion
This project demonstrates how Exploratory Data Analysis (EDA) can help businesses understand sales performance, discover patterns, and generate meaningful insights using Python, Pandas, NumPy, and Matplotlib.

## Project Files
- [Retail_Sales_EDA.ipynb](Retail_Sales_EDA.ipynb) - Complete exploratory data analysis notebook
- [Superstore Sales Dataset.csv](Superstore%20Sales%20Dataset.csv) - Dataset used for analysis


