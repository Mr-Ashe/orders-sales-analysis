# Orders Sales Analysis
Analysis of a 60-order e-commerce dataset across 5 countries (UK, France, Morocco, Germany, Spain) and 5 categories (Electronics, Fashion, Grocery, Beauty, Sports).
## Business Context
Acting as a junior data analyst, I was asked a broad question: "tell us what's happening with our sales." I broke this into
5 concrete, answerable questions.
## Questions Asked
1. Which category brings in the most revenue? 2. Which country is the strongest market?
3. Which category has the highest average order value?
4. Is there a monthly trend?
5. How concentrated is revenue among top customers?
## Key Findings
- **Electronics leads total revenue** ($4,570.73), ahead of Beauty ($3,900.96). Sports trails far behind ($594.30).
- **UK is the strongest market** by both total revenue ($4,706.67) and average order value ($294.17).
- **Grocery has the highest average order value** ($267.29) despite ranking last in total revenue -- fewer orders,
higher value each.
- **March showed a revenue dip** (-35% vs January), recovering
fully by April.
- **Top 10 customers = 40.6% of total revenue**, suggesting a
retention strategy for high-value customers.
- **Data gaps found:** Electronics has zero recorded revenue
in France; Sports is absent from Germany, Spain, and the UK. Worth verifying with the data source before treating as fact.
## Tools Used
- Python (pandas, matplotlib) for cleaning and analysis
- SQL (SQLite) for the same queries in a second language - Tableau Public for the interactive dashboard
## Limitations
- Small sample per country (5-16 orders)
- Only 4 months of data, no year attached -- cannot confirm true seasonality
- Some category-country combinations have zero data, which may reflect real market gaps or incomplete data collection
## Files
- `notebooks/Sales.ipynb` -- full analysis
- `data/orders.csv` -- raw data
- `sql/queries.sql` -- same questions in SQL
- `dashboard/` -- Tableau dashboard screenshot + link
