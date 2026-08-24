# Smart Retail Pricing & Inventory Optimization

Interactive Power BI dashboard designed to analyze retail pricing, sales performance, and inventory optimization opportunities.

## Project Overview

Retail businesses need to balance pricing decisions with inventory levels to maximize revenue while avoiding excess inventory.

This project combines sales, pricing, and inventory data into an interactive Power BI solution that helps identify pricing patterns, evaluate inventory efficiency, and estimate the potential value that can be released through inventory reduction.

## Business Problem

The objective was to answer key business questions:

- How does discounting affect revenue performance?
- How do sales volumes change across different discount levels?
- Which product categories generate the most revenue?
- How much inventory is currently held?
- How much inventory could potentially be reduced?
- How does the selected safety factor affect inventory requirements?
- What is the potential inventory value that could be released?

## Approach

The project was developed using a combination of data preparation, DAX calculations, and interactive Power BI visualizations.

The analysis was structured into two main areas:

### 1. Retail Pricing Analysis

The pricing dashboard evaluates:

- Total revenue
- Units sold
- Average units sold by discount
- Net revenue per record by discount
- Price by category
- Discount and seasonal patterns

The analysis helps illustrate the relationship between discount levels, sales volume, and revenue performance.

### 2. Inventory Optimization

The inventory dashboard evaluates:

- Current inventory
- Target inventory
- Excess inventory
- Inventory reduction percentage
- Inventory value released
- Safety factor scenarios

Different safety factor scenarios are compared to understand how inventory requirements and potential inventory release change under different operating assumptions.

## Key Metrics

### Pricing Dashboard

- **Total Revenue:** 550.23M
- **Units Sold:** 10M
- **Inventory Level:** 20M
- **Potential Inventory Value Released:** 356.04M

### Inventory Optimization

- **Current Inventory:** 20M
- **Target Inventory:** 15.51M
- **Excess Inventory:** 6.42M
- **Inventory Reduction:** 32.00%

## Key Insights

- Average units sold increase as discounts move from 0% toward the 10% range, before leveling off.
- Net revenue per record decreases as discount levels increase.
- The pricing analysis shows that higher discounts can support sales volume while reducing revenue generated per record.
- Inventory optimization scenarios show that the selected safety factor materially affects target inventory levels.
- Lower safety factor scenarios result in lower target inventory and greater potential inventory reduction.
- The inventory model provides a way to evaluate the trade-off between inventory availability and working capital efficiency.

## Tools & Technologies

- Power BI
- DAX
- Microsoft Excel / CSV
- Data Modeling
- Data Visualization
- Business Intelligence
- Inventory Optimization
- Pricing Analysis

## Dashboard Screenshots

### Retail Pricing Dashboard

![Retail Optimization Dashboard](retail%20optimization.png)

### Inventory Optimization Dashboard

![Inventory Optimization Dashboard](Inventory%20optimization.png)

## Project Files

| File | Description |
|---|---|
| `Smart Retail Pricing Inventory Model.pbix` | Power BI dashboard and data model |
| `retail_store_inventory.csv` | Retail inventory dataset |
| `smart_retail_executive_summary.csv` | Executive-level retail summary data |
| `smart_retail_inventory_scenarios.csv` | Inventory optimization scenario data |
| `smart_retail_pricing_analysis.csv` | Pricing analysis data |
| `retail optimization.png` | Retail pricing dashboard screenshot |
| `Inventory optimization.png` | Inventory optimization dashboard screenshot |

## Conclusion

This project demonstrates how Power BI can transform retail pricing, sales, and inventory data into an interactive decision-support tool.

The solution combines technical analysis with business-focused insights to help decision-makers evaluate pricing strategies, identify excess inventory, and understand the potential financial impact of inventory optimization.
