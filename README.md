📈 Dynamic Portfolio Allocation Using Predictive Modeling

A data-driven approach to optimize portfolio allocations by predicting market movements and automating asset rebalancing based on macroeconomic factors.

📌 Project Overview

This project develops a log-log regression model to predict Price-to-Earnings (PE) ratios and generate buy/sell/hold signals. The goal is to dynamically adjust allocations for indices such as Nifty Smallcap 100, Nifty Midcap 100, Nifty JR, and Nifty 50, improving portfolio performance.

🔍 Problem Statement

Investors face challenges in:
	•	Accurately predicting market cycles for mid-cap and small-cap indices.
	•	Managing risks by determining optimal allocation to cash or equities based on valuation signals.
	•	Reducing volatility in returns due to market fluctuations.

🔹 Hypotheses Tested

✅ Valuations based on PE ratios can predict when to overweight or underweight allocations.
✅ Macroeconomic factors such as inflation, repo rate, and oil prices significantly impact PE ratios.
✅ Log-log regression provides a more accurate model for predicting non-linear market relationships.

🔹 Technologies Used
	•	Python (pandas, NumPy, statsmodels) for data analysis, modeling, and back-testing.
	•	Jupyter Notebook for developing and visualizing the predictive model.
	•	Data sources: Bloomberg, NSE Website, Federal Reserve Economic Data, Investing.com.

📊 Key Insights from Analysis

1️⃣ Undervaluation leads to buy signals, and overvaluation triggers sell signals across indices.
2️⃣ Inflation and repo rate are key drivers of market valuation, significantly affecting PE ratios.
3️⃣ Back-testing results showed the model outperformed a buy-and-hold strategy, especially during volatile periods.
4️⃣ Dynamic allocation based on signal strength optimized returns and minimized risks.

📌 Recommendations

✅ Overweight allocations to mid-cap indices during periods of low PE ratios based on predictive signals.
✅ Underweight allocations or shift to cash during periods of high valuations or unfavorable macroeconomic conditions.
✅ Continuous monitoring of key indicators such as inflation and repo rate to adjust allocations dynamically.
