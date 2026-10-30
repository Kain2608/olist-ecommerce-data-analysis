# Brazilian E-Commerce Data Analysis – Olist

## Project Overview

This project analyzes the Brazilian E-Commerce Public Dataset by Olist to explore sales performance, product categories, customer behavior, payment methods, delivery performance, and customer reviews.

The project follows a data analytics workflow, including data understanding, data cleaning, exploratory data analysis (EDA), SQL analysis, and business insights.

## Dataset

- **Source:** [Brazilian E-Commerce Public Dataset by Olist – Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Period:** 2016–2018
- **Tables:** 9 CSV datasets
- **Domain:** E-commerce

The dataset contains information about customers, orders, products, sellers, payments, reviews, and geolocation.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
olist-ecommerce-data-analysis/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   └── 03_eda.ipynb
├── reports/
├── images/
├── .gitignore
├── requirements.txt
└── README.md
```

## Project Progress

### 1. Data Understanding

- Inspected the structure of all 9 datasets.
- Examined data types and missing values.
- Identified duplicate records.
- Investigated categorical values and potential primary/foreign keys.

### 2. Data Cleaning

- Investigated missing values and selected appropriate handling strategies.
- Removed exact duplicate records from the geolocation dataset.
- Converted timestamp columns into datetime format.
- Developed data validation checks.
- Saved processed datasets locally.

### 3. Exploratory Data Analysis – In Progress

**Sales Analysis**

- Analyzed monthly product revenue.
- Identified monthly revenue trends.

**Product Analysis**

- Analyzed revenue by product category.
- Identified the top 10 product categories by revenue.

### Upcoming Tasks

- Customer Analysis
- Payment Analysis
- Delivery Analysis
- Review Analysis
- SQL Analysis
- Business Insights
- Machine Learning
- Power BI Dashboard

## Key Findings So Far

- November 2017 recorded the highest monthly product revenue in the current analysis, at approximately BRL 1.01 million.
- Health & Beauty was the highest-revenue category among the top 10 categories, generating approximately BRL 1.26 million.
- Bed, Bath & Table recorded the highest number of product-item rows among the top 10 categories.

## Author

Data Analytics Portfolio Project
