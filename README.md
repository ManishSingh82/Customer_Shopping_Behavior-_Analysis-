# Customer_Shopping_Behavior-_Analysis-


📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
The objective is to uncover insights into spending patterns, discount dependency, customer segmentation, and subscription behavior to support data-driven business decisions.

🎯 Business Objectives

Identify high-value customer segments

Analyze the impact of discounts on purchasing behavior

Compare subscriber vs non-subscriber spending

Evaluate product performance and ratings

Support strategic decisions using data visualization

🗂 Dataset Summary

Rows: 3,900

Columns: 18

Key Features

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior: Discount Applied, Previous Purchases, Review Rating, Shipping Type

Data Quality

Missing values: 37 records in review_rating

Handled using median imputation by product category

🛠 Tools & Technologies

Python: Pandas, NumPy (EDA & preprocessing)

SQL: MySQL (business analysis queries)

Power BI: Interactive dashboard & insights

Jupyter Notebook: Data exploration & ETL

🔧 Data Preparation & Feature Engineering

Standardized column names using snake_case

Imputed missing review ratings using category-wise median

Created new features:

age_group

purchase_frequency_days

Removed redundant fields after consistency checks

Loaded cleaned data into SQL database for analysis

📊 SQL Analysis Performed

Key business questions answered using SQL:

Revenue comparison by gender

Top 5 products by average customer rating

Average purchase amount by shipping type

Subscriber vs non-subscriber spending analysis

Discount-dependent products identification

Customer segmentation (New, Returning, Loyal)

Top 3 products per category

Repeat buyers vs subscription likelihood

Revenue contribution by age group

📈 Power BI Dashboard

An interactive dashboard was built to visualize:

Revenue and spending trends

Customer segmentation

Discount impact on products

Product ratings and performance

Subscription-based revenue comparison

📌 Dashboard includes slicers for category, age group, and subscription status.
Dashboard:

<img width="1340" height="751" alt="Customer_Behavior Dashboard" src="https://github.com/user-attachments/assets/0c5a310a-8439-4e19-b5a0-83f5f21b84df" />


💡 Key Insights

Subscribers generate higher average revenue per customer

Loyal customers contribute disproportionately to total revenue

Certain products are highly dependent on discounts

Express shipping users tend to have higher purchase values

🚀 Business Recommendations

Promote subscription plans with exclusive benefits

Introduce loyalty programs for repeat buyers

Reevaluate discount strategies for margin-sensitive products

Focus marketing efforts on high-revenue age groups

Upsell express shipping for high-intent customers

📬 Author

Manish Singh

Data Analyst | Mis Excutive.
