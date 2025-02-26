📈 Dynamic Portfolio Allocation Using Predictive Modeling

📝 Project Overview

This project focuses on dynamically adjusting portfolio allocations for indices such as Nifty Smallcap 100, Nifty Midcap 100, Nifty JR, and Nifty 50. A signal-driven predictive model is used to interpret market conditions, helping determine whether to overweight or underweight assets, or allocate to cash if all indices are overvalued.
🎯 Objective
	•	Develop a model to identify the right times to increase or decrease allocations to Mid & Small Caps, using various valuation metrics and indicators.
	•	Back-test the model to evaluate its performance in optimizing portfolio allocations over time.
 ✨ Features
	•	Log-Log Regression Model: Predicts Price-to-Earnings (PE) ratios based on multiple macroeconomic factors.
	•	Buy/Sell/Hold Signals: Generated based on predicted PE values, offering guidance for portfolio reallocation.
	•	Quarterly Data Processing: To capture medium-term trends while smoothing out short-term market fluctuations.
	•	Back-Testing: Historical performance data is used to ensure model accuracy and reliability.
 📊 Data Sources
	•	Bloomberg
	•	NSE Website
	•	Federal Reserve Economic Data
	•	Investing.com
 🔑 Key Inputs
	•	Lag PE & Lag PB: Historical PE/PB ratios for trend analysis.
	•	Repo Rate: Interest rates that affect overall liquidity and market conditions.
	•	Inflation: Economic stability that impacts company earnings.
	•	Oil & Gold Prices: Commodity prices that reflect market sentiment and corporate earnings.
	•	USD/INR Exchange Rate: Currency fluctuations affecting foreign investment and import/export.
 🛠️ Model Development
	•	Log-Log Regression: Used to capture non-linear relationships between economic variables and PE ratios. This transformation helps handle outliers and enhances model interpretability.
	•	Feature Selection: An iterative process was employed to refine input variables, focusing on the most predictive features to improve model accuracy.
 ⚡ Results
	•	Outperformance: Back-testing shows the model’s ability to outperform traditional strategies, especially in volatile market environments.
	•	Accurate Signals: The model successfully generated reliable buy/sell signals, providing valuable insights for portfolio rebalancing.
 ✅ Conclusion

This predictive model offers a data-driven approach to portfolio management by interpreting macroeconomic conditions and adjusting allocations accordingly. Investors benefit from optimized returns through systematic reallocation decisions, guided by model signals.
