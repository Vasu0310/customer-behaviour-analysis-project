# customer-behaviour-analysis-project
Data Analytics project showcasing customer behaviour analysis using python, my sql and power bi.
🛒 Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover insights into:

Customer spending patterns
Product preferences
Customer segmentation
Subscription behavior

These insights help drive data-driven business decisions and strategic recommendations.

📊 Dataset Summary
Total Records: 3,900
Total Features: 18
Key Data Categories:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Item, Category, Amount, Season, Size, Color)
Behavioral data (Discounts, Purchase Frequency, Ratings, Shipping Type)
Data Quality:
Missing values: 37 (Review Rating column)
Handled using median imputation per product category
🧠 Project Workflow
1️⃣ Data Cleaning & Preprocessing (Python)
Data loading using pandas
Null value handling (median imputation)
Column standardization (snake_case)
Feature engineering:
Age groups
Purchase frequency
Removed redundant columns (promo_code_used)

Loaded cleaned data into MySQL database
2️⃣ Data Analysis (MySQL)

Key business questions answered:

Revenue analysis by gender
High-spending customers using discounts
Top-rated products
Shipping type impact on spending
Subscriber vs non-subscriber behavior
Discount dependency of products
Customer segmentation (New / Returning / Loyal)
Top products per category
Repeat buyers vs subscription trends
Revenue contribution by age group

📊 Power BI Dashboard

An interactive dashboard was developed using Power BI to visualize key insights and enable business decision-making.

🔑 Key Metrics
Total Customers: 3.9K
Average Purchase Amount: $59.76
Average Review Rating: 3.75
📈 Dashboard Features
Revenue analysis by category
Sales distribution by age group
Subscription vs non-subscription insights
Shipping type comparison
Interactive filters (Category, Gender, Subscription Status, Shipping Type)

📌 The dashboard enables stakeholders to quickly explore patterns and trends without writing queries.

📈 Key Insights
Loyal customers form the largest segment
Discount usage does not necessarily reduce spending
Some products are highly discount-dependent
Young adults contribute the highest revenue
Subscription users show similar spending patterns to non-subscribers

💡 Business Recommendations
🎯 Boost subscriptions with exclusive benefits
🔁 Implement loyalty programs for repeat customers
💸 Optimize discount strategies to maintain profitability
🛍️ Promote top-performing products
📊 Target high-revenue customer segments

🛠️ Tech Stack
Python (Pandas, NumPy)
MySQL (Data Analysis)
Power BI (Data Visualization & Dashboarding)
Jupyter Notebook
