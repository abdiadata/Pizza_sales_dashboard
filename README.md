# Pizza_sales_dashboard
Excel dashboard analyzing a year of pizzeria sales — revenue trends, peak ordering hours, and top/bottom-performing menu items, built with formula-driven pivot tables and charts.
# Pizza Sales Dashboard (Excel)

An Excel-based sales performance dashboard analyzing a full year of pizzeria order data, built with formula-driven pivot tables, KPI cards, and charts.

## Overview

This project analyzes 48,620 order line items (21,350 orders) from a pizzeria's 2015 sales data to surface what's driving revenue, when demand peaks, and which menu items are over- and under-performing.

Every summary table is built with live Excel formulas (`SUMIFS`, `COUNTIFS`, `AVERAGEIFS`, `INDEX`/`MATCH`) referencing the raw data — nothing is hardcoded, so the workbook recalculates automatically if the underlying data changes.

**Dataset:** 48,620 order line items · 21,350 unique orders · 49,574 pizzas sold · 32 pizza varieties · full year 2015 · $817,860 total revenue

## Key Insights

- **Large (L) pizzas drive nearly half of all revenue**, far ahead of Medium and Small — sizing/pricing strategy is clearly working in that segment.
- **Classic and Supreme categories lead in revenue**, with Chicken and Veggie close behind — a fairly balanced menu, not a single-category business.
- **Clear lunch and dinner rush pattern**: order volume peaks around 12–1pm and again at 5–7pm, with very little activity before 11am or after 10pm — useful for staffing and prep timing.
- **A handful of specialty pizzas (e.g., Brie Carre, Green Garden) consistently underperform** on revenue, making them candidates for menu review, repricing, or promotion.

## What's in the Workbook

| Sheet | Contents |
|---|---|
| `Dashboard` | KPI summary (revenue, orders, pizzas sold, AOV) + category, monthly trend, and day-of-week charts |
| `Pivot_Category` | Revenue, quantity, and average price by pizza category |
| `Pivot_Size` | Revenue and quantity by size (S/M/L/XL/XXL) |
| `Pivot_HourlyTrend` | Revenue and order volume by hour of day — identifies peak demand windows |
| `Top_Pizzas` | Top 10 and bottom 10 pizzas by revenue |
| `Data` | Raw order-level data, with derived Month/Day-of-Week/Hour helper columns |

## Skills Demonstrated

- Data aggregation with `SUMIFS`, `COUNTIFS`, `AVERAGEIFS`, `INDEX`/`MATCH`
- Time-based analysis (hourly, daily, monthly demand patterns) from raw date/time fields
- Pivot-style summary table design without relying on native Excel PivotTables
- KPI dashboard layout and data visualization (bar, line, pie charts)
- Product performance ranking and menu-optimization analysis
- Structuring a large workbook (48K+ rows) so formulas — not hardcoded values — drive every output

## Tools

Microsoft Excel (formulas, charts, conditional formatting)

## File
[Pizza_Sales_Dashboard.xlsx](https://github.com/user-attachments/files/31501936/Pizza_Sales_Dashboard.xlsx)
