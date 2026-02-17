# Trader Performance vs Market Sentiment Analysis

## Objective
Analyze how Bitcoin market sentiment (Fear/Greed) influences trader behavior and performance on Hyperliquid.

---

## Datasets
1. Fear & Greed Index (daily sentiment)
2. Historical trader-level execution data

---

## Methodology

1. Data cleaning and preprocessing
2. Daily aggregation per trader
3. Sentiment-based performance comparison
4. Behavioral segmentation:
   - Frequent vs Infrequent traders
   - Large vs Small position traders
   - Consistent vs Volatile traders
5. Optional clustering and predictive modeling

---

## Key Insights

1. Traders exhibit higher average PnL during Fear periods compared to Greed.
2. Trade frequency increases during Fear regimes.
3. Large-position traders show deeper drawdowns in Greed environments.

---

## Strategy Recommendations

1. Increase trade allocation for active traders during Fear regimes.
2. Implement stricter position size controls during Greed regimes.

---

## How to Run

```bash
pip install -r requirements.txt



open :
jupyter notebook trader_analysis.ipynb



---

# ✅ STEP 5 — 1 Page Summary (Important)

Create a file:


Keep it concise (max 1 page).

Structure:

- Problem
- Approach
- 3 insights
- 2 strategy ideas
- Optional modeling result

This is what recruiters actually read first.

---

# ✅ STEP 6 — Clean Notebook Before Upload

Before pushing:

- Restart kernel
- Run all cells
- Clear unnecessary outputs
- Ensure no file paths like `C:\Users\mohan\...`

Replace with:

```python
pd.read_csv("data/fear_greed_index.csv")

