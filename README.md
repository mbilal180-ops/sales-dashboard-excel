# sales-dashboard-excel
Interactive Excel Sales Dashboard with Power Query
# Sales Performance Dashboard — Excel

## Project Overview
An interactive sales analysis dashboard built in Microsoft Excel
using Power Query for data cleaning and Pivot Tables for analysis.
Covers global sales data from 2003 to 2005 across 7 product lines
and 4 territories.

## Dataset
- Source: Sample Sales Dataset (CSV)
- Rows: 2,823 transactions
- Period: 2003–2005
- Columns after cleaning: 18

## Tools Used
- Microsoft Excel
- Power Query (data cleaning)
- Pivot Tables (data aggregation)
- Excel Charts (visualization)

## Data Cleaning Steps
- Removed 9 irrelevant columns
- Handled null SALES values using QUANTITYORDERED x PRICEEACH
- Standardized ORDERDATE format and flagged unknown dates
- Added calculated columns: Discount %, Month-Year, Contact Name

## Dashboard Features
- 4 KPI Cards: Total Revenue, Total Orders, Top Territory, Best Product
- Revenue by Product Line (horizontal bar chart)
- Monthly Revenue Trend 2003-2005 (line chart)
- Revenue by Territory (horizontal bar chart)
- Top 10 Customers by Revenue (horizontal bar chart)
- 3 Interactive Slicers: Year, Product Line, Territory

## Key Insights
- Total Revenue: $9,944,357 across 3 years
- Classic Cars is the top product line at $3.85M (38.8% of revenue)
- EMEA is the top territory at $4.94M (49.7% of revenue)
- Euro Shopping Channel is the top customer at $903,906
- November consistently shows the highest monthly sales in 2003 and 2004
- Revenue grew from $3.48M in 2003 to $4.69M in 2004 (34.7% growth)

## Files
- Sales_Analysis_Bilal.xlsx — Main dashboard file
- sales_data_sample.csv — Raw data source
- dashboard_preview.png — Dashboard screenshot

## Notes
- KPI cards display overall totals independent of slicer selection
- Monthly trend chart uses numeric month axis due to pivot hierarchy
