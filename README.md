# Sales Performance Analysis

Analysis of 1,246 sales orders (2010–2017) of a company selling 12 product categories in 45 countries: which products, markets, channels and periods generate the most profit, and how long orders take to ship.

**Tools:** Python (pandas, matplotlib, seaborn)

## Data
Three tables joined in pandas: `events.csv` (orders), `products.csv` (product categories), `countries.csv` (countries and regions).

## Approach
1. **Data cleaning:** missing values, data types, duplicates, anomalies, inconsistent channel names (`Online` / `online`).
2. **Merging** the three tables and calculating revenue, cost and profit.
3. **Analysis** by product category, country and region, sales channel, shipment duration, time, weekday and month.
4. **Conclusions and business recommendations.**

## Key findings
- Revenue ≈ **1.60 bn**, profit ≈ **474 m**, margin ≈ 30%.
- **Cosmetics, Office Supplies and Household** bring the most profit; Office Supplies and Meat have high revenue but the lowest margins, Clothes the highest margin (≈67%).
- **Europe generates ≈95% of profit**; the top-10 countries are close to each other, so no single market dominates.
- **Online and offline are almost equal** (49.7% vs. 50.3% of profit).
- Shipping takes ≈25 days on average, with **no clear link between shipping time and profit**.
- **Friday and Monday** are the most profitable days, Thursday the least.

## Files
| File | Content |
|---|---|
| `sales_performance_analysis.ipynb` | full analysis with charts, conclusions and recommendations |
