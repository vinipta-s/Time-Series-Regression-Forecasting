# Time Series Regression Forecasting

In this project 6-month's of data on taxi orders at airports was cleaned and explored for patterns. A daily seasonal trend was observed. 

Models were fitted and evaluated with features and without features, aiming for a low RMSE (48 treshold). 

## Table of contents
<b>Part 1: Libraries</b>

<b>Part 2: EDA</b>
* data was stored as data_original and data
* data was explored; trends were noted
* 'num_orders' column values overwritten with sum of taxi orders by hour

<b>Part 3: Functions</b>
* RMSE function
* SMAPE function
* forecast function: takes actual and predictions as input, and returns the RSME, SMAPE and forecast bias, and returns as plot of the actual and predictions on the same graph for visual comparison. Also adds to the all_model_scores array.

<b>Part 4: Time Series Feature Engineering</b>
* create_features function
* feature created: lags (1-4) and rolling mean from 4th hour

<b>Part 5: Forecasting With Features</b>
* models: Linear Regressor, Random Forest Regressor, and LightBGM Regressor

<b>Part 6: Forcasting Without Features
* models: AR, and SARIMA

<b>Final Report</b>
