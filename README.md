# 📊 Trader Performance vs Market Sentiment

## 🎯 Objective
Analyze how Bitcoin market sentiment (Fear/Greed) affects trader performance and behavior using historical trading data.

## 📁 Dataset
- **Fear & Greed Index** – Market mood classified daily
- **Hyperliquid Trades** – Trader behavior data (PnL, side, size, etc.)

## 🔍 Key Insights
- Traders had slightly higher average PnL during Fear (75.37) vs Greed (75.17).
- Win rate was also highest in Fear (43.36%) compared to Greed (41.80%).
- Fear sentiment led to larger trade sizes (9125 USD avg) vs smaller sizes during Greed (7153 USD).
- Greed days showed more SELL activity, indicating profit-booking behavior.
- Fear days showed more balanced BUY and SELL trades, implying cautious entries.


## 📊 Visualizations
- Bar plots for PnL, Win Rate, Trade Size
- Stacked bar for Side (BUY/SELL) preference

## 🛠️ Tools Used
- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook

## 📝 Conclusion
The analysis reveals that traders tend to perform better during Fear sentiment phases. They trade more
selectively, take higher conviction positions, and manage risk better. In contrast, Greed sentiment sees more
reactive trading, smaller trades, and slightly lower success rates. Thus, market sentiment is a strong indicator
that can be leveraged to build sentiment-aware trading strategies.

