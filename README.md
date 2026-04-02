# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases across multiple product categories**. The goal is to uncover insights into:

- Customer spending patterns  
- Product preferences  
- Customer segmentation  
- Subscription behavior  

These insights help drive **data-driven business decisions** and strategic recommendations.

---

## 📊 Dataset Summary

- **Total Records:** 3,900  
- **Total Features:** 18  

### Key Data Categories:
- Customer demographics (Age, Gender, Location, Subscription Status)
- Purchase details (Item, Category, Amount, Season, Size, Color)
- Behavioral data (Discounts, Purchase Frequency, Ratings, Shipping Type)

### Data Quality:
- Missing values: 37 (Review Rating column)  
- Handled using median imputation  

---

## 🧠 Project Workflow

### 1️⃣ Data Cleaning & Preprocessing (Python)
- Data loading using `pandas`
- Null value handling (median imputation)
- Column standardization (snake_case)
- Feature engineering:
  - Age groups
  - Purchase frequency
- Removed redundant column (`promo_code_used`)
- Loaded cleaned data into **MySQL**

---

### 2️⃣ Data Analysis (MySQL)

Key business questions answered:

- Revenue analysis by gender  
- High-spending discount users  
- Top-rated products  
- Shipping type comparison  
- Subscribers vs non-subscribers  
- Discount-dependent products  
- Customer segmentation  
- Top products per category  
- Repeat buyers vs subscriptions  
- Revenue by age group  

---

## 📊 Power BI Dashboard

An interactive dashboard was built in **Power BI** to visualize insights.

### Key Metrics:
- Total Customers: **3.9K**
- Average Purchase Amount: **$59.76**
- Average Review Rating: **3.75**

### Dashboard Features:
- Revenue by category  
- Sales by age group  
- Subscription distribution  
- Shipping comparison  
- Interactive filters  

---

## 📈 Key Insights

- Loyal customers form the largest segment  
- Discount usage does not reduce spending significantly  
- Some products are highly discount-dependent  
- Young adults contribute the highest revenue  
- Subscription users have similar spending patterns  

---

## 💡 Business Recommendations

- Boost subscriptions with exclusive benefits  
- Strengthen loyalty programs  
- Optimize discount strategies  
- Promote top-performing products  
- Target high-value customer segments  

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy)  
- MySQL  
- Power BI  
- Jupyter Notebook  

---



