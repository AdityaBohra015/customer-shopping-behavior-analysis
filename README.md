# Customer Shopping Behavior Analysis

An end-to-end data analytics project analyzing customer purchasing patterns, product performance, discount usage, subscription behavior, and customer loyalty using Python, MySQL, Excel, and Tableau.

## Business Objective

Analyze customer shopping data to identify revenue patterns, understand purchasing behavior across customer segments, and generate insights to support promotional planning and customer retention strategies.

## Tools & Technologies

- **Python (Pandas):** Data cleaning, missing-value treatment, and feature engineering
- **MySQL:** SQL queries and business analysis
- **Excel:** Data inspection and cleaned data export
- **Tableau:** Interactive dashboards and visualizations

## Dataset Overview

- **Total records:** 3,900
- **Original columns:** 18
- **Missing review ratings:** 37, treated using category-level median imputation
- **Feature engineering:** Age groups and purchase-frequency segments

## Key Findings

| Metric | Result |
|---|---:|
| Total revenue | $233,081 |
| Average purchase spend | $59.76 |
| Average review rating | 3.75 |
| Clothing revenue | $104,264 |
| Clothing revenue share | 44.73% |
| Accessories revenue | $74,200 |
| Footwear revenue | $36,093 |
| Outerwear revenue | $18,524 |
| Male customer revenue share | 67.74% |
| Female customer revenue share | 32.26% |

## Business Insights

- **Clothing** was the leading product category, contributing 44.73% of total revenue.
- **Accessories** ranked second in revenue contribution.
- Male customers accounted for 67.74% of recorded revenue in the dataset.
- Subscription behavior, discount usage, and customer loyalty provide additional perspectives on shopping patterns.

## SQL Analysis

The SQL analysis explores:

- Revenue by gender and age group
- Discount usage and above-average spending
- Product review ratings
- Subscription status and purchasing behavior
- Products with high discount usage
- Customer loyalty segments
- Best-selling products within categories
- Repeat purchasing behavior

## Tableau Dashboards

**Dashboard 1 — Shopping Overview**
- Key performance indicators
- Revenue by product category
- Revenue by gender
- Customer age-group distribution

**Dashboard 2 — Customer & Product Insights**
- Subscription behavior
- Discount usage by product
- Customer loyalty segments
