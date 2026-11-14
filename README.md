# PigulkaBio: Sales and Profitability Analysis (2019–2021) 

## Client Background

PigulkaBio is a fictional pharmaceutical company serving domestic and export markets through distributors and other business customers. Its portfolio includes diagnostics and reagents, immunobiologics, injectables, lyophilized products, antiseptics, and supplements. The company also generates a small share of revenue from services.

This case study covers 2019–2021 and uses a synthetic dataset based on real transactions. The data includes sales, returns, and financial discount adjustments, supporting a comparative analysis of the company’s commercial performance over the three-year period.

## Executive summary

2021 KPIs (relative to 2020): net revenue – $5.38 million (+16.0%); product gross profit – $2.22 million (+4.2%); product gross margin – 41.4% (-4.7 percentage points).

### 1. Revenue Growth and Peak Performance

- In 2021, net revenue reached $5.38 million, marking the highest figure during the analyzed period. In 2020, it amounted to $4.64 million, compared to $4.76 million in 2019.
- Following a 2.5% decline in 2020, revenue recovered, showing an increase of 16.0%—or $740,000. Compared to 2019, revenue grew by 13.1%, or $624,000.
- Average quarterly revenue in 2021 was $1.35 million, exceeding the average for the entire period ($1.23 million). For comparison, this figure was $1.19 million in 2019 and $1.16 million in 2020.

### Quarterly Patterns and Key Changes

- Across all three years, Q1 accounted for the smallest share of annual revenue, while Q4 accounted for the largest.
- In 2021, the concentration of revenue toward the end of the year intensified. Q4 accounted for $2.16 million—or 40.1% of annual revenue—compared to 29.9% in 2019 and 30% in 2020. Q1 2021 generated $647,000 (12%), marking the quarter with the lowest revenue for the entire period.

### Key Takeaways and Recommendations

- The recovery in revenue was accompanied by an increased concentration in Q4. When planning for the next period, it is necessary to assess the likelihood that the elevated sales levels seen at the end of 2021 will recur.
- Conduct a more detailed analysis of the customers and products that drove the results for Q1 and Q4. Use these findings to refine the quarterly sales and shipment plan. 

## ERD

The dataset consists of: Sales (3,560 transaction lines, including sales, returns, and discounts), Products (a catalog comprising 34 products and 5 types of services), SKUs (101 product variants), and Customers (a directory of 43 clients). 

The relationships between the tables are illustrated in the ERD visualization.

## Insights and Deep-Dive
All metrics in the Deep-Dive section are calculated based on products only; all service-related transactions are excluded. The primary comparison is between 2021 and 2020.

### Sales and profitability trends

#### Revenue and Gross Profit Recovery

- Product revenue grew by 16%, reaching $5.37 million. Gross profit increased by 4.2%, rising from $2.13 million to $2.22 million. The growth in sales was accompanied by a less pronounced increase in gross profit.
- When comparing 2021 to 2019, product revenue increased by 13.1%, while gross profit remained 8.9% lower. The recovery in revenue did not restore gross profit to its initial level.

#### Gross Margin Trend

- Gross margin declined consistently over the three-year period: 51.4% in 2019, 46.1% in 2020, and 41.4% in 2021—representing year-over-year decreases of 5.3 percentage points and 4.7 percentage points, respectively.
  
#### Quarterly Contributions

- The trends for revenue and gross profit diverged in certain quarters. In Q2 2021, product revenue increased by $39,000, while gross profit decreased by $90,000 compared to the same quarter in 2020.
- Following a decline in revenue of $297,000 and in gross profit of $240,000 in Q1, the second half of the year bolstered the annual performance. Q4 delivered the most significant growth, contributing $769,000 in revenue and $283,000 in gross profit (year-over-year increases). These figures exceeded the net annual growth for both metrics, offsetting the declines seen in other quarters.

### Products and Categories

#### Best and Worst Performers

- Diagnostic_09 remained the leader in terms of revenue, generating $1.52 million in revenue and $959,000 in gross profit. Other top performers by revenue included Lyophilized_01 ($966,000) and Biologic_03 ($420,000).
- Lyophilized_01 saw the largest revenue increase, up by $636,000. Other products that contributed positively to the results were Injectable_06 (+$235,000), Lyophilized_03 (+$203,000), and Biologic_01 (+$199,000).
- The most significant revenue declines were recorded for Diagnostic_07 (-$333,000) and Diagnostic_09 (-$263,000). Despite this drop in sales, the leading product (Diagnostic_09) managed to retain its top position. 

#### Product Trends, 2019–2021

- The Diagnostics & Reagents category saw a significant decline in its share of product revenue: from 60.7% in 2019 to 57.2% in 2020 and 35.9% in 2021. Over the last year, revenue for this category fell by $723,000, and gross profit decreased by $407,000.
- The Lyophilized category emerged as the primary driver of growth. Its share rose from 2.5% in 2019 to 9.6% in 2020 and 24.7% in 2021. Compared to 2020, it contributed an additional $883,000 in revenue and $294,000 in gross profit.
- Dependence on the leading product has decreased. The share of Diagnostic_09 in product revenue declined from 53.2% in 2019 to 38.6% in 2020, settling at 28.4% in 2021.

#### Product Mix and Margin


