📊 Marketing ROI & Budget Optimization Analysis
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/62854527-a72b-45ef-84f9-083f2da38830" />

End-to-End Marketing Analytics Project

This project analyzes 200,000 marketing campaign records across two years to evaluate marketing performance, identify inefficiencies, and develop a data-driven marketing budget optimization strategy.

The analysis combines SQL data architecture, statistical testing, Python optimization modeling, and Power BI dashboards to deliver actionable insights for marketing decision-making.

🚀 Project Objective

The goal of this project is to determine whether strategic reallocation of marketing budget across channels and customer segments can improve profitability without significantly increasing total spend.

Key analytical questions addressed:

Which marketing channels deliver the highest ROI?

Which customer segments are most profitable?

Is there evidence of diminishing returns in marketing spend?

Does engagement strongly influence ROI?

Can budget reallocation improve total marketing profit?

📂 Dataset Overview

The dataset contains 200,000 marketing campaign records across two years.

Key Variables
Column	Description
Company	Brand running the campaign
Campaign_Type	Email, Social Media, Influencer, Display, Search
Target_Audience	Age and gender targeting
Duration	Campaign length (days)
Channels_Used	Marketing platform
Conversion_Rate	% of conversions
Acquisition_Cost	Cost of campaign
ROI	Return on investment
Location	Campaign geography
Language	Campaign language
Clicks	Number of ad clicks
Impressions	Ad impressions
Engagement_Score	Engagement metric (1–10)
Customer_Segment	Audience category
Date	Campaign date
🏗️ Project Architecture

The project follows a full analytics workflow:

Raw Dataset
     ↓
PostgreSQL Data Architecture
     ↓
Data Cleaning & Feature Engineering
     ↓
Exploratory Data Analysis (SQL + Excel)
     ↓
Statistical Testing
     ↓
Python Optimization Modeling
     ↓
Power BI Data Modeling
     ↓
Interactive Executive Dashboard
🗄️ Data Architecture (PostgreSQL)

Data was processed using PostgreSQL to build a structured analytical data model.

Key Steps

Raw dataset ingestion

Data cleaning and transformation

Business rule validation

Feature engineering

Fact table creation

Derived Metrics

CTR (Click Through Rate)

CPA (Cost per Acquisition)

Conversion Volume

Total Revenue

Total Profit

ROI Ratio

Core Analytical Table
Fact_Marketing_Performance

This table was used for all analytical queries.

🔍 Exploratory Data Analysis

EDA was conducted using SQL and Excel.

Key Analyses

Channel ROI comparison

Segment-level profitability

Geographic performance

Marketing funnel efficiency

Funnel Analysis
Impressions
     ↓
Clicks
     ↓
Conversions

This analysis revealed patterns in campaign efficiency and customer behavior.

📈 Statistical Analysis & Hypothesis Testing

Several statistical techniques were applied to validate observed trends.

1️⃣ Correlation Analysis

Objective:
Determine relationship between marketing spend and ROI.

Result:

Correlation (Spend vs ROI) = -0.41

Interpretation:

Moderate negative relationship

Higher spend often produces lower ROI

Evidence of diminishing returns

2️⃣ T-Test: High vs Low Budget Campaigns

Hypothesis:

H0: High and low budget campaigns have equal ROI
H1: ROI differs significantly

Result:

Low-budget campaigns show higher average ROI, suggesting efficiency declines at higher spend levels.

3️⃣ ANOVA Test (Campaign Type Impact)

Result:

p-value < 0.05

Interpretation:

Campaign type significantly affects ROI.

Marketing channel selection is therefore a critical strategic decision.

4️⃣ Regression Modeling

A multiple linear regression model was built using:

Independent variables:

Acquisition Cost

Engagement Score

Campaign Duration

Dependent variable:

ROI

Key insight:

Engagement metrics show weak predictive power for profitability.

🤖 Budget Optimization Modeling (Python)

A scenario-based optimization model was built to simulate strategic marketing budget changes.

Scenario Adjustments
Change	Adjustment
Email channel	-5% budget
Google Ads	+10% budget
Foodies segment	-10% budget
Outdoor Adventurers segment	+10% budget

Revenue and profit were recalculated using historical ROI.

📊 Optimization Results
Metric	Value
Current Profit	₹5.73B
Optimized Profit	₹6.01B
Profit Improvement	4.86%
Key Insights

Budget reallocation improved overall marketing efficiency

High-performing segments received increased investment

Low-efficiency segments experienced reduced spending

Profit increased without major growth in total marketing spend

📊 Power BI Data Modeling

A Star Schema data model was implemented.

Fact Table
Fact_Marketing_Performance
Dimension Tables
Dim_Channel
Dim_Segment
Dim_Date
Dim_Location
Key DAX Measures
Total Spend =
SUM(Fact_Marketing_Performance[acquisition_cost])

Total Revenue =
SUM(Fact_Marketing_Performance[total_revenue])

ROI % =
DIVIDE([Total Revenue]-[Total Spend],[Total Spend])

CPA =
DIVIDE(
SUM(Fact_Marketing_Performance[acquisition_cost]),
SUM(Fact_Marketing_Performance[conversion_volume])
)

CTR =
DIVIDE(
SUM(Fact_Marketing_Performance[clicks]),
SUM(Fact_Marketing_Performance[impressions])
)
📊 Power BI Dashboard

The project includes a 3-page interactive dashboard.

1️⃣ Executive Overview

Key visuals:

KPI Cards (Spend, Revenue, Profit, ROI)

ROI by Channel

Spend vs ROI Scatter Plot

Year-over-Year ROI Trend

2️⃣ Campaign Performance Analysis

Key visuals:

Marketing Funnel

Segment Conversion Analysis

Engagement vs ROI Heatmap

Geographic Performance Map

3️⃣ Budget Optimization Simulation

Key visuals:

Current vs Recommended Budget Allocation

ROI Curve (Diminishing Returns)

Channel Efficiency Comparison

Profit Impact Summary

💼 Business Impact

The analysis demonstrates how data-driven marketing strategies can improve financial performance.

Key outcomes:

4.86% increase in total marketing profit

Improved marketing efficiency

Reduced wasteful campaign spending

Better allocation of marketing budget

🧠 Strategic Recommendations

1️⃣ Reallocate budget toward high-performing channels
2️⃣ Reduce spending on inefficient customer segments
3️⃣ Monitor diminishing returns for large campaigns
4️⃣ Implement continuous ROI tracking
5️⃣ Use analytics-driven budget allocation frameworks

🛠️ Tools & Technologies
Tool	Purpose
PostgreSQL	Data architecture & SQL analysis
Excel	Statistical testing
Python	Optimization modeling
Power BI	Data modeling & dashboard visualization
🎯 Project Skills Demonstrated

SQL Data Architecture

Data Cleaning & Feature Engineering

Exploratory Data Analysis

Statistical Hypothesis Testing

Regression Modeling

Scenario-Based Optimization

Business Intelligence Dashboard Design

📌 Portfolio / Interview Summary

This project demonstrates end-to-end marketing analytics capability — from SQL-based data architecture and statistical validation to optimization modeling and executive-level Power BI dashboards for strategic decision-making.
