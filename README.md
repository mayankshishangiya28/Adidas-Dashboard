👟 Adidas Sales Analysis Dashboard

<div align="center">



📊 Interactive Power BI Dashboard for Adidas Sales Performance

Sales • Profitability • Products • Regions • Retailers • Trends

</div>

🚀 Project Overview

The Adidas Sales Analysis Dashboard is a Power BI business intelligence project designed to analyze sales performance across time, regions, states, products, and retailers.

The dashboard converts raw sales data into an interactive visual report that helps users quickly understand key business KPIs, sales trends, regional contribution, product performance, and retailer performance.

🎯 Project Objectives

Monitor overall sales and profitability

Analyze monthly sales trends

Compare performance across regions and states

Identify high-performing products

Compare major retailers

Track important business KPIs in one place

Support faster, data-driven business analysis

📌 Dashboard KPIs

KPI

Dashboard Value

💰 Total Sales

$900M

📦 Units Sold

2M

💵 Price per Unit

45.22

📈 Operating Profit

$332M

🎯 Operating Margin

42%

Values above are the headline figures displayed in the dashboard screenshot.

📊 Dashboard Sections

1. 📈 Total Sales by Month

Shows how sales change throughout the year and highlights monthly peaks and declines.

2. 🗺️ Total Sales by State

Provides a state-level comparison to identify geographic markets with higher sales contribution.

3. 🌎 Sales by Region

The donut chart breaks total sales into regional segments such as West, Northeast, Southeast, South, and Midwest.

4. 👕 Sales by Product

Compares product categories and highlights products contributing more strongly to total sales.

5. 🏬 Sales by Retailer

Compares retailer performance across major sellers such as West Gear, Foot Locker, Sports Direct, Kohl's, Amazon, and Walmart.

🛠️ Tools & Technologies

Tool

Purpose

Microsoft Power BI

Dashboard development & visualization

Power Query

Data cleaning & transformation

DAX

KPI calculations & business measures

Excel / CSV

Data preparation and source data

🔍 Key Analysis Areas

The dashboard focuses on five core business questions:

How much total sales and operating profit were generated?

Which months produced the highest sales?

Which regions and states contributed the most sales?

Which products performed strongly?

Which retailers generated higher sales?

🎨 Dashboard Design

The dashboard uses a clean business-reporting layout with:

Dark header with Adidas branding

KPI cards for quick executive-level monitoring

Consistent typography and spacing

Area/line chart for monthly trends

Horizontal and vertical bar charts for comparisons

Donut chart for regional contribution

Interactive Region and Invoice Date filters

Business-focused visual hierarchy for quick decision-making

📂 Suggested Repository Structure

Adidas-Sales-Analysis/
│
├── README.md
├── assets/
│   └── adidas-sales-dashboard.png
│
├── data/
│   └── adidas_sales_data.xlsx
│
└── dashboard/
    └── Adidas_Sales_Analysis.pbix

Rename the files/folders to match the actual files in your repository.

📷 Dashboard Preview

<p align="center">
  <img src="assets/adidas-sales-dashboard.png" alt="Adidas Sales Analysis Power BI Dashboard" width="100%">
</p>

💡 Example Business Insights

The dashboard can be used to investigate questions such as:

Which month generated the highest sales?

Which states contribute the most revenue?

Which region has the largest share of total sales?

Which product category generates stronger sales?

Which retailer contributes the most sales?

How does operating profit compare with total sales?

These questions demonstrate how Power BI can turn transaction-level data into a management-friendly analytical dashboard.

🧮 Example DAX Measures

Total Sales = SUM(Sales[Total Sales])

Units Sold = SUM(Sales[Units Sold])

Average Price per Unit = AVERAGE(Sales[Price per Unit])

Operating Profit = SUM(Sales[Operating Profit])

Operating Margin = DIVIDE([Operating Profit], [Total Sales], 0)

Update table and column names to match your Power BI data model.

▶️ How to Use the Project

Clone or download this repository.

Open the .pbix file in Microsoft Power BI Desktop.

Verify the data source path if required.

Refresh the dataset.

Use the Region and Invoice Date filters to explore the dashboard.

📌 Learning Outcomes

This project demonstrates practical skills in:

Data cleaning and transformation

Data modeling

DAX calculations

KPI design

Business data visualization

Interactive dashboard development

Sales and profitability analysis

Presenting insights for business users

👨‍💻 Author

Your Name
Power BI | Data Analytics | Business Intelligence

⭐ Support the Project

If you found this Power BI project useful, consider giving the repository a ⭐ Star and sharing it with other data analytics learners.

<div align="center">

Built with Microsoft Power BI 📊

</div>
