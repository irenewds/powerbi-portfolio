# Marketing Campaign Analytics Dashboard

## Project Goal
Help marketing teams monitor campaign ROI, conversion trends, and
top-performing channels — enabling faster budget decisions across
200,000 records and multiple regions.


## Dataset
| Field | Detail |
|---|---|
| Source | marketing_campaign_dataset.csv |
| Rows | 200,000 |
| Columns | 16 |
| Period | 2021 (full year) |

## DAX Measures

| Measure | Formula Summary |
|---|---|
| Total Campaigns | COUNTROWS |
| Total Clicks | SUM |
| Total Impressions | SUM |
| Total Acquisition Cost | SUM |
| Avg ROI | AVERAGE |
| Avg Conversion Rate | AVERAGE |
| Avg CTR | AVERAGE |
| Avg Engagement Score | AVERAGE |
| Avg Acquisition Cost | AVERAGE |
| Avg CPC | AVERAGE |
| Cost per Conversion | DIVIDE(Total Cost, Clicks × Conv Rate) |


## Dashboard Preview
📄 [View Dashboard PDF](./Marketing_Campaign_Dashboard.pdf)