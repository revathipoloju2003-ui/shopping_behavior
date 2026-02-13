# 🛍️ Customer Shopping Behavior Analysis Dashboard

## 📌 Project Overview

This project analyzes customer shopping behavior using Power BI.\
The objective is to understand customer demographics, purchasing
patterns, payment preferences, and shipping behavior through interactive
dashboards.

The dataset contains customer details, product information, purchase
amount, payment methods, and review ratings.

------------------------------------------------------------------------

## 🎯 Project Objectives

-   Analyze total revenue and transactions
-   Identify customer demographics (Age, Gender, Location)
-   Understand product category performance
-   Analyze payment and shipping preferences
-   Measure customer satisfaction using review ratings

------------------------------------------------------------------------

## 📊 Dashboards Created

### 🔹 Dashboard 1: Customer Overview

**KPIs:** - Total Customers - Total Transactions - Total Revenue -
Average Age - Average Review Rating

**Visuals:** - Gender Distribution (Bar Chart) - Item Purchased
Distribution (Bar Chart) - Customers by Location (Map) - Category Wise
Purchases

------------------------------------------------------------------------

### 🔹 Dashboard 2: Purchasing Insights

**KPIs:** - Total Revenue - Total Transactions - Average Order Value -
Unique Customers

**Visuals:** - Revenue by Category - Payment Method Distribution - Age
Group vs Review Rating - Sales Trend Analysis

------------------------------------------------------------------------

### 🔹 Dashboard 3: Shipping & Customer Experience

**KPIs:** - Total Orders - Average Review Rating - % Express Shipping
Users

**Visuals:** - Shipping Type Distribution - Purchase Amount by Shipping
Type - Review Rating by Season - Frequency of Purchases

------------------------------------------------------------------------

## 🧮 Key DAX Measures Used

Total Revenue = SUM(Purchase Amount (USD))

Total Transactions = COUNTROWS(Table)

Total Customers = DISTINCTCOUNT(Customer ID)

Average Age = AVERAGE(Age)

Average Review Rating = AVERAGE(Review Rating)

Average Order Value = DIVIDE(Total Revenue, Total Transactions)

------------------------------------------------------------------------

## 🛠 Tools & Technologies Used

-   Power BI
-   DAX
-   Excel / CSV Dataset
-   GitHub

------------------------------------------------------------------------

## 📂 Dataset Columns Used

-   Customer ID
-   Age
-   Gender
-   Item Purchased
-   Category
-   Purchase Amount (USD)
-   Location
-   Season
-   Review Rating
-   Subscription Status
-   Shipping Type
-   Payment Method
-   Frequency of Purchases

------------------------------------------------------------------------

## 📈 Insights Generated

-   Identified most purchased items
-   Analyzed revenue contribution by category
-   Compared male vs female shopping behavior
-   Measured customer satisfaction through ratings
-   Evaluated preferred payment and shipping methods

------------------------------------------------------------------------

## 🚀 Conclusion

This project demonstrates the ability to clean and analyze customer
data, create interactive dashboards, use DAX measures effectively, and
present business insights visually.
