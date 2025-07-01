# DmartAnalysis

Retail Data Deep Dive: Customer, Sales & Marketing Analysis

Overview
This project presents a comprehensive end-to-end data analysis of a retail e-commerce dataset, inspired by D-Mart’s business model. The goal is to extract actionable insights from customer, sales, product, payment, and marketing data using Python and popular data science libraries. The analysis covers data cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, visualization, and business recommendations.



Project Objectives
Clean and preprocess raw retail transaction data for robust analysis.

Explore and visualize customer demographics, sales trends, product performance, payment patterns, and marketing effectiveness.

Segment customers using RFM (Recency, Frequency, Monetary) analysis.

Identify actionable business insights to drive customer retention, sales growth, and marketing ROI.

Dataset
Source: Synthetic/Anonymized D-Mart e-commerce data (dmart.csv)

Size: 25000 rows, 29 columns

Features:

Customer demographics (ID, age, gender, city, subscription)

Order details (order ID, date, status, value, shipping charges)

Product info (name, category, MRP, discount)

Payment method

Marketing channel

Engagement metrics (time on site, clicks)

Key Questions & Insights
What are the most profitable customer segments?

How do sales and order trends vary by time, city, and product?

Which products and categories drive the most revenue?

How do payment methods and subscription status affect sales?

Which marketing channels yield the best ROI?

What customer behaviors signal high intent or loyalty?

Methodology
Data Cleaning & Preprocessing
Standardized column names and formats
Missing value checks
Converted date fields to datetime
Created new features (age group, RFM scores, discount %)
Exploratory Data Analysis (EDA)
Visualized distributions and trends
Grouped and aggregated key metrics
Correlation and segmentation analysis
Business Insights & Recommendations
Interpreted findings in a business context
Suggested actionable strategies

Key Findings
Balanced Gender Mix: Male and female customers are nearly equal, supporting gender-neutral campaigns.
Top Spending Age Groups: 30–45-year-olds drive the majority of high-value purchases.
Loyalty Drives Revenue: Top 20% of customers contribute over 35% of revenue.
Sales Peaks: December, May, and August are high-volume months, likely due to seasonality and promotions.
Tier-1 City Dominance: Mumbai, Hyderabad, and other metros account for ~60% of sales.
Product Insights: Branded and imported products dominate high-value orders; local products see lower spend.
Payment Patterns: Credit and debit cards account for 80% of payments; digital buyers spend more per order.
Marketing ROI: Social/email campaigns yield higher site engagement and conversion than display ads.
Engagement Matters: More clicks and time on site correlate with higher order value.

Project Structure
text
retail-data-deep-dive/
│
├── data/
│   └── dmart.csv               # (Dataset)
├── retail_eda_analysis.py      # Main analysis script
├── Retail_EDA_Notebook.ipynb   # Jupyter notebook version (optional)
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation
└── images/                     # Visualizations and plots

Technologies Used
Python 3.x
Pandas (data cleaning, analysis)
NumPy (numerical operations)
Matplotlib & Seaborn (visualization)
Jupyter Notebook (optional, for interactive analysis)

Business Recommendations
Target high-value and loyal customers with exclusive offers and retention programs.
Focus marketing spend on peak sales months and Tier-1 cities for maximum ROI.
Bundle top repeat products and branded items to increase basket size.
Optimize pricing and discount strategy for imported and high-MRP products.
Promote digital payments and subscriptions for higher order values.
Refine marketing channels by investing more in social/email and A/B testing underperforming sources.

Sample Visualizations

Customer Age Group Spend Distribution

Monthly Sales Trends

RFM Customer Segmentation Heatmap

Top Products by Repeat Orders

Payment Method vs. Average Order Value

Contact
Author: Nilakshi Gogoi
LinkedIn: https://www.linkedin.com/in/nilakshi-gogoi-9b1ba211a/
Email: gogoi.nilakshi@gmail.com

Feel free to fork, adapt, or reach out for collaboration!
