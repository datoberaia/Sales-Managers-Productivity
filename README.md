# Sales Managers Productivity Dashboard

An interactive Power BI dashboard that compares sales managers by lead volume and profit, to show who converts leads into profit most effectively.

![Dashboard preview](sales_managers_productivity.png)

## Key Insight

**Manager 6 earns the most profit ($394K) from fewer leads than Manager 3.** Lead volume alone does not predict profit: Manager 3 handled the most leads (949) but ranks third in profit, while Managers 6 and 10 earn more from fewer leads.

## Overview

The dashboard analyses 12 sales managers across 6,955 leads and $3.03M in total profit. It answers three questions:

- Who generates the most profit?
- Is profit driven by lead volume or by lead quality?
- How efficient is each manager's work (profit per lead, margin, markup)?

## KPIs

| KPI | Value | Definition |
|---|---|---|
| Leads | 6,955 | Total number of leads |
| Total Profit | $3.03M | Sum of profit |
| Profit per Lead | $436 | Total Profit / Leads |
| Top Profit | Manager 6 | Manager with the highest total profit |
| Avg Margin | 43.20% | Profit / Revenue |
| Avg Markup | 77.89% | Profit / Cost (COGS) |

## Visuals

- **Quantity of Leads by Sales Manager** (bar chart), sorted by profit so lead volume can be compared against results.
- **Total Profit by Sales Manager** (column chart) with data labels.
- **KPI cards** for the six headline metrics.
- **Dynamic subtitle** that highlights the main finding.

## Tools

- Power BI Desktop
- DAX (measures such as `Profit per Lead` and `Top Profit`)


## How to Use

1. Download the `.pbix` file.
2. Open it in Power BI Desktop (free from Microsoft).
3. Explore the visuals and measures.
