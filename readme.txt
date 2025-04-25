# 🛒 Supermarket Sales Data Pipeline & Analysis

This project provides a comprehensive Python-based pipeline for analyzing and visualizing sales data from a supermarket.  
It includes time-based aggregations, product category evaluations, gender-based comparisons, and city-level sales breakdowns — all powered by pandas and seaborn.

## 📊 Features

- 📈 **Weekly Sales Analysis** using ISO calendar weeks (Monday–Sunday)
- 🏷️ **Category-Level Rating Averages**
- 👨‍👩‍👧‍👦 **Gender-Based Purchase Breakdown** (stacked bar chart)
- ⏰ **Hourly Sales Trends** and purchase volume distribution
- 💳 **Total Sales by Payment Method**
- 🧠 **Strategic vs. Non-Strategic Product Filtering** using external CSV
- 🌆 **City-Level Sales Summary** for non-strategic products


## 📂 Files

- `supermarket_sales_data_pipeline.py` – The main Python script for processing and analyzing the data.
- `supermarket_sales.csv` – The primary dataset containing transactional records.
- `product_types_strategy.csv` – A supplemental file marking each product line as strategic or non-strategic.


## 🧪 Sample Visuals

The script produces:
- Bar charts for weekly sales by category
- Stacked bar charts split by gender
- Line charts for hourly sales and transaction volume


## 🧰 Technologies Used

- **Python 3**
- **pandas**
- **matplotlib**
- **seaborn**
