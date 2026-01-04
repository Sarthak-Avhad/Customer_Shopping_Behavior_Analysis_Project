🛒 Customer Shopping Behavior Analysis

A complete end-to-end Data Analytics project that studies customer shopping patterns across demographics, product categories, and purchase channels to help a retail company improve revenue, customer engagement, and loyalty.
The project integrates Python for data preparation, SQL for business analysis, and Power BI for visualization.

📌 Business Problem

A leading retail company observed changing purchasing trends across customer segments and sales channels.
They want to understand:

How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies? 

Business Problem Document

🎯 Project Objectives

Identify key factors driving customer purchases.

Segment customers based on behavior and loyalty.

Analyze discount dependency and subscription patterns.

Provide business recommendations backed by data insights.

📂 Repository Structure
📁 Customer-Shopping-Behavior-Analysis
│
├── 📁 python/
│   └── data_preprocessing.ipynb
│
├── 📁 sql/
│   └── customer_analysis_queries.sql
│
├── 📁 powerbi/
│   └── shopping_behavior_dashboard.pbix
│
├── 📁 reports/
│   ├── Business Problem Document.pdf
│   └── Customer Shopping Behavior Analysis.pdf
│
└── README.md

📊 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer Demographics – Age, Gender, Location, Subscription Status

Purchase Details – Item Purchased, Category, Amount, Season, Size, Color

Shopping Behavior – Discounts, Reviews, Shipping Type, Purchase Frequency

Missing Values: 37 missing values in Review Rating column 

Customer Shopping Behavior Anal…

🐍 Data Preparation & Feature Engineering (Python)

Loaded dataset using pandas.

Performed initial exploration using .info() and .describe().

Handled missing values in review_rating using median rating per category.

Standardized column names using snake_case.

Created new features:

age_group

purchase_frequency_days

Removed redundant column promo_code_used.

Loaded cleaned data into PostgreSQL for SQL analysis. 

Customer Shopping Behavior Anal…

🗄️ Data Analysis (SQL – PostgreSQL)

Business insights extracted:

Revenue comparison by gender

High-spending customers who still use discounts

Top 5 products by average rating

Shipping type vs. average purchase amount

Subscribers vs. non-subscribers revenue

Most discount-dependent products

Customer segmentation – New, Returning, Loyal

Top 3 products in each category

Repeat buyers vs subscription likelihood

Revenue contribution by age group 

Customer Shopping Behavior Anal…

📈 Dashboard (Power BI)

An interactive Power BI dashboard showing:

Revenue distribution by age group & gender

Discount & subscription impact on revenue

Top-selling & top-rated products

Customer loyalty segments

Shipping behavior trends

💡 Business Recommendations

Boost Subscriptions: Promote exclusive benefits to non-subscribers.

Customer Loyalty Programs: Convert returning buyers into loyal customers.

Review Discount Strategy: Balance discount-driven sales with profit margins.

Product Positioning: Highlight top-rated & best-selling products.

Targeted Marketing: Focus on high-revenue age groups and express-shipping users. 

Customer Shopping Behavior Anal…

🛠️ Tools & Technologies

Python (pandas, numpy)

PostgreSQL (SQL)

Power BI

Jupyter Notebook
