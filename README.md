# 🛍️ Retail Sales Data Analysis with NumPy & Pandas

## 📌 Project Overview

This project involves performing **data cleaning**, **feature engineering**, and **exploratory analysis** on a real-world retail dataset from *ShopSmart*. The goal is to derive actionable insights into sales performance, return behaviors, and profitability across products and regions using Python's NumPy and Pandas libraries.

---

## 🧾 Scenario

You've joined *ShopSmart* as a Data Analyst Intern. Your manager provided a one-year retail dataset and requested an in-depth analysis to assist business decisions in the following areas:

- 🔹 Sales performance (product-wise and region-wise)
- 🔹 Seasonal trends (monthly and weekday patterns)
- 🔹 Customer return behavior
- 🔹 Pricing effectiveness
- 🔹 Profitability insights

---

## ✅ Tasks Performed

### 📂 Part 1: Data Cleaning
- Loaded the dataset using **Pandas**
- Checked and handled **missing/null values**
- Converted column data types (e.g., `Date` to `datetime`)
- Removed **duplicate Order IDs**

### 🔧 Part 2: Feature Engineering
- Created new column `Total_Sale = (Quantity * Unit_Price) * (1 - Discount)`
- Extracted **Month** and **Weekday** from `Date`
- Added a boolean column `Is_Returned` based on return flag

### 📊 Part 3: Exploratory Analysis
- Identified **Top 5 Products** by Total Sales
- Analyzed **Monthly Sales Trends**
- Evaluated **Region-wise** sales, quantity, and discount averages
- Assessed **Revenue Contribution** per Category
- Calculated **Return Rates** per Category/Sub-Category

### 📈 Part 4: Statistical & NumPy Insights
- Computed **Mean**, **Median**, and **Standard Deviation** of `Unit_Price` per Category
- Used **Z-Score** to detect outliers in high discounts
- Calculated **Correlation** between `Quantity` and `Discount`

---

## 📌 Sample Visuals and Output Snapshots

> *(Include screenshots or sample tables of cleaned data, transformed columns, and analysis outputs here if available in your notebook.)*

---

## 🔚 Summary of Key Insights

- **Top Products** significantly outperform others in both units sold and revenue.
- **Seasonality** shows peak sales during select months, indicating promotional opportunities.
- **Regions** differ in sales and return behavior — some need logistic or quality improvement.
- **High discounts** correlate with **higher return rates**, suggesting pricing strategy review.
- **Outlier transactions** were detected using statistical methods (Z-Score).
- **Category A** showed the **highest return rate**, likely due to sizing or product expectation mismatches.

---

## 💡 Bonus Thought Answers

1. **Highest Return Rate Product**: Likely due to quality or mismatched expectations.
2. **Regional Return Behavior**: Certain regions had consistently high return ratios — service or product fit issues?
3. **Discount Strategy**: High discounts should be cautiously applied in categories with poor retention metrics.

---

## 🔧 Tools Used

- 🐍 **Python**
- 📦 **Pandas**, **NumPy**
- 📊 *(Optional)*: **Matplotlib**, **Seaborn** for visualizations
- 📓 Jupyter Notebook / .py Script

---

## 👤 Author

**Your Name**  
Data Analyst Intern | Python Enthusiast

---

