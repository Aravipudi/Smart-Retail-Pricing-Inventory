# Smart Retail Pricing & Inventory Optimization

Interactive Power BI dashboard for analyzing retail pricing, sales performance, and inventory optimization.

## Project Overview

This project uses Power BI to analyze retail sales, pricing, and inventory data and turn it into an interactive business intelligence solution.

The goal is to help identify pricing patterns, understand sales performance, evaluate excess inventory, and estimate the potential value that can be released through inventory optimization.

## Business Problem

Retail businesses need to balance pricing and inventory levels carefully.

The project focuses on questions such as:

- How do discounts affect sales performance?
- How does discounting affect net revenue per record?
- Which product categories generate the most revenue?
- How much inventory is currently held?
- How much inventory is above the target level?
- How does the safety factor affect inventory requirements?
- What is the potential inventory value that could be released?

## Solution

The project was divided into two Power BI dashboards.

### Retail Pricing Dashboard

The pricing dashboard provides an interactive view of:

- Total Revenue
- Units Sold
- Inventory Level
- Potential Inventory Value Released
- Average Units Sold by Discount
- Net Revenue per Record by Discount
- Price by Category

Users can interact with the dashboard using filters for:

- Category
- Region
- Discount
- Seasonality

### Inventory Optimization Dashboard

The inventory dashboard evaluates inventory requirements under different safety factor scenarios.

It includes:

- Current Inventory
- Target Inventory
- Excess Inventory
- Inventory Reduction %
- Inventory Value Released
- Safety Factor analysis

The safety factor scenarios allow the user to compare how different inventory policies affect target inventory and potential inventory reduction.

## Key Metrics

### Retail Pricing

| Metric | Value |
|---|---:|
| Total Revenue | 550.23M |
| Units Sold | 10M |
| Inventory Level | 20M |
| Potential Inventory Value Released | 356.04M |

### Inventory Optimization

| Metric | Value |
|---|---:|
| Current Inventory | 20M |
| Target Inventory | 15.51M |
| Excess Inventory | 6.42M |
| Inventory Reduction | 32.00% |

## Key Insights

- Average units sold increase as discounts move toward the 10% range before leveling off.
- Net revenue per record decreases as discount levels increase.
- Discounting can increase sales volume while reducing revenue generated per record.
- Inventory requirements change significantly depending on the selected safety factor.
- Lower safety factor scenarios result in lower target inventory levels.
- Inventory optimization can help identify excess inventory and potential working-capital opportunities.

## Tools & Technologies

- Power BI
- DAX
- Data Modeling
- Data Visualization
- Microsoft Excel / CSV
- Business Intelligence
- Pricing Analysis
- Inventory Optimization

## Dashboard Screenshots

The repository includes screenshots of both Power BI dashboards:

- `retail optimization.png`
- `Inventory optimization.png`

## Project Files

| File | Description |
|---|---|
| Power BI `.pbix` file | Complete Power BI dashboard and data model |
| `retail_store_inventory.csv` | Retail inventory data |
| `smart_retail_executive_summary.csv` | Executive summary data |
| `smart_retail_inventory_scenarios.csv` | Inventory optimization scenarios |
| `smart_retail_pricing_analysis.csv` | Pricing analysis data |
| `retail optimization.png` | Retail pricing dashboard screenshot |
| `Inventory optimization.png` | Inventory optimization dashboard screenshot |

## Conclusion

This project demonstrates how Power BI can transform retail pricing, sales, and inventory data into an interactive decision-support solution.

The dashboard combines technical analysis with business-focused insights to help evaluate pricing strategies, understand inventory requirements, identify excess inventory, and assess potential financial opportunities.

## Repository Contents

This repository contains the Power BI model, supporting datasets, and dashboard screenshots used to develop the solution.
