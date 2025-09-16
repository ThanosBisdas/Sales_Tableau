# Sales — Tableau Analysis

Short, self-contained Tableau project analyzing a retail **Orders** dataset (Superstore-style, 2016–2019). It focuses on **Profit, Sales, and Discounts** across product, customer, shipping, and city dimensions.

## Data Fields (high level)
`Order Date (Year)`, `Category`, `Sub-Category`, `Segment`, `Ship Mode`, `City`, `Sales`, `Profit`, `Discount`, plus standard order fields.

## Workbook Contents
- **Profit per Category:** Profit by **Category / Sub-Category** (color highlights top/low performers)
- **Profit per Ship Mode:** Profit share by **Ship Mode** (percent-of-total pie)
- **Sales per City:** **Sales by City** (point view with level-of-sales encoding)
- **Sales per City per Year:** **Sales by City over Years** (Order Date at Year granularity)
- **Sales per Segment:** **Sales** by **Segment × Ship Mode** (crosstab/heatmap comparison)
- **Discount per Sub-Category:** **Discount** by **Sub-Category** (+ **Count of Orders**)
- **Dashboard:** Consolidates the above for a single-glance overview

## Purpose
Provide a compact view of profitability, sales performance, and discounting patterns by product hierarchy, customer segment, shipping method, city, and time.
