# Supermarket Sales Analysis Using Microsoft Excel

## Project Overview

This project focuses on analyzing supermarket sales data using Microsoft Excel. The dataset contains transaction-level information about product categories, sales amounts, customer types, payment methods, branches, dates, and customer ratings.

The objective is to organize sales data, summarize business performance, and identify patterns that can support retail decision-making.


## Business Problem

Retail businesses need to understand which product lines generate sales, how performance varies across branches and cities, what payment methods customers use, and when transactions occur. This project uses Excel-based analysis to explore these questions and turn transaction data into understandable business insights.

## Dataset Overview

The dataset includes supermarket transactions from **January to March 2019** and contains fields such as:

| Column | Description |
|---|---|
| `Invoice ID` | Unique transaction identifier |
| `Branch` | Store branch code |
| `City` | City where the transaction occurred |
| `Customer type` | Member or Normal customer |
| `Gender` | Customer gender recorded in the dataset |
| `Product line` | Product category purchased |
| `Unit price` | Price per item |
| `Quantity` | Number of units purchased |
| `Tax 5%` | Tax amount for the transaction |
| `Total` | Total transaction amount including tax |
| `Date` | Transaction date |
| `Time` | Transaction time |
| `Payment` | Payment method used |
| `cogs` | Cost of goods sold |
| `gross margin percentage` | Gross margin percentage field in the source data |
| `gross income` | Gross income recorded for the transaction |
| `Rating` | Customer rating |
| `Month` | Month derived from the transaction date |
| `Hour` | Hour derived from transaction time |
| `Time Slot` | Time-of-day grouping, such as Morning, Afternoon, or Evening |
| `Total Profit (Gross Income)` | Additional field containing gross income values |

The source file includes calculated or derived fields such as `Month`, `Hour`, `Time Slot`, and `Total Profit (Gross Income)`. Check formulas and definitions in the workbook before treating these as independently calculated metrics.

## Tools Used

- **Microsoft Excel**
- Sorting and filtering
- Excel formulas and calculated columns, where used
- PivotTables and PivotCharts, where used
- Charts and KPI summaries, where included in the workbook

## Analysis Areas

The dataset supports analysis of:

- **Sales performance:** total sales, transaction count, and quantity sold
- **Product line performance:** compare sales and gross income across product categories
- **Branch and city performance:** compare results across store locations
- **Customer analysis:** compare Member and Normal customers and explore recorded customer demographics
- **Payment analysis:** review the use of Cash, Credit card, and Ewallet
- **Time-based trends:** examine sales by date, month, hour, and time slot
- **Customer satisfaction:** compare customer ratings across product lines, branches, or other relevant groups
- **Profitability:** examine gross income and cost-of-goods-sold fields

These are analysis opportunities supported by the dataset; specific conclusions should be added only after validating the results in the Excel workbook.

## Key Questions

1. Which product lines contribute the most to total sales?
2. Which branch or city records the highest sales?
3. How do sales differ between Member and Normal customers?
4. Which payment methods are most frequently used?
5. At what times of day are transactions most common?
6. How do customer ratings vary across product lines?
7. Which categories or branches generate the most gross income?
8. How do sales and gross income change over the January–March period?

## Suggested Excel Workflow

1. Import the dataset into Excel and format it as a table.
2. Check for blank cells, duplicate invoice IDs, inconsistent category labels, and incorrect data types.
3. Ensure currency and numeric fields are stored as numbers rather than text.
4. Validate date and time fields and review the definitions of derived columns.
5. Use PivotTables to summarize sales, quantity, gross income, and transaction counts.
6. Create PivotCharts or standard charts to compare categories, locations, payment methods, and time periods.
7. Add slicers or filters if the workbook uses an interactive dashboard.
8. Verify that totals in charts and KPI cards reconcile with the source data.

## Suggested Repository Structure

```text
Supermarket-Sales-Excel-Analysis/
├── README.md
├── supermarket_sales.xlsx
└── images/
    └── dashboard-screenshot.png
```

Adjust the file names to match the files you upload. Add a dashboard screenshot to the `images` folder if you want the GitHub README to show a preview of your Excel work.

## How to Use

1. Download or clone this repository.
2. Open the `.xlsx` workbook in Microsoft Excel or a compatible spreadsheet application.
3. Review the raw data and any data-cleaning steps.
4. Explore the PivotTables, charts, filters, and dashboard sheets included in the workbook.
5. Use the workbook's filters or slicers, if available, to explore different branches, product lines, customer types, and time periods.

## Notes and Limitations

- The dataset covers a limited period, January–March 2019; findings should not automatically be generalized to other periods or retailers.
- The `Total` field represents transaction total including the listed tax, while `gross income` and `cogs` represent separate financial measures in the source data.
- Confirm the meaning and formula of each derived field before using it in business reporting.
- Do not claim specific sales leaders, trends, or business outcomes unless they are verified from the completed workbook.
- If the dataset license has restrictions, follow them before redistributing the raw data publicly.

## Future Improvements

- Add a concise executive dashboard with clearly defined KPIs.
- Include slicers for branch, city, product line, customer type, and month.
- Standardize number formats, column names, and metric definitions.
- Document important findings and recommendations based on validated results.
- Add screenshots of the dashboard and selected PivotTables to the repository.



## Author

**Rushikesh Palade**
- **GitHub:**  https://github.com/rushikeshpalde02-zip
- **LinkedIn:** https://www.linkedin.com/in/RushikeshPalade
