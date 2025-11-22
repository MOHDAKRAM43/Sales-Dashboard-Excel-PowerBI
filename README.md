# Sales-Dashboard-Excel-PowerBI
**📊 SuperStore Sales Dashboard & 15-Day Forecasting**

This project showcases an interactive SuperStore Sales Performance Dashboard along with a 15-Day Sales Forecasting Model built in Power BI.
The solution provides deep insights into sales performance, profitability, customer behavior, and future sales trends using time-series forecasting.

**🚀 Project Overview**

This project analyzes SuperStore sales data (2019–2021) and presents the insights through beautifully designed dashboards. It consists of two major components:
📘 Sales Performance Dashboard (Descriptive Analytics)
Regional, monthly, and state-level sales performance
Category & subcategory breakdowns
Profit analysis
Payment mode, segment, and shipping mode insights

📈 Sales Forecast Dashboard (Predictive Analytics)
15-day sales forecast
Historical sales trends
Time-series forecasting model using Power BI
State-level sales distribution

**🛠️ Tech Stack & Tools**
Component	Technology
Data Visualization	Power BI
Forecasting Model	Power BI Analytics / Time-Series Forecasting
Data Source	Sample SuperStore Dataset
Data Cleaning	Power Query
Data Modelling	Star Schema with Date Table

**📥 Data Source & Preprocessing**
📌 Data Source
The SuperStore dataset was extracted from an Excel file (.xlsx).

📌 Cleaning & Filtering Performed
Using Power Query, the following steps were applied:
Removed duplicate records
Standardized date formats
Fixed missing values where required
Filtered invalid or negative values
Created a separate Date Table for accurate time intelligence
Formatted data types (numeric, categorical, date fields)
Removed unnecessary columns
Added calculated columns for better segmentation


**📸 Dashboard Previews**
⭐ Sales Overview Dashboard
Sales by Region
Sales by Segment
Sales by Payment Mode
Yearly Sales & Profit Trends
Orders, Profit & Ship Days KPIs
Sales by Category & Subcategory
Profit & Sales by State (Map Visualization)

![Sales Dashboard]([/mnt/data/Overview dashboard.png](https://github.com/MOHDAKRAM43/Sales-Dashboard-Excel-PowerBI/blob/main/Overview%20dashboard.png))

⭐ 15-Day Sales Forecast Dashboard
15-Day forecasting visual using historical trend
Detailed zoom-in forecast section
State-level sales performance
Trend comparisons across months

**📊 Key Insights**
✔ Sales Performance
Total Sales: $2M+
Total Orders: 22K
Profit Generated: $175K
Average Ship Time: 4 Days

✔ Top Performing Segments & Regions
Segment Leader: Consumer (48%)
Top Region: West (33%)

✔ Category Breakdown
Office Supplies → $0.64M
Technology → $0.47M
Furniture → $0.45M

✔ Forecasting Insights
Next 15 days show an upward trend
Predicted spike up to ~10K sales
Seasonality detected around month-end

🧠 Data Model
A clean Star Schema model was designed:
Fact Table: Sales Fact
Dimension Tables: Date, Customer, Product, Category, Region, Segment
This ensures optimized performance and clean DAX calculations.

**📌 Features Implemented**
🔹 Power Query Data Cleaning
Removed duplicates
Normalized fields
Created Date table
Added conditional columns

🔹 DAX Measures
Total Sales
Total Profit
Orders Count
YOY Sales
Sales Forecast
Average Shipping Days

**🔹 Dashboard Interactivity**
Drill-downs
Slicers for Region
Tooltip insights
Dynamic Forecast visuals

**🎯 Business Value**
This dashboard helps companies:
Understand sales trends quickly
Identify profitable categories & regions
Predict upcoming sales
Improve inventory decisions
Optimize shipping and customer segmentation strategies
Incorporated data analysis techniques, specializing in time series analysis, to deliver valuable insights, accurate sales forecasting, and interactive dashboard creation, driving business success.

**📥 How to Use the Dashboard**

Download the .pbix file (if included).
Open using Power BI Desktop.
Refresh data if required.
Interact using slicers & filters to explore insights.

**📎 Future Enhancements**

Add RLS (Row-Level Security)
Integrate real-time data using APIs
Add customer churn prediction model
Build automated refresh pipeline using Power BI Service

**⭐ Author**
Mohd Akram
Data Engineer | BI Developer
linkedin : (https://www.linkedin.com/in/mohd-akram-6a210a259/)
