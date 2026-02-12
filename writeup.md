# Hyperliquid & Market Sentiment Study

## Methodology

In this project, I analyzed how Bitcoin market sentiment influences
trader performance on the Hyperliquid platform.

Two datasets were used:
1. Fear & Greed Index (daily classification)
2. Hyperliquid trade history

First, I standardized the sentiment labels and converted timestamps
into proper dates.

Next, I aggregated raw trades into daily summaries for each account.
For every account-day, I calculated:
- total daily profit/loss  
- number of trades  
- win rate  
- average trade size  
- long vs short ratio  

After that, I merged sentiment data with trading performance using the date.

Finally, I compared Fear vs Greed days using averages, distributions,
and statistical tests.

---

## Insights

Several clear behavioural patterns appeared.

**1. Performance changes with sentiment.**  
Daily PnL and win rates were not the same in Fear and Greed regimes.

**2. Trader activity shifts.**  
On emotionally charged days, many traders increased participation,
which sometimes reduced consistency.

**3. Discipline matters.**  
Traders with controlled activity generally showed more stable results
than highly active traders.

---

## Strategy Recommendations

Based on the data, I propose:

**• Reduce unnecessary trades during emotional extremes.**  
Higher activity did not always translate to better results.

**• Be cautious when the market becomes crowded.**  
If most traders lean in one direction, risk of reversal increases.

---

This project demonstrates how raw transaction data can be converted
into practical insights and rule-based strategies.