# Housing Data EDA

This analysis uses the **Melbourne Housing Dataset** (`dansbecker/melbourne-housing-snapshot`) from Kaggle.  

## Cleaning Steps
- Dropped all columns with nulls (e.g. `BuildingArea`, `YearBuilt`).

## Key Insights
- **Price vs Rooms**: More rooms generally lead to higher prices.
- **Region Analysis**: Houses in inner suburbs tend to be more expensive.
- **Top Suburbs**: Most sales occurred in Reservoir, Richmond, and Bentleigh.

## Visualizations
- Scatter plot: `Rooms` vs `Price`
- Bar chart: Average price by `Regionname`
- Histogram: Distribution of house prices
