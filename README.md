# Data-Analysis
Project Overview  This analysis explores the relationship between Bitcoin trader performance (from Hyperliquid historical data) and market sentiment (from the Bitcoin Fear &amp; Greed Index). 
Insights & Findings

1. **Profitability vs Sentiment:**  
   Traders showed higher average PnL during "Greed" phases, indicating increased risk appetite pays off in bullish sentiment.

2. **Leverage Behavior:**  
   Leverage tends to rise during "Greed" days, confirming higher risk-taking during positive sentiment.

3. **Statistical Significance:**  
   T-test revealed a significant difference (p < 0.05) in PnL between Fear and Greed days.

4. **Lag Effect:**  
   The sentiment of the previous day moderately affects next-day profitability — suggesting emotional carryover.
Conclusion & Recommendations

- **Sentiment awareness** can serve as an additional risk management layer.
- **Traders** should consider scaling down leverage during Fear periods.
- **Firms** can integrate sentiment data into algorithmic trading strategies.
- **Future work:**  
  - Add volume and volatility metrics from BTC price data.  
  - Test model with real market volatility indicators (VIX, BTC price, etc.).
