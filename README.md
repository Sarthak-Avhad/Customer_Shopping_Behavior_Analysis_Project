# 🛒 Customer Shopping Behavior Analysis – End-to-End Data Analytics Project

## 📌 Business Problem Statement

A leading retail company wants to better understand its customers’ shopping behavior to improve sales, customer satisfaction, and long-term loyalty. The management observed changing purchasing patterns across demographics, product categories, and sales channels (online vs offline).  

The main business question addressed in this project is:

**“How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?”**

---

## 🎯 Project Objectives

- Analyze customer shopping behavior using transactional data.
- Identify key drivers such as discounts, reviews, seasons, and payment preferences.
- Segment customers to understand loyalty and repeat purchase behavior.
- Provide business recommendations using data-driven insights.

---

## 📂 Dataset Summary

- Total Records: **3,900**
- Total Columns: **18**
- Key Features:
  - Customer Demographics: `age`, `gender`, `location`, `subscription_status`
  - Purchase Details: `item_purchased`, `category`, `purchase_amount`, `season`, `size`, `color`
  - Shopping Behavior: `discount_applied`, `promo_code_used`, `previous_purchases`,  
    `frequency_of_purchases`, `review_rating`, `shipping_type`
- Missing Values:
  - `review_rating` column had **37 missing values**.

---

## 🛠️ Tools & Technologies Used

- **Python** – Data Cleaning, EDA, Feature Engineering  
- **PostgreSQL** – SQL Analysis & Business Transactions  
- **Power BI** – Interactive Dashboard & Visualization  
- **Jupyter Notebook**, **pandas**, **NumPy**, **SQL**, **Power BI Desktop**

---

## 🔹 Step 1: Data Preparation & Modeling (Python)

- Loaded dataset using pandas.
- Performed data exploration using `df.info()` and `df.describe()`.
- Handled missing values in `review_rating` using **median of each product category**.
- Renamed columns into **snake_case**.
- Feature Engineering:
  - Created `age_group` column using binning.
  - Created `purchase_frequency_days`.
- Removed redundant column `promo_code_used`.
- Connected Python with PostgreSQL and loaded cleaned dataset.

---

## 🔹 Step 2: Data Analysis (SQL)

Key Business Queries Executed:

1. Revenue by Gender  
2. High-Spending Discount Users  
3. Top 5 Products by Rating  
4. Shipping Type vs Average Spend  
5. Subscribers vs Non-Subscribers Revenue  
6. Discount-Dependent Products  
7. Customer Segmentation – New, Returning, Loyal  
8. Top 3 Products per Category  
9. Repeat Buyers vs Subscription Status  
10. Revenue Contribution by Age Group  

---

## 🔹 Step 3: Dashboard in Power BI

An interactive Power BI dashboard was built to show:

- Revenue trends  
- Customer segmentation  
- Product performance  
- Shipping & subscription behavior  
- Discount usage impact  

This enables management to take **data-driven decisions**.

---

## 💡 Business Recommendations

- 🎯 Promote **subscription benefits** to increase customer lifetime value.  
- 🏆 Introduce **loyalty programs** for repeat buyers.  
- ⚖️ Review discount strategy to balance profit margins.  
- 📦 Highlight **top-rated & best-selling products** in marketing campaigns.  
- 📈 Focus marketing on **high-revenue age groups** and **express shipping users**.

---






