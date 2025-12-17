# Superstore Sales Analysis

## Objective
Analyze sales performance to identify revenue declines, customer behavior patterns,
sales outliers, and regional differences, and translate findings into actionable business recommendations.


## Dataset
Superstore Sales Dataset covering sales transactions from 2015–2018.

## Business Questions
1. What factors explain the decline in sales?
2. Which products or categories are underperforming?
3. Which customer segments are buying less?
4. Are there relevant temporal trends (monthly, yearly)?
5. Which regions show the greatest impact?
6. Where are the sales outliers and why do they occur?
7. What strategic recommendations can be made?

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
![Yearly Sales Trend](3.figures/yearly_sales_trend.png)

### Monthly Seasonality
![Monthly Seasonality](3.figures/monthly_seasonality.png)

### Sales by Category
![Sales by Category](3.figures/sales_by_category.png)

### Sales by Segment
![Sales by Segment](3.figures/sales_by_segment.png)

### Sales Outliers Distribution
![Sales Outliers](3.figures/box_plot_outliers.png)


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
