# Supermarket Sales Intelligence Dashboard

An interactive Power BI report for exploring supermarket sales, revenue, transactions, customer ratings, product lines, branches, cities, payment methods, and hourly sales.

## Project files

- `dashboard/Supermarket Sales Intelligence.pbix` — Power BI report.
- `data/supermarket_sales.csv` — original source dataset.
- `data/supermarket_sales_cleaned_repaired.csv` — repaired dataset with valid dates and derived columns.
- `dax/PowerBI_DAX_Measures.txt` — sample DAX measures.
- `power-query/PowerBI_PowerQuery_M.txt` — Power Query M import example.
- `screenshots/` — place a screenshot of your finished report here.

## Key figures

- Total sales: **322,966.75**
- Gross income: **15,379.37**
- Transactions: **1,000**
- Units sold: **5,510**
- Average customer rating: approximately **6.97**

## Dashboard views

- KPI cards for sales, gross income, transactions, units sold, and average rating.
- Sales by product line, city, branch, payment method, hour, and customer type.
- Date and category slicers for interactive filtering.

## Tools

- Microsoft Power BI Desktop
- Power Query
- DAX
- CSV / tabular data preparation

## Data validation

The repaired CSV contains 1,000 rows, zero blank dates, and total sales of 322,966.75. Monthly sales in the repaired file:
- January: 116,291.87
- February: 97,219.37
- March: 109,455.51

Branch sales:
- Branch A: 106,200.37
- Branch B: 106,197.67
- Branch C: 110,568.71

## Use the report

1. Download the repository.
2. Open the `.pbix` file in Power BI Desktop.
3. If Power BI prompts for a data source, point it to `data/supermarket_sales_cleaned_repaired.csv`.
4. Confirm the `Date` field is a Date type and `Total` is numeric.
5. Refresh the report.

> Note: The PBIX may store a local file path from the author's computer. The dataset is included, but another computer may need its source path updated.

## Suggested resume entry

**Supermarket Sales Intelligence Dashboard | Power BI, DAX, Power Query**
- Built an interactive sales dashboard with five KPI cards and six analytical visuals.
- Analyzed sales by product line, city, branch, payment method, hour, and customer type.
- Prepared and validated 1,000 transaction records, with total sales of 322,966.75.
