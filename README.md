# Retail Sales Analytics Using Python

## Major Data Analytics Project

A data analytics project focused on analyzing retail transaction data to understand sales performance, product demand, customer purchasing behaviour, geographic sales distribution, and sales trends.

The project applies **Data Cleaning, Exploratory Data Analysis (EDA), Statistical Analysis, Data Visualization, Outlier Analysis, and Business Insight Generation** to transform raw retail transaction data into meaningful business information.

---

## Student Information

| Field | Details |
|---|---|
| **Student Name** | SUJITHA LAKSHMI S |
| **AICTE Student ID** | STU6820e8ae215fd1746987182 |
| **College** | PANIMALAR ENGINEERING COLLEGE |
| **Department** | Artificial Intelligence and Machine Learning (AIML) |
| **Project Title** | Retail Sales Analytics Using Python |

---

## Problem Statement

Retail businesses generate large volumes of transaction data containing information about products, quantities, prices, customers, dates, and locations.

Raw transaction data alone does not directly reveal important patterns in sales performance, product demand, customer purchasing behaviour, or geographic sales distribution.

This project analyzes retail transaction data to identify meaningful trends, relationships, variations, and unusual transaction patterns.

The findings are used to generate evidence-based business insights and recommendations that can support data-driven decision-making.

---

## Objectives

1. Load and understand a real-world retail transaction dataset.
2. Perform data quality checks on the transaction data.
3. Clean and prepare the dataset for analysis.
4. Calculate transaction-level revenue.
5. Analyze overall sales performance.
6. Examine monthly sales trends.
7. Identify top-performing products.
8. Analyze customer purchasing patterns.
9. Compare sales performance across countries.
10. Examine relationships between important sales variables.
11. Identify unusual transactions and data-quality issues.
12. Create meaningful visualizations for retail sales analysis.
13. Generate business insights from the analytical results.
14. Provide practical recommendations based on the findings.

---

## Dataset

The project uses the **Online Retail dataset** from the **UCI Machine Learning Repository**.

### Dataset Source

**UCI Machine Learning Repository**

Dataset link:

https://archive.ics.uci.edu/dataset/352/online+retail

### Dataset Summary

| Property | Value |
|---|---:|
| **Original transactions** | 541,909 |
| **Original columns** | 8 |
| **Transaction period** | December 2010 – December 2011 |
| **Final valid sales transactions** | 524,878 |
| **Unique invoices** | 19,960 |
| **Physical products analysed** | 4,018 |
| **Countries represented** | 38 |
| **Identified customers** | 4,338 |

### Main Attributes

| Column | Description |
|---|---|
| `InvoiceNo` | Invoice or transaction number |
| `StockCode` | Product stock code |
| `Description` | Product description |
| `Quantity` | Quantity purchased |
| `InvoiceDate` | Transaction date and time |
| `UnitPrice` | Price per unit |
| `CustomerID` | Customer identifier |
| `Country` | Customer country |

---

## Dataset Loading

The project is designed to run directly in **Google Colab** without requiring manual dataset upload.

The notebook automatically:

1. Creates the required `data` directories.
2. Downloads the official Online Retail dataset from the UCI Machine Learning Repository.
3. Extracts the downloaded ZIP file.
4. Loads `Online Retail.xlsx` using Pandas.
5. Continues with the complete retail sales analysis pipeline.

The raw dataset is **not stored inside the GitHub repository** because the notebook can download it automatically when required.

### Automatic Dataset Flow

```text
UCI Machine Learning Repository
            ↓
Download online+retail.zip
            ↓
Extract ZIP file
            ↓
Online Retail.xlsx
            ↓
Load using Pandas
            ↓
Data Cleaning
            ↓
Retail Sales Analysis
