# Marketing ROI Analysis: Optimizing Advertising Spend

## Project Overview
This project utilizes Simple Linear Regression (OLS) to analyze the impact of different advertising channels (TV, Radio, Social Media) on product sales. The goal is to identify the most effective channel for maximizing return on investment (ROI).

## Data
The analysis is based on `marketing_data.csv`, a dataset containing advertising budgets for TV, Radio, and Social Media, alongside corresponding sales figures.

## Methodology

1.  **Data Cleaning**: Missing values were handled by dropping relevant rows.
2.  **Exploratory Data Analysis (EDA)**: Scatter plots and correlation analysis were used to understand relationships between advertising channels and sales.
3.  **Variable Selection**: TV advertising was identified as the strongest predictor of sales.
4.  **OLS Regression**: A simple linear regression model was built using TV advertising budget to predict sales.
5.  **Model Diagnostics**: Assumptions of linearity, normality of residuals, and homoscedasticity were validated.

## Key Findings

*   **Strongest Predictor**: TV advertising shows an exceptionally strong positive linear relationship with sales (correlation = 0.9995).
*   **Model Performance**: The OLS model (Sales = 3.5615 × TV - 0.1325) achieved an R-squared of 0.999, indicating that 99.9% of the variation in sales is explained by TV spend.
*   **ROI**: For every $1,000 increase in TV advertising, sales are predicted to increase by approximately $3,561.50.
*   **Model Validity**: All critical OLS assumptions were met, confirming the model's reliability.

## Business Recommendation

Prioritize TV advertising as the primary channel for budget allocation due to its exceptionally high and statistically significant return on investment. Radio can serve as a secondary channel, while Social Media advertising should be re-evaluated or receive lower priority until further analysis demonstrates a more consistent impact on sales.
