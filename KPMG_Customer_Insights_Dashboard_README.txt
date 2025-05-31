
📊 KPMG Customer Insights Dashboard

Overview
--------

This project presents a comprehensive customer insights dashboard developed as part of the KPMG Virtual Internship. The data visualization was created using Power BI, based on the provided dataset (full_data.csv) by KPMG.

The dashboard delivers key business intelligence insights into customer demographics, transaction behavior, and regional performance to assist in strategic decision-making.

Objective
---------

The goal of this project is to analyze and visualize:
- Customer age and gender distribution
- Top-selling product classes
- Online vs in-store purchasing patterns
- Total sales by region
- Customer segments based on wealth and location

Dataset Breakdown
-----------------

The original full_data.csv was split into the following logical datasets for clarity and visualization:
1. CustomerDemographic.csv
2. CustomerAddress.csv
3. CustomerTransactions.csv

These subsets were created based on field relevance:
- Demographics: Age, Gender, Wealth Segment, DOB
- Address: Region, State, Postcode
- Transactions: Transaction Date, Channel, Product Class, Brand

Key Visuals in Dashboard
------------------------

👥 Age & Gender Distribution
- Chart: Histogram and Bar Chart
- Insight: Understand the age spread and gender breakdown of customers.

🛍️ Top Selling Products
- Chart: Bar Chart
- Fields Used: Product Class or Brand vs Count of Transactions
- Insight: Identify high-performing product lines.

🌐 Online vs In-store Purchases
- Chart: Donut Chart
- Fields Used: Online Order (Yes/No) vs Count of Transactions
- Insight: Track consumer preference for online or in-store channels.

🌎 Total Sales by Region
- Chart: Map or Column Chart
- Fields Used: State/Region vs Count of Transactions
- Insight: Geographical distribution of sales.

Interactive Slicers
-------------------

To make the dashboard dynamic and user-driven, the following slicers were added:
- Gender
- State
- Wealth Segment

These allow stakeholders to filter and explore insights based on various demographic and regional factors.

Tools Used
----------

- Power BI Desktop
- Python (for initial preprocessing and splitting of dataset)
- Pandas, Jupyter Notebook
- CSV to Excel transformation for loading into Power BI

How to Use
----------

1. Open Power BI Desktop.
2. Load the split .csv or .xlsx files into the workspace.
3. Create visuals using appropriate charts.
4. Add slicers for interactivity.
5. Explore insights and refine visuals based on need.

Insights Derived
----------------

- Majority of customers are aged between 30–50 years.
- Male and Female customer distribution is almost balanced.
- In-store purchases dominate, but online preference is rising.
- Certain product classes/brands drive significantly higher sales.
- Some regions consistently outperform others in sales volume.

Acknowledgment
--------------

This dashboard and analysis were created as part of the KPMG Data Analytics Consulting Virtual Internship hosted on Forage. All data is fictional and intended for educational purposes.
