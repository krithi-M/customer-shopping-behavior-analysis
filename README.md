# Customer Shopping Behavior Analysis 📊

## Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases.
The goal is to understand customer spending patterns, product performance, discount usage,
and subscription behavior to support data-driven business decisions.

The project uses **Python**, **SQL**, and **Power BI** for end-to-end data analysis and visualization.

---

## Dataset
- Total Records: 3,900
- Total Columns: 18
- Data Type: Customer transactional data

### Key Information
- Customer details: Age, Gender, Location, Subscription Status
- Purchase details: Item, Category, Amount, Season, Size, Color
- Shopping behavior: Discounts, Promo Codes, Review Ratings, Shipping Type

📁 File: `data/raw_customer_shopping_data.csv`

---

## Python Analysis (Jupyter Notebook)
Python was used for data cleaning and feature engineering.

### Key Tasks:
- Loaded and explored the dataset
- Handled missing values in the Review Rating column
- Standardized column names
- Created new features such as age groups and purchase frequency
- Prepared cleaned data for SQL analysis

📁 File: `notebooks/customer_shopping_analysis.ipynb`

---

## SQL Analysis
SQL queries were written to answer important business questions, including:
- Revenue by gender
- High-spending customers using discounts
- Top-rated products
- Shipping type comparison
- Subscriber vs non-subscriber behavior
- Discount-dependent products
- Customer segmentation (New, Returning, Loyal)
- Revenue contribution by age group

📁 File: `sql/customer_shopping_analysis.sql`

---

## Power BI Dashboard
An interactive Power BI dashboard was created to visualize:
- Revenue trends
- Customer segmentation
- Product category performance
- Subscription impact on revenue

📁 File: `powerbi/customer_shopping_dashboard.pbix`

### Dashboard Preview
![Dashboard Preview]((https://github.com/krithi-M/customer-shopping-behavior-analysis/blob/main/powerbi/screenshots/Dashboard.png))

---

## Reports
- Customer Shopping Behavior Analysis Report
- Project Presentation (Executive Summary)

📁 Folder: `reports/`

---

## Tools & Technologies
- Python (Pandas, NumPy)
- SQL (MySQL)
- Power BI
- Jupyter Notebook
- CSV and PDF files

---

## Key Insights
- Male customers generated higher total revenue than female customers
- Non-subscribers contributed more revenue, while subscribers showed higher loyalty
- Certain products were highly dependent on discounts
- Express shipping showed slightly higher average purchase values
- Loyal customers formed the largest customer segment

---

## Repository Structure
