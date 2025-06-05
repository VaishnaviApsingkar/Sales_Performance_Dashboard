# 📊 Sales Performance Dashboard – Power BI Project

An interactive Power BI dashboard designed to analyze sales, profit, and target performance across fiscal years, product categories, regions, and salespersons. The report demonstrates end-to-end business intelligence capabilities, including advanced DAX calculations, visual storytelling, and actionable insights.

- Link to Power BI Report

https://github.com/VaishnaviApsingkar/Sales_Performance_Dashboard/blob/main/Sales_Analysis_Report.pbix

---

## 🧠 Objective

To build a comprehensive dashboard that enables business stakeholders to:
- Monitor profit trends by year and quarter
- Compare sales vs. targets
- Analyze sales quantity and margin by product category and region
- Identify top-performing salespersons and underperformers
- Make data-driven decisions based on historical sales performance

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (M Language)**
- Excel as data source

---

## 📌 Key Features

- **Financial Performance Summary**
  - Year-wise and quarter-wise breakdown of sales, cost, profit, and margin
- **Category Analysis**
  - Sales quantity and profit distribution by product category
- **Geographic Insights**
  - Sales by region and country with interactive filters
- **Salesperson Performance**
  - Variance from targets with percentage margins
- **Time Intelligence**
  - Month-wise trend of total sales vs. targets using DAX time functions

---

## 🧮 DAX Measures Used

- `Profit = [Sum of Sales] - [Sum of Cost]`
- `Profit Margin = DIVIDE([Profit], [Sum of Sales])`
- `Variance = [Sum of Sales] - [Target Amount]`
- `Variance Margin = DIVIDE([Variance], [Target Amount])`
- Time-based filters and aggregation using **CALCULATE**, **FILTER**, **ALL**, and **DATEADD**

---

## 📊 Visuals Included

- Bar charts (profit by quarter)
- Line graphs (sales vs. target by month)
- Pie charts (profit by category)
- Tables (financial breakdown, salesperson rankings)
- Interactive slicers for region, year, and salesperson

---

## 🧩 Skills Demonstrated

- Advanced data modeling and relationship building
- Custom DAX measure creation and debugging
- Designing user-friendly dashboards for business users
- Performance optimization and conditional formatting
- Business storytelling using data visualization

---

## 📣 License

This project is for academic and portfolio use only. Commercial use is not permitted without consent.
