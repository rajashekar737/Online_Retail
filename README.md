# Week 2 – Exploratory Data Analysis and Visualization

## Project Overview

This project presents an Exploratory Data Analysis (EDA) and visualization of the Online Retail dataset using Python.

The objective is to understand transaction patterns, revenue trends, customer behavior, product performance, country-level revenue, and time-based activity through statistical analysis and data visualization.

## Objectives

- Understand the structure and characteristics of the Online Retail dataset.
- Perform descriptive and exploratory statistical analysis.
- Identify patterns and trends in transaction volume and revenue.
- Analyze customer, product, country, and time-based behavior.
- Create meaningful visualizations using Python.
- Identify correlations, patterns, anomalies, and data-quality issues.
- Interpret the findings from a business perspective.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

## Dataset

The project uses the publicly available Online Retail dataset.

The dataset contains:

- 541,909 transaction records
- 25,900 unique invoices
- 4,070 unique products
- 4,372 identified customers
- 38 countries

## Data Quality Findings

The analysis identified:

- 5,268 duplicate records
- 135,080 missing CustomerID values
- 10,624 negative quantity records
- 2,515 zero UnitPrice records
- 9,288 cancelled invoice records

These observations were interpreted according to their potential business meaning rather than being blindly removed.

## Key Findings

- Total net transaction revenue: 9,747,747.93
- Average transaction revenue: 17.99
- Median transaction revenue: 9.75
- Average quantity: 9.55
- Median quantity: 3.00
- The United Kingdom generated 8,187,806.36 in net transaction revenue.
- November 2011 recorded the highest observed transaction volume.
- November 2011 also recorded the highest observed revenue.
- The top 10% of identified customers accounted for 60.01% of customer revenue.
- Product transaction frequency and total revenue showed a correlation of approximately 0.67.

## Project Structure

```text
Week2_Online_Retail/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── Week2_EDA.ipynb
│
├── report/
│
├── Screenshots/
│
└── visualizations/