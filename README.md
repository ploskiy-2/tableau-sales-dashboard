# Sales Performance Dashboard

A Tableau dashboard built to help sales managers and executives analyze year-over-year sales performance and trends.

This is a pet project made by following this tutorial: https://www.youtube.com/watch?v=dahrmqT5GD4

## Sales Dashboard
- **KPI Overview**: total sales, profit, and quantity (current vs. previous year)
- **Sales Trends**: monthly KPI trends with highest/lowest months highlighted
- **Product Subcategory Comparison**: sales vs. profit by subcategory, year-over-year
- **Weekly Trends**: weekly sales & profit vs. average, with above/below average weeks highlighted

## Features
- Year selector for exploring historical data
- Interactive charts for filtering
- Filters by product (category, subcategory) and location (region, state, city)

## Tools
Tableau

## Data
Sample sales dataset used in the tutorial above.

## Files
- `dashboard/KPI_Sales.twbx` – packaged workbook (includes data, opens directly in Tableau Desktop or Tableau Reader)
- `dashboard/KPI_Sales.twb` – workbook only (requires the data source in `data/` to be connected manually)
- `data/` – source data
- `images/` – dashboard screenshot

## How to run
- **Easiest**: open `KPI_Sales.twbx` in Tableau Desktop or the free Tableau Reader — data is bundled inside, no setup needed.
- **Alternative**: open `KPI_Sales.twb` in Tableau Desktop and point it to the data files in the `data/` folder if the connection doesn't resolve automatically.