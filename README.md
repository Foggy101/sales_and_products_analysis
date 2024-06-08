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
This part is dedicated to creating a review classification neural network. The aim of the model is distinguishing between positive/neutral/negative text reviews left by customers. The code includes a way for users to input a custom comment and make the model evaluate it. Keep in mind that the comment has to be in portuguese.<br><br>
<strong>EXAMPLE IMAGE: USER INPUT PREDICTION</strong><br>
<img src="images/review_sentiment_prediction.jpg">

<hr>
<h2>REVIEW ANALYTICS</h2>

n about numerical product ratings with text comments. I hear that modern algorithms can read and understand these reviews. Let’s implement the functionality for classifying positive/negative comments and consolidate the analytics. I’m interested in the correlation of text comments with a numerical rating (1-5), products with the best/worst reviews, sellers who only collect negative feedback.

<hr>
<h2>SALES AND PRODUCTS DASHBOARD</h2>
