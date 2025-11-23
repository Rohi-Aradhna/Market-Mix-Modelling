This project builds a Market Mix Model (MMM) for an e-commerce company selling camera accessories, gaming products, and home audio. Using one year of sales, pricing, discount, and marketing spend data, the goal is to understand what drives weekly revenue and recommend a better marketing budget for the next year.

Steps involved:

1. Data Preparation

Cleaned and merged all order-level datasets

Fixed missing values and standardized dates

Converted daily data into weekly time-series

Added discount bands, holidays/paydays, and NPS features

2. Feature Engineering

Created SMA/EMA moving averages

Built ad-stocked marketing variables to capture delayed effects

Added lagged features and seasonality patterns

Produced a modeling-ready dataset

3. Exploratory Analysis

Checked trends and correlations

Compared sales across discount levels

Studied the impact of different marketing channels

Identified possible non-linear effects

4. Model Building

Built and compared multiple models:

Linear regression

Log–Log elasticity model

Koyck lag model

Generalized Additive Model (GAM)

GAM gave the most realistic results.

5. Model Evaluation

Used cross-validation (5-fold)

Evaluated R², RMSE, and residual patterns

Compared response curves and elasticities

6. Budget Optimization

Ran simulations to test how shifting spend affects revenue

Explored both constrained and unconstrained scenarios

Identified 10–20% as the most effective discount range

Flagged low-impact marketing channels

Results:

Clear understanding of which factors drive sales
A GAM-based MMM that predicts weekly revenue
Budget recommendations for next year
Insights on discount effectiveness and channel performance
