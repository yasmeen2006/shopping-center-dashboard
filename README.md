# 🛍️ Shopping Center Analytics Dashboard

An interactive Power BI dashboard providing real-time insights into shopping center performance, customer demographics, sales trends, and vendor analytics.

## 📊 Dashboard Overview

This multi-page Power BI dashboard visualizes shopping center operations data to support data-driven business decisions across:

- 📈 **Sales Performance** — Daily/weekly/monthly revenue trends
- 👥 **Customer Analytics** — Demographic breakdowns, visit patterns, spending behavior
- 🏪 **Vendor Performance** — Store-level sales, footfall, top products
- 💳 **Payment Trends** — Payment method preferences, transaction values
- 🗓️ **Temporal Patterns** — Busiest hours/days, seasonal trends

## 🎯 Dashboard Features

### 📌 Key Metrics (KPIs)
- Total Revenue
- Average Transaction Value
- Customer Count
- Vendor Count
- Repeat Customer %

### 📊 Visualizations
- **Line Charts** — Revenue trends over time
- **Bar Charts** — Top vendors, categories, payment methods
- **Pie Charts** — Customer demographic distribution
- **Heatmaps** — Busiest shopping times
- **KPI Cards** — Quick-glance metrics
- **Drill-down Filters** — Filter by date, vendor, category, location

### 🎮 Interactive Features
- **Slicers** — Filter by date range, vendor, product category
- **Cross-filtering** — Click any chart to filter all others
- **Drill-through** — Dive from summary to transaction-level detail
- **Tooltips** — Hover for detailed information

## 🛠️ Tech Stack

`Power BI` `Power Query` `DAX` `Excel` `Data Modeling`

## 📁 Files

| File | Description |
|------|-------------|
| `Shopping_center_dashboard.pbix` | Main Power BI dashboard file |
| `assignment_shopping_dataset.xlsx` | Source dataset (50K+ shopping records) |

## 📊 Data Model

**Tables:**
- Transactions (fact table) — 50K+ records
- Customers (dimension) — Demographics, segments
- Vendors (dimension) — Store information, category
- Calendar (dimension) — Date hierarchy for time analysis

**Relationships:**
- Transactions → Customers (many-to-one)
- Transactions → Vendors (many-to-one)
- Transactions → Calendar (many-to-one)

## 🔍 Insights Delivered

- 🏆 Top 5 vendors by revenue
- 📅 Peak shopping hours and days
- 💳 Customer payment preferences
- 🔄 Repeat customer identification and behavior
- 🎯 Average spend by customer segment
- 📍 Footfall density by store location

## 🚀 How to Use

1. **Download** `Shopping_center_dashboard.pbix`
2. **Open** in Power BI Desktop (free or Pro version)
3. **Refresh Data** — Connect to your data source
4. **Explore** — Click filters, charts, and drill-down options
5. **Publish** — Share to Power BI Service for team access

## 📈 Dashboard Pages

1. **Executive Summary** — High-level KPIs and key metrics
2. **Sales Analytics** — Revenue trends, top products, categories
3. **Customer Insights** — Demographics, visit frequency, spending patterns
4. **Vendor Performance** — Store rankings, traffic, conversion rates
5. **Operational Metrics** — Peak times, payment methods, transaction analysis

## 💡 Business Impact

- **Identify** top-performing vendors and product categories
- **Optimize** staffing based on peak shopping hours
- **Target** high-value customer segments
- **Improve** vendor performance through benchmarking
- **Forecast** revenue based on historical trends
