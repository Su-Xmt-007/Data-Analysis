<img width="750" height="427" alt="image" src="https://github.com/user-attachments/assets/17370d33-6ed3-4647-90aa-15b1caaf61fb" />



📌 Project Overview

This project analyzes a global retail dataset spanning six countries (Canada, China, India, Nigeria, UK, US). As a Data Analyst, the goal is to move beyond descriptive reporting and utilize PostgreSQL, Excel/Python, and Power BI to uncover diagnostic insights that drive business strategy, specifically focusing on regional performance, customer demographics, and payment optimization.



🗂️ Data Scope

The analysis is based on 6 regional CSV files with 15 dimensions:



Transaction Details: Transaction_ID, Date, Sales_Rep.

Product Info: Product_ID, Product_Name, Category, Price_per_Unit, Cost_Price.

Sales Metrics: Quantity_Purchased, Discount_Applied.

Geography & Demographics: Country, Store_Location, Customer_Age_Group, Customer_Gender, Payment_Method.







Step 1: Data Architecture (PostgreSQL)



Schema Design: Unified table structures for multi-country imports.

Data Cleaning: Standardizing date formats (MM/DD/YYYY) and handling null values.

Feature Engineering: SQL scripts to calculate:





Step 2: Exploratory Data Analysis (EDA)



Using SQL to answer critical business questions, including:

Identify the top 3 Sales Reps per region by Net Revenue.

Determine the Month-over-Month (MoM) growth rate of profit.

Analyze the relationship between high discount depth and customer retention.

Gross Revenue: $Price \times Quantity$

Net Revenue: $Gross - Discount$

Total Profit: $Net - Total Cost$

Profit Margin: $Total Profit / Net Revenue$





Step 3: Visualization & Dashboarding



A  interactive dashboard designed for different stakeholder levels:



Executive Summary: Global KPI cards and trend lines.

Regional Deep-Dive: Map-based analysis and category-wise breakdown.

Customer Behavior: Demographic profiles and payment method trends.

<img width="750" height="427" alt="image" src="https://github.com/user-attachments/assets/b1a1c2c3-d7b7-40e1-bd4b-35cc9d01fec5" />

