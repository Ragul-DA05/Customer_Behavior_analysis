# Customer Behavior Data Analytics Project

## Overview
This project analyzes customer shopping behavior to generate meaningful business insights. It covers the complete data analytics workflow including data loading, cleaning, exploratory data analysis (EDA), SQL querying, and building an interactive Power BI dashboard.

## Dataset
The dataset includes:
- Customer details: Age, Gender, Location
- Product details: Category, Item Purchased
- Purchase data: Purchase Amount, Frequency of Purchases
- Marketing data: Discount Applied, Promo Code Used
- Feedback: Review Rating

## Tools & Technologies
- Python (Pandas, NumPy, Matplotlib) – Data analysis and EDA
- MySQL – Data querying and analysis
- Power BI – Dashboard creation
- Excel – Initial data review
- Gamma – Presentation creation

## Project Steps

1. Data Loading (Python)
- Loaded dataset using Pandas
- Checked structure and data types

2. Data Cleaning
- Handled missing values
- Removed duplicates
- Converted data types

3. Exploratory Data Analysis (EDA)
- Analyzed sales distribution
- Identified trends by category, gender, and age
- Studied customer behavior patterns

4. SQL Analysis (MySQL)
- Performed queries such as:
  - Total sales by category
  - Customer segmentation
  - Repeat vs new customers
- Used GROUP BY, JOIN, and aggregation functions

5. Power BI Dashboard
- Built interactive dashboard with:
  - KPI Cards (Total Sales, Customers, AOV, Rating)
  - Sales by Category and Gender
  - Customer segmentation (Age, Subscription)
  - Sales trend analysis (Season)
  - Discount impact analysis

6. Report & Presentation
- Documented insights
- Created presentation using Gamma

## Dashboard Highlights
- Category-wise sales performance
- Gender-based purchasing behavior
- Customer segmentation by age group
- Seasonal sales trends
- Discount impact on revenue

## Key Insights
- Clothing category generated the highest revenue
- Repeat customers contributed more to total sales
- Discounts influenced customer purchases
- Seasonal trends affected sales performance
- Young adults were the most active customers

## How to Run

Python:
pip install pandas numpy matplotlib
python analysis.py

MySQL:
- Import dataset into MySQL
- Run queries from queries.sql

Power BI:
- Open the .pbix file
- Refresh data if needed

## Conclusion
This project demonstrates end-to-end data analytics skills including data cleaning, SQL analysis, dashboard creation, and business insight generation.
