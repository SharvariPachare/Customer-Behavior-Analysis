# Customer-Behavior-Analysis
🛍️ Customer Shopping Behavior Analysis
📌 Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The objective was to uncover insights related to:

Revenue patterns

Customer segmentation

Product performance

Subscription behavior

The project follows an end-to-end workflow using Python, PostgreSQL, and Power BI for data preparation, analysis, and visualization.

🛠️ Tech Stack

Python – Data cleaning & feature engineering

MySQL – Business analysis using SQL

Power BI – Interactive dashboard & visualization

📊 Dataset Summary

Total Records: 3,900

Total Features: 18

Key Categories

Customer Information

Age

Gender

Location

Subscription Status

Purchase Details

Item Purchased

Category

Purchase Amount

Season

Size

Color

Behavioral Data

Discount Applied

Promo Code Used

Previous Purchases

Frequency of Purchases

Review Rating

Shipping Type

Data Cleaning Note

37 missing values were present in the Review Rating column.

🔄 Data Preparation

Performed using Python (Pandas):

Explored dataset structure and summary statistics

Handled missing values (filled review ratings using category-wise median)

Standardized column names to snake_case

Removed redundant column (promo_code_used)

Created new features:

age_group

purchase_frequency_days

The cleaned dataset was then imported into PostgreSQL for analysis.

🧮 SQL Analysis

Business questions answered using SQL:

Revenue comparison by gender

Subscription vs non-subscription revenue analysis

High-spending customers using discounts

Top products based on average rating

Revenue contribution by age group

Category-wise top-selling products

Shipping type impact on purchase amount

Customer segmentation (New, Returning, Loyal)

Discount usage patterns

📈 Power BI Dashboard

An interactive dashboard was created to visualize insights, including:

Key performance indicators (KPIs)

Revenue breakdown by gender

Category performance analysis

Customer segmentation

Subscription impact on revenue

Product performance insights

💡 Key Insights

Clear revenue differences across customer segments

Subscription status influences purchasing behavior

Certain age groups contribute significantly to revenue

Discount strategy impacts product performance

Top-rated products align with high sales categories

📌 Business Recommendations

Encourage subscriptions through exclusive benefits

Introduce loyalty programs for repeat customers

Optimize discount strategies for better profit balance

Promote high-rated and best-selling products

Target marketing toward high-revenue age groups

🎯 Project Outcome

This project demonstrates an end-to-end data analysis workflow:

Data Cleaning → Feature Engineering → SQL Analysis → Dashboard Visualization → Business Insights

It highlights practical skills in data handling, querying, and building business-focused dashboards.
