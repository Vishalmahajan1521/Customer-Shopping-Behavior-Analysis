📊 Customer Shopping Behavior Analysis

A complete data analysis project using Python, MySQL, and Power BI

📌 Overview

This project analyzes customer shopping behavior using a retail dataset containing 3,900 rows and 18 features.
The goal is to uncover insights about customer spending patterns, loyalty, product preferences, discount dependency, and demographic trends to support better business decisions.

🗂️ Project Workflow
1. Data Cleaning & Preprocessing (Python)

Handled missing values (median imputation).

Performed outlier detection and removal.

Standardized column names and data types.

Engineered new features:

age_group

purchase_frequency_days

Validated dataset consistency and removed redundant columns.

2. Exploratory Data Analysis (Python)

Summary statistics and distribution analysis.

Revenue patterns by age, gender, and category.

Correlation analysis for key numerical variables.

Identified discount impact on purchasing behavior.

🛢️ SQL Analysis (MySQL)

The cleaned dataset was loaded into MySQL for structured analysis.
Key queries explored:

Customer Lifetime Value (CLV)

Discount dependency & high-spend discount users

Subscription vs. non-subscription behavior

Repeat purchase patterns

Revenue by age group and gender

Top-rated and top-selling products

Shipping type impact on spending

Customer segmentation: New, Returning, Loyal

📊 Dashboard (Power BI)

An interactive Power BI dashboard was built with:

Revenue trends

Customer segments

Top products by rating & sales

Discount-based buying patterns

Demographic insights

Shipping preference analysis

The dashboard helps stakeholders make data-driven marketing and product decisions.

🧠 Key Insights

High-spend customers frequently use express shipping.

Repeat buyers show higher subscription likelihood.

Specific age groups contribute the highest revenue.

Discounts influence purchase frequency but reduce margins.

Some product categories are highly rating-sensitive.

🛠️ Tech Stack

Languages & Tools:

Python (Pandas, NumPy, Matplotlib, Seaborn)

MySQL

Power BI

Jupyter Notebook
