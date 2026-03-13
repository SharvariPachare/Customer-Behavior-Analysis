# Customer-Behavior-Analysis
🛍️ Customer Shopping Behavior Analysis
📌 Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.

The goal was to understand revenue patterns, customer segmentation, product performance, and subscription behavior to support better business decisions.

The project was developed using Python, MySQL, and Power BI.

🛠️ Tools & Technologies

Python (Pandas)

MySQL

Power BI

📊 Dataset Summary

Records: 3,900

Features: 18

The dataset includes customer demographics, purchase details, and behavioral attributes such as discount usage, review ratings, shipping type, and subscription status.

🧹 Data Cleaning

37 missing values were found in the Review Rating column.

Missing values were filled using category-wise median.

Redundant column (promo_code_used) was removed.

🔧 Feature Engineering

New features created:

age_group

purchase_frequency_days

🧮 SQL Analysis

The following business questions were explored:

Revenue comparison by gender

Subscriber vs non-subscriber revenue

High-spending customers

Top-rated products

Revenue contribution by age group

Category-wise top products

Shipping type impact

Customer segmentation (New, Returning, Loyal)

Discount usage patterns

📈 Dashboard

An interactive Power BI dashboard was created to visualize:

Revenue trends

Customer segments

Product performance

Category analysis

Subscription impact

🔍 Key Insights

Revenue varies across customer segments

Subscription status influences purchasing behavior

Certain age groups contribute significantly to revenue

Discount strategies impact product performance

Top-rated products align with high sales categories

💡 Business Impact

The analysis supports:

Improved subscription strategies

Better customer loyalty programs

Optimized discount policies

Targeted marketing decisions

Enhanced product positioning

🔄 Project Workflow

Data Cleaning → Feature Engineering → SQL Analysis → Dashboard → Business Insights
