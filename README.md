# DmartAnalysis

Retail Data Deep Dive: Customer, Sales & Marketing Analysis

Full youtube link: https://youtu.be/jRBbW9-EsNU?si=qimseLJfCCY4q-pn

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


Contact
Author: Nilakshi Gogoi
LinkedIn: https://www.linkedin.com/in/nilakshi-gogoi-9b1ba211a/
Email: gogoi.nilakshi@gmail.com

Feel free to fork, adapt, or reach out for collaboration!
