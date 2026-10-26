# Beyond the First Purchase
### Customer Loyalty & Retention Analysis Using Python

## Project Overview

This project explores customer purchasing behavior using the UCI Online Retail dataset.

The analysis focuses on understanding repeat purchases, identifying valuable customer segments, and examining customer retention over time.

The goal is to translate transaction data into actionable business insights that can support customer engagement and retention strategies.

## Business Objectives

- Analyze customer purchasing behavior.
- Calculate repeat purchase rates.
- Compare one-time and repeat customers.
- Segment customers using Recency, Frequency, and Monetary (RFM) analysis.
- Measure monthly customer retention through cohort analysis.
- Develop data-driven business recommendations.

## Tools & Technologies

- **Python:** Data analysis and processing
- **Pandas:** Data cleaning and manipulation
- **Matplotlib:** Data visualization
- **Seaborn:** Cohort retention heatmap
- **Jupyter Notebook:** Analysis and documentation

## Key Results

| Metric | Result |
|---|---:|
| Total Customers | 4,338 |
| Repeat Customers | 2,845 |
| One-Time Customers | 1,493 |
| Repeat Purchase Rate | 65.58% |
| Champions | 462 |
| Champions' Share of Recorded Spending | 49.03% |

## Key Findings

**1. Repeat Purchasing Behavior**

Approximately 65.58% of customers made purchases on more than one distinct invoice during the observation period.

**2. High-Value Customers**

Champions represent 10.65% of customers and account for 49.03% of recorded positive purchase spending.

**3. Customer Retention**

Most customer cohorts had second-month retention rates below 25%, highlighting an opportunity to test strategies that encourage customers to return after their first observed purchase.

## Data Visualizations

### 1. Customer Retention by Cohort

The heatmap shows the percentage of customers who returned
to make purchases in subsequent months after their first
observed purchase.

![Customer Retention Heatmap](customer_retention_heatmap.png)

### 2. Customer Share vs. Revenue Share

This chart compares each RFM segment's percentage of
customers with its contribution to total recorded spending.

![Customer Share vs Revenue Share](customer_vs_revenue_share.png)
**4. Customer Segmentation**

RFM analysis identified six customer groups, providing a framework for exploring targeted engagement and retention strategies.
