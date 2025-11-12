# World-Population

Goal:
To analyze world population trends from 1970–2022 and predict future population growth using machine learning models
GPF


Dataset:
Contains population data for each country (1970–2022)
Includes: population count, continent, area, density, growth rate, and share of world population
GPF


Steps Followed:

Data Cleaning:
Converted wide-year format into a long format (one “Year” column).
Handled missing values.
Prepared features such as lagged population (Pop_lag1) for modeling
GPF

Exploratory Analysis:
Used Power BI to visualize trends and insights.

Example findings:
The most populated countries differ from those with the highest population density (e.g., China vs. Singapore).
Africa showed the highest growth rate over time 


Modeling:
Built a Linear Regression model using lagged population and growth features.
Training: Data ≤ 2015
Validation: Data ≥ 2020
Evaluation metrics: R², MAE, MAPE


Result: Linear regression achieved the best accuracy for predicting population trends

Output:
A Power BI dashboard showing population growth, density, and model forecasts.
Clear insight into demographic trends useful for policy or business forecasting.
