
This repository contains the first task for the DevLab Data Analyst Internship. The project focuses on data loading, data cleaning, initial exploration, and business insight generation using Python (Pandas) and Matplotlib.

## 📌 Project Overview
The objective of this task is to analyze historical retail sales data, clean inconsistencies, handle missing values, and visualize key trends to derive actionable business insights.

## 🛠️ Technologies Used
* **Python** (Data Processing)
* **Pandas** (Data Manipulation & Cleaning)
* **Matplotlib / Pyplot** (Data Visualization)
* **Jupyter Notebook** (Development Environment)

## 🧼 Data Cleaning & Preprocessing
* Checked data types and structure (`df.info()`, `df.describe()`).
* Converted date column into standardized datetime format.
* Handled missing/null values in key columns to prevent analysis bias.
* Detected and removed duplicate entries to ensure data integrity.

## 📊 Key Business Insights & Visualizations

### 1. Delivery Status Trends (Sifariş Statusları)
* **Insight:** Over **50% of orders** are consistently in a *Shipped* status, which proves that the logistical pipeline is highly stable. 
* **Visualization:** A customized bar chart displaying the exact count for each shipping status category.

### 2. Peak Order Years (İllərə Görə Sifariş Sayı)
* **Insight:** There is a massive spike in orders during **2004**, reaching **1,351 total orders**, which is nearly a **35% jump** from 2003. This indicates a highly successful marketing campaign or rapid market expansion during that year.
* **Visualization:** A salmon-colored bar chart mapping out order distributions across 2003, 2004, and 2005.

