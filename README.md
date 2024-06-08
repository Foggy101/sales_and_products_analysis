# SALES AND PRODUCTS ANALYSIS
Python and PowerBI analysis of the Brazilian E-Commerce Public Dataset by Olist.

The project is divided into 4 parts:<br>
• [Demand forecasting models](https://github.com/Foggy101/sales_and_products_analysis/blob/main/demand_forecasting.ipynb) (ARIMA and random forest) in Python<br>
• [Review sentiment analysis](https://github.com/Foggy101/sales_and_products_analysis/blob/main/review_semantics_prediction_model.ipynb) (neural network) in Python<br>
• [Review analytics](https://github.com/Foggy101/sales_and_products_analysis/blob/main/review_semantics_review_analytics.ipynb) in Python<br>
• [Sales and products dashboard](https://github.com/Foggy101/sales_and_products_analysis/tree/main/images) in PowerBI (*links to images*)

<hr>
<h2>DEMAND FORECASTING</h2>
The main goal of this part is to implement a demand forecasting system for a short-term period (14 days), with forecasts generated 7 days from the last date. These forecasts would then be used to optimize inventory levels, ensuring enough stock to meet customer demand without overstocking and thus reducing stocking expenses.<br><br>
After performing time series decomposition, two models are built - SARIMA and random forest. Both models yield similar forecasts, and the default recommended approach is to consider both results and average them for the final forecast.<br><br>
<strong>EXAMPLE IMAGE: TIME SERIES DECOMPOSITION</strong><br>
<img src="images/demand_decomposition.jpg">

<hr>
<h2>REVIEW SENTIMENT ANALYSIS</h2>
This section is dedicated to creating a review classification neural network. The aim of the model is to distinguish between positive, neutral, and negative text reviews left by customers. The code includes a feature that allows users to input a custom comment for the model to evaluate. Please note that the comment must be in Portuguese.<br><br>
<strong>EXAMPLE IMAGE: USER INPUT PREDICTION</strong><br>
<img src="images/review_sentiment_prediction.jpg">

<hr>
<h2>REVIEW ANALYTICS</h2>
The third part is also focused on customer reviews, providing additional analysis on selected business cases:<br>
• It examines the correlation between review scores and whether a comment was left.<br>
• It identifies products with the best and worst reviews.<br>
• It filters for sellers with negative reviews only.<br>
• It highlights price mentions in text comments, enabling the identification of competitors’ prices within the comments.<br><br>
<strong>EXAMPLE IMAGE: REVIEW SCORE VS COMMENT LEFT</strong><br>
<img src="images/review_analytics_comments.jpg">

<hr>
<h2>SALES AND PRODUCTS DASHBOARD</h2>
The goal of the final part is to create an interactive dashboard for stakeholders to derive insights from. It primarily focuses on identifying the best and worst sellers and products within product categories. Additionally, it includes an additional tab dedicated to analyzing the impact of product weight on their price and total sales.<br><br>
FOR MORE IMAGES GO TO: <a href="https://github.com/Foggy101/sales_and_products_analysis/tree/main/images">LINK</a>
<br><br>
<strong>EXAMPLE IMAGE: MAIN VIEW</strong><br>
<img src="images/dashboard_1.jpg">
