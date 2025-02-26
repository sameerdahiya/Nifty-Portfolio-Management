Dynamic Portfolio Allocation Using Predictive Modeling

Project Overview

This project focuses on dynamically adjusting portfolio allocations for different indices (Nifty Smallcap 100, Nifty Midcap 100, Nifty JR, and Nifty 50) using a signal-driven predictive model. The model interprets market conditions to determine whether to overweight or underweight certain asset classes and identifies if cash allocation is appropriate when all indices are overvalued.

Objective
	•	Develop a model to determine when to increase or decrease allocations to Mid & Small Caps based on valuations and indicators.
	•	Use back-testing to evaluate model performance and optimize portfolio allocations.

Features
	•	Log-Log Regression Model: The model predicts the Price-to-Earnings (PE) ratio based on multiple macroeconomic factors such as inflation, repo rate, oil prices, and USD/INR exchange rate.
	•	Buy/Sell/Hold Signals: Based on the predicted PE ratio, buy, sell, or hold signals are generated to inform portfolio reallocation decisions.
	•	Quarterly Data: The model works on quarterly data to smooth out short-term market volatility while capturing medium-term trends.
	•	Back-Testing: Historical data is used to test the model’s accuracy and ensure consistent performance compared to benchmarks.

Data Sources
	•	Bloomberg
	•	NSE Website
	•	Federal Reserve Economic Data
	•	Investing.com

Key Inputs
	•	Lag PE and Lag PB: Tracks historical PE and PB trends.
	•	Repo Rate: Central bank interest rates affecting liquidity.
	•	Inflation: Price stability affecting market valuation.
	•	Oil and Gold Prices: Global commodity prices influencing corporate earnings and market sentiment.
	•	USD/INR Exchange Rate: Currency fluctuations affecting foreign investments and corporate earnings.

Model Development
	•	Log-Log Regression: Non-linear relationships between variables are handled using log-log transformation, making it robust to outliers and ensuring better model interpretation.
	•	Feature Selection: The model includes iterative selection of macroeconomic factors with key metrics like R-squared and mean-squared error for accuracy.

Portfolio Allocation Strategy
	•	Signal-Based Allocation: Portfolio weights are adjusted based on the signal strength (Buy, Sell, or Hold) and the quartile band of allocation (0-25%, 26-50%, 51-75%, 76-100%).
	•	Dynamic Adjustments: The model updates predictions and signals based on new data, ensuring continuous optimization.

Results
	•	Outperformance: Back-testing showed the model’s effectiveness in identifying overvaluation and undervaluation periods, with portfolios adjusted by the model outperforming benchmark strategies.
	•	Accurate Signals: The model generated reliable buy/sell signals based on predicted and actual PE differences, providing consistent guidance on when to rebalance portfolios.

Conclusion

The predictive model provides a data-driven approach for managing portfolio allocations across indices, improving returns through timely reallocation decisions. This model can assist investors in navigating volatile markets by responding to economic signals and ensuring portfolio allocations are optimized based on market conditions.
