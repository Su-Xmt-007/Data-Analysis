# Sales Dashboard Project

## 📊 Project Overview

This project analyzes retail sales data and provides insights through
interactive pivot tables and a dashboard. The goal is to understand
sales trends, identify peak hours, top-selling products, and store
performance, and generate actionable insights to improve business
decisions.

------------------------------------------------------------------------

## 📂 Repository Structure

    MainRepo/
     ├─ README.md   ← Project overview and documentation
     ├─ Dashboard creating(AutoRecovered).xlsx
     │    ├─ Sheet1 → Raw transactions data
     │    ├─ PivotTables → Aggregated sales insights
     │    ├─ Dashboard → Visualization layout

------------------------------------------------------------------------

## 📑 Data Description

### **Sheet1 (Raw Data)**

Contains transaction-level details: - `transaction_id` -- Unique ID per
transaction\
- `transaction_date` & `transaction_time` -- Date & time of purchase\
- `Month Name`, `Day Name`, `Hour` -- Time-based features\
- `store_id`, `store_location` -- Store identifiers\
- `product_id`, `product_category`, `product_type`, `product_detail`,
`Size` -- Product details\
- `transaction_qty`, `unit_price`, `Total Bill` -- Sales metrics

------------------------------------------------------------------------

### **PivotTables (Insights)**

Pre-built summaries for analysis: 1. **Per Hour Transaction Quantity** →
Identifies hourly sales patterns\
2. **Day-Wise Total Sales** → Weekly sales distribution\
3. **Month-Wise Total Sales** → Seasonal/Monthly trends\
4. **Top 5 Product Categories** → Best-selling product categories by
revenue

------------------------------------------------------------------------

### **Dashboard (Visualization Layer)**

-   Interactive dashboard summarizing:
    -   Hourly & daily sales activity\
    -   Monthly revenue trends\
    -   Top products & categories\
    -   Store location performance

------------------------------------------------------------------------

## ❓ Key Business Questions Answered

-   How do sales vary by **day of the week** and **hour of the day**?\
-   Are there any **peak times** for sales activity?\
-   What is the **total sales revenue per month**?\
-   How do sales vary across different **store locations**?\
-   What is the **average price/order per person**?\
-   Which **products are best-selling** in terms of quantity and
    revenue?\
-   How do sales vary by **product category and type**?\
-   (Extra for coffee sales): Which **products are most often bought
    with coffee** → for bundle promotions

------------------------------------------------------------------------

## 🚀 How to Use

1.  Open the Excel file\
2.  Explore **Sheet1** for raw data\
3.  Use **PivotTables** to slice and analyze specific trends\
4.  View the **Dashboard** sheet for summarized visuals

------------------------------------------------------------------------

## 📌 Future Enhancements

-   Add interactive slicers with improved formatting (rounded borders,
    custom styles)\
-   Explore product combination analysis for **cross-selling**
    opportunities (e.g., Coffee + Pastry bundles)\
-   Automate reporting using Python or Power BI
