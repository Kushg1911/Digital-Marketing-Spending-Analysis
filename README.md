# Digital-Marketing-Spending-Analysis

## Overview

This project analyzes marketing spending data to evaluate the effectiveness of marketing campaigns and derive actionable insights. The analysis is conducted using SQL queries on a PostgreSQL database. I aim to calculate key marketing metrics and identify patterns that can help improve business results.

## Problem Statement

Marketing teams need to assess the performance of their campaigns to make informed decisions. This project addresses the following questions:

- How effective are our marketing campaigns?
- What is the return on investment (ROMI) for each campaign?
- Which campaigns are most cost-efficient?
- Are there any trends or patterns in campaign performance?

## Tools Used

- Database: PostgreSQL
- Analysis and Reporting: SQL Queries

## Key Metrics and Functions Used

1. **Return on Marketing Investment (ROMI):**
   - Formula: `(Total Earnings - Marketing Cost) / Marketing Cost`

2. **Click-through Rate (CTR):**
   - Formula: `(Clicks / Impressions)`

3. **Conversion Rates (Conversion 1 & Conversion 2):**
   - Formula (Conversion 1): `(Leads / Clicks)`
   - Formula (Conversion 2): `(Orders / Leads)`

4. **Average Order Value (AOV):**
   - Formula: `(Revenue / Number of Orders)`

5. **Cost per Click (CPC):**
   - Formula: `(Marketing Spending / Clicks)`

6. **Cost per Lead (CPL):**
   - Formula: `(Marketing Spending / Leads)`

7. **Customer Acquisition Cost (CAC):**
   - Formula: `(Marketing Spending / Orders)`

## Insights and Analysis

- **Overall ROMI**: ROMI is 0.4, indicating a positive return on investment for the marketing efforts.

- **ROMI for "instagram_blogger" Campaign**: During the period from 15th Feb to 25th Feb, the ROMI was 0.38, suggesting profitability during that specific timeframe.

- **Weekend vs. Weekdays**: The average revenue spent on weekends (Saturday and Sunday) is INR 132,593.58, while on weekdays (Monday to Friday), it is INR 141,914.20, allowing for performance comparison.

- **Campaign with Worst Loss**: Campaign ID 544756 showed the worst loss in a single day, indicating the need for optimization.

- **Total Spending on Facebook Campaigns with Negative ROMI**: INR 9,280,237.56. This information helps evaluate the effectiveness of Facebook campaigns and allocation of resources.

## Usage

This project provides valuable insights for marketing teams to make data-driven decisions. SQL queries used for analysis are provided in the project's SQL files.

Feel free to contribute to this project by improving the analysis, adding more metrics, or sharing your insights.
