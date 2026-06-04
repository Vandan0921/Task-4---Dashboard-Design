# 📊 Sales Analysis Dashboard — Task 4

**Data Analyst Internship | Elevate Labs**

---

## 🛠 Problem Statement

A company selling various products across multiple countries needed a consolidated view of its sales performance, profitability, and discount impact to support data-driven business decisions. Management lacked visibility into key metrics such as total sales, profit, units sold, and discount trends — all critical for identifying growth opportunities and optimizing pricing strategies.

---

## 🎯 Objectives

1. **Analyze Overall Sales Performance** — Track total sales, profit, and discounts across regions and product categories.
2. **Identify Top-Performing Products & Markets** — Determine which countries and products contribute the most revenue.
3. **Understand Seasonal Trends** — Examine monthly and yearly sales trends to optimize inventory and marketing.
4. **Segment Sales by Business Type** — Evaluate how Enterprise, Government, Small Business, etc. contribute to overall sales.
5. **Assess the Impact of Discounts** — Investigate whether higher discounts lead to increased profit or reduced margins.

---

## 🔧 Tools Used

- **Power BI Desktop** — Dashboard creation and interactive visualizations
- **Dataset** — Financial Sample (Kaggle) — `Financial_Sample.xlsx`

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `Financial_Sample.xlsx` | Raw sales dataset used for the dashboard |
| `Sales_Analysis_Dashboard.pbix` | Power BI dashboard file |
| `Sales_Dash.png` | Screenshot of the final dashboard |
| `Sales_Analysis_Dashboard_PPT.pptx` | PPT summary of findings |
| `README.md` | Project documentation |

---

## 📊 Dashboard Overview

### Key KPI Cards
| Metric | Value |
|--------|-------|
| 💰 Total Sales | $118.73M |
| 📈 Gross Sales | $127.93M |
| ✅ Total Profit | $16.89M |
| 🏷️ Total Discounts | $9.21M |
| 📦 Units Sold | 1.13M |

### Visuals Built
- **Bar Chart** — Gross Sales by Country
- **Bar Chart** — Gross Sales by Product
- **Donut Chart** — Units Sold by Segment
- **Scatter Plot** — Discounts & Profit by Product
- **Line Chart** — Sales & Profit by Month
- **Column Chart** — Gross Sales & Profit by Year
- **Slicers** — Year & Segment filters for interactivity

---

## 🔍 Key Insights

- **USA leads globally** with $27.27M, but all 5 countries are within $5M of each other — showing balanced international reach.
- **Paseo is the star product** at $36M gross sales — nearly double the second-best seller VTT ($22M).
- **October–December is peak season**, with the highest monthly sales figures. Inventory and campaigns should be planned 6–8 weeks ahead.
- **Government segment dominates** at 41.81% of all units sold. B2B and government tenders are a key growth lever.
- **Discount risk is real** — $9.21M in discounts against $16.89M profit is a 54% ratio; high-discount SKUs should be re-evaluated.
- **Rapid YoY growth** — Sales jumped from $29M (2013) to $99M (2014), a 241% increase.

---

## 🏗 Steps Followed

1. Imported `Financial_Sample.xlsx` into Power BI Desktop.
2. Cleaned and transformed data using Power Query (checked data types, removed nulls).
3. Created calculated measures for Total Sales, Gross Sales, Profit, Discounts, and Units Sold using DAX.
4. Designed KPI card visuals for summary metrics.
5. Built bar, donut, scatter, line, and column charts for detailed breakdowns.
6. Added Year and Segment slicers for dashboard interactivity.
7. Applied a consistent green/dark color theme across all visuals.
8. Added insight annotations and formatted axis labels for readability.

---

## 📸 Dashboard Preview

![Sales Analysis Dashboard](Sales_Dash.png)

---

## 🗂 Interview Questions & Answers

**Q1. What are the key elements of a dashboard?**
KPI cards, charts (bar, line, pie), filters/slicers, a consistent color theme, and a clear title/navigation structure.

**Q2. What is a KPI?**
A Key Performance Indicator — a measurable value that shows how effectively objectives are being achieved. Examples: Total Sales, Profit Margin, Units Sold.

**Q3. What are slicers in Power BI?**
Visual filter controls that let users interactively narrow data — e.g., by year, region, or segment — without editing the report.

**Q4. Difference between Power BI and Tableau?**
Power BI integrates tightly with Microsoft products (Excel, Azure) and is generally more affordable. Tableau is more flexible for complex visualizations and is favored in non-Microsoft environments. Both offer drag-and-drop dashboards and strong analytics.

**Q5. How do you make a dashboard interactive?**
By adding slicers, drill-throughs, cross-filtering between visuals, bookmarks, and navigation buttons.

**Q6. How do you deal with large datasets in dashboards?**
Use aggregations, DirectQuery/Import modes wisely, apply filters early in Power Query, use summary tables, and enable incremental refresh.

**Q7. What chart types do you use for trend analysis?**
Line charts (time series), area charts (cumulative trends), and column charts (year-over-year comparisons).

---

## 🔗 Dashboard Link

[View Power BI Dashboard on GitHub](https://github.com/tanweer96/Sales_Analysis/blob/main/Sales%20Analysis%20Dashboard.pbix)

---

*Submitted as part of Elevate Labs Data Analyst Internship — Task 4: Dashboard Design*
