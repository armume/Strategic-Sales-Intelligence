# Superstore Sales Analysis

## Objective
Analyze sales performance to identify revenue declines, customer behavior patterns,
sales outliers, and regional differences, and translate findings into actionable business recommendations.


## Dataset
Superstore Sales Dataset covering sales transactions from 2015–2018.

## Business Questions
1. What factors explain the decline in sales?
Sales declined by -5.3% in 2016, mainly due to a temporary contraction; no category collapsed completely. The decline in sales suggests external or general market factors rather than an internal product situation.

2. Which products or categories are underperforming?
Office furniture and supplies generate less revenue compared to technology and record fewer high-value transactions. These categories depend on volume rather than value, which limits revenue.
  ### Sales by Category
  <img src="retail-sales-analysis/3. figures/sales_by_category.png" width="500">

3. Which customer segments are buying less?
Home Office contributes the least to total revenue. Revenue concentration in Consumer increases dependency risk and reduces predictability.
  ### Sales by Segment
  <img src="retail-sales-analysis/3. figures/sales_by_segment.png" width="500">

4.Are there relevant temporal trends (monthly, yearly)?
Sales show strong seasonality in the second quarter, reaching their peaks during the third and fourth quarters. This trend is evident every year. Seasonal planning is essential for product and marketing optimization.

  ### Yearly Sales Trend
  <img src="retail-sales-analysis/3. figures/yearly_sales_trend.png" width="500">
  
  ### Monthly Seasonality
  <img src="retail-sales-analysis/3. figures/monthly_seasonality.png" width="500">

5. Which regions show the greatest impact?
The West and East regions generate higher sales but also higher volatility.

6. Where are the sales outliers and why do they occur?

   
7. What strategic recommendations can be made?
  -Diversify revenue away from consumer dependency.
  -Strengthen corporate segment for stable growth.
  -Treat high-value outliers as key accounts.
  -Align campaigns with seasonal peaks.

## Analysis Overview
The project follows an end-to-end analytical workflow:
- Data cleaning and feature engineering
- Exploratory Data Analysis (EDA)
- Temporal trend and seasonality analysis
- Category, segment, and regional performance evaluation
- Outlier detection using IQR and Z-score methods
- Translation of insights into business recommendations

## Key Insights
- Sales declined in 2016 but recovered strongly in subsequent years  
- Technology is the top-performing category but relies heavily on high-value transactions
- Consumer dominates revenue, increasing dependency risk
- Corporate segment shows consistent growth potential
- Sales present strong seasonality, especially in Q3 and Q4

## Visual Insights
### Yearly Sales Trend
<img src="retail-sales-analysis/3. figures/yearly_sales_trend.png" width="500">

### Monthly Seasonality
<img src="retail-sales-analysis/3. figures/monthly_seasonality.png" width="500">



### Sales Outliers Distribution
<img src="retail-sales-analysis/3. figures/box_plot_outliers.png" width="500">





## Business Recommendations
- Strengthen the Corporate segment to increase predictable revenue
- Reduce dependency on Consumer sales through diversification
- Leverage seasonality for inventory and campaign planning
- Treat high-value outliers as strategic clients rather than anomalies

## Tools
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
