# SALES AND PRODUCTS ANALYSIS
Python and PowerBI analysis of the Brazilian E-Commerce Public Dataset by Olist.

The project is divided into 4 parts:<br>
• [Demand forecasting models](https://github.com/Foggy101/sales_and_products_analysis/blob/main/demand_forecasting.ipynb) (ARIMA and random forest) in Python<br>
• [Review sentiment analysis](https://github.com/Foggy101/sales_and_products_analysis/blob/main/review_semantics_prediction_model.ipynb) (neural network) in Python<br>
• [Review analytics](https://github.com/Foggy101/sales_and_products_analysis/blob/main/review_semantics_review_analytics.ipynb) in Python<br>
• [Sales and products dashboard](https://github.com/Foggy101/sales_and_products_analysis/tree/main/dashboard_photos) in PowerBI

<hr>
<h2>DEMAND FORECASTING</h2>
The main goal of this part is to implement a demand forecasting system for a short-term period (14 days) 7 days from the last date. The forecasts would then be used to optimize inventory levels - ensuring enough stock to meet customer demand without overstocking - and thus reducing stocking spend.<br><br>
After performing time series decomposition, two models are built - SARIMA and random forest. They both can be used for category and product forecasts, depending on the selected setting. Both models yield similar forecasts and the default recommended approach is to take both results and average them for the final forecast.<br><br>
<strong>EXAMPLE IMAGE: TIME SERIES DECOMPOSITION</strong><br>
<img src="images/demand_decomposition.jpg">

<hr>
<h2>REVIEW SENTIMENT ANALYSIS</h2>

<hr>
<h2>REVIEW ANALYTICS</h2>

<hr>
<h2>SALES AND PRODUCTS DASHBOARD</h2>
