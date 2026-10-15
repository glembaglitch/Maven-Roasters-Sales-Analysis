# Maven Roasters Sales Analysis

An Excel dashboard for exploring Maven Roasters sales from January through June 2023 across Astoria, Hell's Kitchen, and Lower Manhattan.

## Project files

- `Dashboard/dashboard.xlsx` - Interactive Excel dashboard with PivotTables and slicers.
- `Raw_data/Coffee Shop Sales.xlsx` - Source transaction data.

## Key Features

* **Interactive Dynamic Slicers:** Filter the entire dashboard dynamically by date range, region, category, or business segment.
* **KPI Scorecards:** Top-level summary cards displaying core metrics (e.g., Total Revenue, Net Profit, Conversion Rates, Volume) alongside targets and percentage variances.
* **Trend Analysis Charts:** Visual representations of performance over time (Monthly, Quarterly, YoY).
* **Breakdown & Distribution Analysis:** Bar and pie/donut charts detailing top-performing segments, product categories, or geographical areas.
* **Automated Data Processing:** Utilizes Excel Formulas (`XLOOKUP`, `SUMIFS`, `INDEX/MATCH`) and Pivot Tables for dynamic updates.

## What the dashboard explores

- Sales trends over time
- Busiest days of the week
- Popular hours by store location
- Product performance by category, type, and detail, including units sold and revenue

## How to use

Open `Dashboard/dashboard.xlsx` in Excel. Use the product slicers to filter the PivotTables and dashboard views. If the source data changes, refresh the PivotTables in Excel.

## Data notes

The source contains 149,116 transaction records dated January 1 through June 30, 2023. Revenue is calculated as transaction quantity multiplied by unit price. It represents sales revenue, not profit; the source does not include product costs.
