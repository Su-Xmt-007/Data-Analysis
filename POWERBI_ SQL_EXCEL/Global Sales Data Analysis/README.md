🌍 Global Sales Data Analytics Project – 2025

End-to-End Retail Sales Analytics | PostgreSQL | SQL | Advanced Statistics | Power BI | Executive Reporting

📌 Project Overview

This project presents a complete enterprise-grade sales analytics solution built on a multi-country retail dataset (Canada, China, India, Nigeria, UK, US).

The goal was to move beyond descriptive analytics and answer:

🔎 What happened?
🧠 Why did it happen?
🚀 What should management do next?

This project integrates:

🏗 Enterprise Data Architecture (PostgreSQL)

📊 Advanced SQL Exploratory Data Analysis

📈 Statistical Testing (T-Test, ANOVA, Chi-Square)

📉 Regression Modeling

📊 Power BI Executive Dashboards

📘 Executive-Level Strategic Report

🏗 1️⃣ Data Architecture (PostgreSQL)
🔹 Enterprise Layered Design

Implemented a 4-layer architecture:

Layer	Purpose
RAW	Exact CSV ingestion (no transformation)
VALIDATION	Null checks, duplicates, invalid data detection
TRANSFORM	Data cleaning, type casting, metric calculation
FACT	Analytics-ready structured table
✅ Business Metrics Computed

Gross Revenue

Discount Amount

Net Revenue

Total Cost

Total Profit

Profit Margin

🛠 Technologies Used

PostgreSQL

pgAdmin 4

SQL Validation Logic

Error Logging Table

🔍 2️⃣ Data Integrity Correction

During EDA, financial inconsistencies were discovered:

Unrealistic cost structure

Excessive discounts (up to 98%)

Artificial negative profits

🔧 Corrections Applied

Reconstructed cost price (65–75% of selling price)

Standardized discount range (0–40%)

Recalculated all financial metrics

✅ Result: Dataset became economically realistic and decision-ready.

📊 3️⃣ Exploratory Data Analysis (SQL)
Key Business Questions Answered
🌍 Performance

Which country generates highest revenue?

Seasonal trends by month?

Revenue volatility analysis?

📦 Profitability

Top profitable categories

Discount vs margin analysis

High-margin low-volume products

👥 Customer Behavior

Age group revenue contribution

Gender-wise profit

Payment method preference

⚠ Risk & Stability

Revenue volatility (CV = 82%)

Profit margin stability (CV = 42%)

Outlier detection (Z-score & IQR)

📈 4️⃣ Advanced Statistical Testing

Moved from descriptive → diagnostic analytics.

🔹 T-Test (Adult vs Senior)

p = 0.728

Cohen’s d = 0.015

❌ No significant difference in purchase quantity.

🔹 ANOVA (Store Location → Profit Margin)

p = 0.629

Eta² = 0.0048

❌ Geography does not drive profitability.

🔹 Chi-Square (Age × Payment Method)

p = 0.107

Cramer’s V = 0.038

❌ Payment preference not dependent on age.

📉 5️⃣ Multiple Regression Modeling
Model Strength

R² ≈ 4.9%

Statistically significant overall

Significant Predictor
Variable	Impact	Result
Quantity Purchased	Strong Positive	✅ Significant
Discount Applied	Weak	❌ Not significant
Price Per Unit	Slight Negative	⚠ Small effect
Country	None	❌ Not significant
Category	None	❌ Not significant
🎯 Core Business Finding

🔥 Profit is volume-driven.

After eliminating:

Geography

Category

Demographics

Discount

Payment behavior

Only Quantity Purchased significantly impacts profit margin.

📊 6️⃣ Power BI Dashboard

Built a 3-page interactive dashboard:

📌 Executive Summary

KPI Cards

Revenue Trend

Country Comparison

Profit Overview

🌍 Regional Deep Dive

Map Visualization

Category Profit Matrix

Store Heatmap

👥 Customer Behavior

Age × Gender Treemap

Payment Method Distribution

Discount Sensitivity Scatter

🔥 Advanced Features

Drill-through pages

Dynamic Top N filter

KPI vs Target comparison

Page navigation buttons

📘 7️⃣ Executive Report

A professional board-level PDF report was generated summarizing:

Data governance

Financial validation

Statistical results

Regression insights

Strategic recommendations

📎 See: Global_Sales_Executive_Report_2025.pdf

🧠 Strategic Recommendations

Instead of:

❌ Heavy discounting
❌ Geography restructuring
❌ Demographic segmentation

Focus on:

✅ Increasing basket size
✅ Cross-selling & upselling
✅ Volume growth strategies
✅ Operational efficiency
✅ Seasonal inventory planning

🚀 Business Impact

Expected outcomes:

+4–7% margin improvement

Increased revenue stability

Reduced operational leakage

Better marketing ROI

🛠 Tech Stack
Tool	Purpose
PostgreSQL	Data warehouse
SQL	EDA & Validation
Excel	Statistical Testing
Power BI	Dashboard & Visualization
Python (ReportLab)	PDF Report Generation
📂 Repository Structure
/data
    sales_Canada.csv
    sales_China.csv
    ...
/sql
    schema_creation.sql
    data_validation.sql
    eda_queries.sql
    regression_queries.sql
/powerbi
    Sales_data.pbix
/report
    Global_Sales_Executive_Report_2025.pdf
README.md

🎓 What This Project Demonstrates

Enterprise data modeling

Advanced SQL proficiency

Statistical thinking

Hypothesis-driven analytics

Business storytelling

Dashboard design expertise

Executive communication skills

👨‍💻 Author

Subhamoy Hazra
Data Analyst | SQL | Power BI | Statistical Modeling
