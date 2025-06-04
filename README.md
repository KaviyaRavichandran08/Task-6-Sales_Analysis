# Task-6-Sales_Analysis
Sales Trend Analysis using Aggregations

## Objective
Analyze monthly revenue and order volume from the `online_sales_data` table using SQL aggregate functions.

## Dataset:
- File: `online_sales_data.csv`
- Columns Used:
  - `order_id` (InvoiceNo)
  - `order_date` (InvoiceDate)
  - `amount` (TotalPrice)
  - `product_id` (StockCode)
    
## Key Concepts Applied:
- Extracted month and year using `STRFTIME('%m', order_date)` and `STRFTIME('%Y', order_date)`
- Used `SUM()` to calculate monthly revenue
- Used `COUNT(DISTINCT order_id)` to calculate monthly order volume
- Used `GROUP BY` and `ORDER BY` for aggregation and sorting
- Limited results using `LIMIT` keyword to find top-performing months

## Tools Used:
 **SQLite Online**
- **MS Excel** for preprocessing the dataset
