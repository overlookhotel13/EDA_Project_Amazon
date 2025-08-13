# Amazon Clothing Sales 2025 — EDA Project

This project performs **Exploratory Data Analysis (EDA)** on the Amazon Clothing Sales 2025 dataset, from **Initial Data Exploration & Cleaning** through **Visualization Expectations**.

## Description
The notebook cleans, processes, and analyzes the dataset to identify trends, detect anomalies, and prepare data for potential further analysis.  
No machine learning is used — the focus is on understanding the dataset and generating clear visual insights.

## Features
- Load and inspect raw data
- Handle missing values and incorrect data types
- Remove duplicates and check pricing integrity
- Detect and treat outliers using IQR method
- Merge similar categorical entries using `fuzzywuzzy` (e.g., `'men'` & `'Men'` → `Men`)
- Create new features such as:
  - `order_month`, `order_weekday`, `order_year`
  - `discount_amount`, `unit_price`, `delivery_speed`
  - Customer-level aggregates: total spend, total orders, average rating, return rate
- Save cleaned dataset to CSV
- Perform univariate and bivariate analyses
- Generate Matplotlib visualizations:
  - Monthly revenue trends
  - Category/brand revenue leaders
  - Price vs quantity relationships
  - Discount effectiveness
  - Return rates by category/brand/age group
  - AOV by region and age group
  - Delivery days vs ratings
  - Average ratings by brand/category/region
  - Payment method insights
  - Correlation heatmap of numeric features

## Files
- `Amazon_Clothing_Sales_2025_EDA.ipynb` — The main analysis notebook
- `amazon_clothing_cleaned.csv` — Cleaned dataset
- `requirements.txt` — Python dependencies to run the notebook

## How to Run
1. Clone this project or download all files.
2. Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `Amazon_Clothing_Sales_2025_EDA.ipynb` in Jupyter Notebook or Jupyter Lab.
4. Execute all cells in order.

## Visualization Expectations
The notebook provides clear, labeled visualizations to answer key business questions, such as:
- How do revenues change over time?
- Which categories and brands are most profitable?
- How do discounts impact sales?
- What factors correlate with returns?
- How do regions and customer segments differ in behavior?

---
**Author:** Muhammad Ahmad  
**Date:** 2025
