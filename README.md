# Retail Sales Analytics Using Python

## Project Overview

Retail businesses generate large volumes of transaction data containing information about products, quantities, prices, customers, dates, and locations.

This project analyzes retail transaction data to understand sales performance and identify meaningful patterns in products, customers, countries, and sales trends.

The project uses the UCI Online Retail dataset and applies Python-based data cleaning, exploratory data analysis, statistical analysis, visualization, and business insight generation.

---

## Problem Statement

Raw retail transaction data does not directly reveal important patterns in sales performance, product demand, customer purchasing behavior, or geographic sales distribution.

The purpose of this project is to analyze retail sales transaction data and identify meaningful trends, relationships, variations, and business insights that can support data-driven decision-making.

---

## Objectives

- Understand the structure and quality of the retail sales dataset.
- Clean and prepare transaction data for analysis.
- Analyze overall sales performance.
- Examine sales trends over time.
- Identify top-performing products.
- Analyze customer purchasing patterns.
- Compare sales performance across countries.
- Examine relationships between important sales variables.
- Identify unusual transactions and data-quality issues.
- Create meaningful visualizations.
- Generate business insights and recommendations.

---

## Dataset

The project uses the **UCI Online Retail Dataset** from the UCI Machine Learning Repository.

The dataset contains retail transaction information including:

- Invoice number
- Product stock code
- Product description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

The dataset is downloaded automatically from the UCI repository when the notebook is executed.

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab
- Excel / OpenPyXL

---

## Project Workflow

The analysis follows these major stages:

1. Project Overview
2. Problem Statement
3. Objectives
4. Dataset Loading
5. Initial Dataset Inspection
6. Data Cleaning and Preparation
7. Exploratory Data Analysis
8. Correlation Analysis
9. Monthly Sales Performance
10. Customer Purchasing Analysis
11. Product Performance Analysis
12. Outlier and Data Quality Analysis
13. Product Data Quality Check
14. Product-Only Analysis
15. Key Business Metrics
16. Business Insights and Recommendations
17. Conclusion

---

## Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate transaction records.
- Removed records with missing product descriptions.
- Identified cancelled transactions.
- Removed cancelled transactions from the valid sales dataset.
- Removed transactions with non-positive quantities.
- Removed transactions with non-positive unit prices.
- Created a Revenue column using:

```text
Revenue = Quantity × UnitPrice