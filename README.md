# Hyperliquid × Fear & Greed Sentiment Analysis

## Project Objective
The aim of this project is to understand how **market sentiment**
(Fear vs Greed) affects trader behaviour and performance on the
Hyperliquid exchange.

We try to answer questions like:
- Do traders earn more during Fear or Greed?
- Does win rate change with sentiment?
- Do people trade more aggressively in certain market moods?

---

## Datasets Used

### Fear & Greed Index
Daily market sentiment label such as:
Fear, Extreme Fear, Neutral, Greed, Extreme Greed.

For simplicity:
- Extreme Fear → Fear  
- Extreme Greed → Greed  

---

### Hyperliquid Trades
Trade-level information including:
account, timestamp, side, trade size, and closed PnL.

---

## What the Notebook Does

1. Cleans both datasets.
2. Converts timestamps to dates.
3. Aggregates trades to **account × day**.
4. Calculates:
   - daily pnl
   - win rate
   - trade frequency
   - long vs short bias
5. Merges sentiment with trading performance.
6. Runs comparisons and statistical tests.
7. Produces charts and tables.

---

## How to Run

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn openpyxl
```

Steps:
1. Put the csv files inside the `data/` folder.
2. Open the notebook.
3. Run all cells from top to bottom.
4. Charts will appear in `outputs/charts/`.

---

## Folder Structure

```
project/
│
├── data/
├── notebooks/
├── outputs/
│   ├── charts/
│   └── tables/
├── README.md
└── writeup.md
```

---

## Skills Demonstrated
- Data cleaning  
- Feature engineering  
- Aggregation  
- Behavioral analysis  
- Visualization  
- Turning data into strategy ideas  

---

## Author
Vishal Arkalwar  
B.Tech AIML