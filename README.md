# 🛍️ Sterling E-Commerce Data Analysis

Analyzing customer purchasing behavior, product trends, and regional sales performance to provide business insights for Sterling E-Commerce using advanced data analytics and visualization.

# Project Overview

This project presents a comprehensive retail analytics study for Sterling E-Commerce, an online marketplace offering products across multiple categories.
The goal was to uncover consumer trends, top-performing categories, regional buying patterns, and payment preferences using descriptive analytics and visualization.

The dataset included transactional details such as product category, customer demographics, order dates, payment method, quantity purchased, and total sales amount.
Through Exploratory Data Analysis (EDA) and visualization, the analysis provided data-driven recommendations for marketing, customer segmentation, and inventory planning.

# Objectives

Identify best-selling product categories and analyze purchase frequency.

Examine regional and gender-based revenue distribution.

Assess customer segmentation by tenure (new vs loyal vs regular).

Detect monthly and seasonal purchasing trends.

Evaluate preferred payment channels and their impact on conversion.

# Tools, Libraries & Tech Stack

Programming Language: Python

Libraries & Frameworks:

Pandas, NumPy — Data preprocessing and analysis

Matplotlib, Seaborn — Data visualization and trend analysis

Jupyter Notebook — Exploratory analysis environment

Excel — Initial data review and charting

Techniques:
EDA, Data Aggregation, Segmentation Analysis, Visualization, Insight Generation

# Workflow / Steps to Execute
1️⃣ Data Collection

The dataset contained key fields such as Category, Region, Gender, PaymentMethod, QuantityOrdered, TotalSales, and CustomerType.

2️⃣ Data Cleaning & Preparation

Verified data consistency across regions and genders.

Formatted dates and derived monthly and yearly order columns.

Aggregated transactions by category, region, and customer segment.

3️⃣ Exploratory Data Analysis (EDA)

a. Product Category Analysis

Top 5 categories: 

1. Mobiles & Tablets (60,954 orders)

2. Men’s Fashion (40,183

3. Appliances (32,693)

4. Women’s Fashion (28,003)

5. Others (25,913)

These categories contributed most to overall revenue and demand frequency


b. Regional & Gender Sales Distribution

The Southern Region generated the highest sales, followed by Midwest, Northeast, and West.

Gender-based purchasing power was nearly balanced: Female ≈ ₦115.7 M vs Male ≈ ₦115.3 M total revenue


c. Customer Segmentation by Loyalty

Segment	-------------Orders	---------Total Sales (₦)

New Customers	------202,870	---------160,579,320

Regular Customers	----66,398	---------59,679,909

Loyal Customers	------13,810	---------10,801,809

New customers contributed over 70% of total sales, indicating strong acquisition but lower long-term retention


d. Monthly & Seasonal Trends

Orders peaked in December and April, driven by holiday and seasonal sales.

Mobile & Tablet and Appliance categories dominated these months.

e. Payment Method Preference

Easypay was the most preferred payment method nationwide.

Followed by Bank Alfalah, Easypay Voucher, Payaxis, and Cash on Delivery


f. Sales by Quantity & Category

Category	-------------Qty Ordered	----------Total Sales (₦)

Mobiles & Tablets	--------60,954	---------------128.6 M

Appliances	--------------32,693	----------------29.8 M

Entertainment	------------17,120	----------------26.8 M

Computing	-----------------8,025	-----------------9.3 M

Men’s Fashion	------------40,183	-----------------4.7 M

These five categories collectively accounted for over 80% of total revenue


# Results & Key Insights

Metric	-------------------------------------------Observation

Top Product Category	----------------------Mobiles & Tablets (₦128.6 M Sales)

Strongest Region	--------------------------South Region (₦89.6 M)

Gender Trend	------------------------------Minimal difference in male vs female spending

Customer Tenure	----------------------------New customers generated the most sales but need loyalty programs

Peak Months---------------------------------December & April

Preferred Payment	--------------------------Easypay → Bank Alfalah → Easypay Voucher → Payaxis → COD

# Business Recommendations

Loyalty Program Launch:
Introduce points or cash-back schemes for regular and loyal customers to increase repeat purchases.

Seasonal Marketing:
Focus advertising spend and discount campaigns in April and December to capitalize on peak demand.

Regional Optimization:
Strengthen logistics and ad placement in the Southern Region where purchasing power is highest.

Payment Diversification:
Promote Easypay and digital wallet methods while streamlining the checkout experience to reduce abandoned carts.

Product Focus:
Prioritize inventory for high-performing categories like Mobiles, Appliances, and Entertainment.

# Business Impact

Revealed key drivers of sales volume and customer behavior across regions and categories.

Provided marketing and inventory teams with data-driven insights for demand forecasting.

Identified strategic opportunities to increase customer retention and optimize regional campaigns.

Helped management visualize purchase patterns for better decision making.

# Install dependencies
pip install -r requirements.txt

# Open the Jupyter Notebook
jupyter notebook Sterling_Ecommerce_Analysis.ipynb

📁 Folder Structure

Sterling-Ecommerce-Data-Analysis/

│

├── data/

│   └── sterling_ecommerce_sales.csv

│

├── notebooks/

│   ├── EDA.ipynb

│   ├── Category_Analysis.ipynb

│
├── visuals/

│   ├── sales_by_category.png

│   ├── regional_sales.png

│

├── README.md

└── requirements.txt

# Outcome Summary

This project successfully analyzed over 280,000 transactions to uncover key trends in sales performance, regional distribution, and customer behavior for Sterling E-Commerce.
It demonstrates strong skills in data visualization, insight generation, and business communication, bridging the gap between technical analysis and strategic decision-making for e-commerce growth.
