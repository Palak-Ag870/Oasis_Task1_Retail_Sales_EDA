# Oasis Infobyte – Task 1: Retail Sales EDA

## Project Overview

This project was completed as part of the Oasis Infobyte Data Analytics Internship – Data Analytics Track, Task 1.

The objective of this project is to perform Exploratory Data Analysis (EDA) on retail sales data to identify sales trends, customer characteristics, product category performance, relationships between numerical variables, and actionable business insights.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset contains 1,000 retail transaction records and 9 columns, including:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

The dataset file used in this project is included in this repository as `retail_sales_dataset.csv`.

## Analysis Performed

The notebook covers:

1. Initial dataset inspection
2. Missing-value and duplicate checks
3. Descriptive statistics
4. Date conversion and time-based analysis
5. Monthly sales trend analysis
6. Quarterly sales trend analysis
7. Customer age-group analysis
8. Gender distribution analysis
9. Product-category quantity and revenue analysis
10. Correlation matrix and heatmap
11. Average transaction amount by age group
12. Business conclusions and actionable recommendations

## Key Findings

- Clothing has the highest sales volume with 894 units.
- Electronics generates the highest revenue at 156,905.
- Female customers account for 510 records, while male customers account for 490 records.
- The 46–55 age group has the highest customer representation with 229 records.
- Price per Unit and Total Amount have a strong positive correlation of approximately 0.85.
- Quantity and Total Amount have a moderate positive correlation of approximately 0.37.
- Average transaction value generally decreases across the analyzed age groups.

## Business Recommendations

1. Strengthen Electronics promotion because it generates the highest revenue.
2. Use bundling, cross-selling, and premium product options to increase revenue from Clothing, which has the highest sales volume.
3. Test age-specific promotions and personalized campaigns based on differences in transaction values across age groups.

## Data Limitation

The dataset does not contain an individual Product Name or Product ID column. Therefore, a reliable Top 10 individual-product analysis cannot be performed. Instead, the project analyzes sales quantity and revenue at the available Product Category level.

## Repository Contents

```text
Oasis_Task1_Retail_Sales_EDA/
│
├── Task1_Retail_Sales_EDA.ipynb
├── retail_sales_dataset.csv
└── README.md
```

## Internship Details

**Organization:** Oasis Infobyte  
**Track:** Data Analytics  
**Task:** Task 1 – EDA on Retail Sales Data
