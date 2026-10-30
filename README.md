# E-commerce-Sales-Dashboard
An interactive, multi-page Excel dashboard that analyses the sales performance of an e-commerce business across targets, products, regions and customers. The project turns raw order data into a clean, navigable report with KPI cards, slicers, timelines and conditional-formatted tables, so managers can see performance at a glance and drill down by month, region, product category, age group and gender.

# Project Objective 🎯
Track revenue vs. target and measure achievement %.
Identify top-performing products and categories.
Compare regional performance, delivery speed and customer satisfaction.
Understand customer demographics and who drives revenue.

# Headline KPIs 📈 
Metric                     Value
Total Target             	$11.40M
Total Revenue	            $10.37M
Total Profit	            $3.44M
Achievement %	            90.99%
Total Orders	            1.00K
Quantity Sold	            3.40K
Total Customers	          200
Avg Order Value	          $10.37K
Avg Discount	            9.01%

# Dashboard Pages
The workbook has four pages linked by a navigation bar (buttons 1–4).

## 1. E-commerce Analysis Dashboard

* KPI cards: Total Target, Revenue, Profit, Achievement %
* Target vs Actual by month (April is the peak month at $1.74M)
* Month-wise revenue and achievement % (2025 / 2026 toggle)
* Orders by year (69% / 31% split)
* Shop-type sales: Express ($2.22M), Outlet ($2.11M), Mall ($2.10M), Flagship ($1.99M), Standard ($1.96M)
* Manager slicer to filter the whole page

## 2. Product Analysis Dashboard

* KPI cards: Quantity Sold, Revenue, Target, Avg Discount
* Top 10 vs remaining 40 products: top 10 contribute ~63% of revenue
* Top 10 / Bottom 10 selling products (Electric Kettle, USB-C Hub, Smart Watch lead)
* Category table with target, revenue, profit and avg discount using conditional formatting
* Month timeline slicer

## 3. Customer Analysis Dashboard
   
* KPI cards: Total Customers, Total Orders, Avg Order Value, Avg Discount
* Revenue by gender and age group
* Gender contribution: Female 54% / Male 46%
* Orders by age group (Adult 466, Old 119, Senior 415)
* Top 5 customers by revenue (funnel chart)
* Age group and gender slicers

## 4. Region Analysis Dashboard

* KPI cards: Avg Order Value, Revenue, Orders, Achievement %
* Regional performance table with revenue rank and achievement rank (Dhaka has the highest achievement at 94.34%)
* Region-wise customer rating distribution (1–5)
* Region-wise average delivery days (Rangpur slowest at 6.43, Dhaka fastest at 2.97)
* Month timeline slicer

# Key Insights 💡
* Overall target achievement is 90.99%, leaving a gap of about $1.03M to target.
* Revenue peaks in April, then drops sharply from June onward.
* The top 10 products generate ~63% of revenue, so the business depends heavily on a few products.
* Electronics and Home Appliance are the biggest categories by revenue, but also carry the highest average discounts (~12.5%).
* Barishal earns the most revenue, while Dhaka has the best achievement % and fastest delivery.
* Rangpur has the slowest delivery and the weakest customer ratings, a clear area for improvement.
* Female customers contribute slightly more revenue (54%) than male customers (46%).

# Tools & Techniques 🛠️
* Microsoft Excel
* Power Query (data cleaning and transformation)
* PivotTables and PivotCharts
* Slicers and Timelines
* Conditional formatting, KPI cards, form-control buttons and page navigation
* Charts: column, line, donut, pie, bar, stacked bar, funnel

# Repository Structure 📁
ecommerce-sales-dashboard/
├── README.md
├── data/
│   └── Data.xlsx
├── Dashboard/
│   └── Dashboard_file.xlsx
├── images/
│   ├── cover.png
│   ├── dashboard-1-ecommerce.png
│   ├── dashboard-2-product.png
│   ├── dashboard-3-customer.png
│   └── dashboard-4-region.png
└── Ecommerce_Dashboard_portfolio.pdf

# How to Use
1 * Download dashboard/ecommerce_sales_dashboard.xlsx.
2 * Open it in Microsoft Excel (desktop, 2016 or later).
3 * Use the numbered buttons on the left to switch between pages.
4 * Use the slicers and timelines to filter the data. Click the filter-clear icon to reset.

# Author👤 

Saif Mahmud 🔗 LinkedIn

If you found this project useful, feel free to ⭐ the repo and connect with me.
