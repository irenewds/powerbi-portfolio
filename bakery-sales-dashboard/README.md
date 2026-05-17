# Bakery Sales Analytics Dashboard

## Project Goal
Help bakery owners identify peak sales hours, best-selling products, and weekday vs weekend buying patterns — turning 980 transactions into actionable daily operation insights across 3 interactive dashboard pages.

## Dataset
| Field | Detail |
|---|---|
| Source | bakery_sales_dataset.csv |
| Rows | 20,507 (line items) |
| Unique Transactions | 9,465 |
| Unique Products | 94 |
| Period | January – December 2017 |

## DAX Measures

| Measure | Formula Summary |
|---|---|
| Total Transactions | DISTINCTCOUNT(TransactionNo) |
| Total Items Sold | COUNTROWS(table) |
| Avg Items per Transaction | DIVIDE(Items, Transactions) |
| Top Product | MAXX + TOPN |
| Top Product Count | MAXX + TOPN |
| Transactions This Month | CALCULATE + DATESMTD |
| Weekend Transaction Share % | DIVIDE + CALCULATE |
| Morning Share % | DIVIDE + CALCULATE |
| % of Total Items | DIVIDE + ALL |

## Dashboard Preview
📄 [View Dashboard PDF](./Bakery_Sales_Dashboard.pdf)