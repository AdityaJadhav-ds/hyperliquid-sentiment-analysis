# Hyperliquid Trader Behavior vs Market Sentiment Analysis

## Objective
Analyze how market sentiment (Fear & Greed Index) relates to trader behavior and performance on Hyperliquid. The goal is to uncover behavioral patterns and derive actionable trading insights.

---

## Methodology

1. Data Cleaning
   - Validated missing values and duplicates
   - Converted timestamps to daily level
   - Merged trading data with Fear & Greed index

2. Feature Engineering
   - Daily PnL per account
   - Win rate
   - Average trade size
   - Trades per day
   - Sentiment grouping (Fear / Greed / Neutral)

3. Behavioral Analysis
   - Compared performance across sentiment regimes
   - Analyzed trade frequency and risk behavior
   - Long/Short bias evaluation

4. Trader Segmentation
   - High vs Low Activity traders
   - Consistent vs Inconsistent traders
   - High vs Low Risk traders

5. Predictive Modeling (Optional)
   - Logistic Regression to predict daily profitability
   - Model saved as `profit_model_bundle.pkl`

---

## Key Insights

1. Profitability varies significantly across sentiment regimes.
2. Traders increase activity and trade size during Greed periods.
3. Consistent, lower-volatility traders outperform aggressive high-risk participants.

---

## Strategy Recommendations

- Reduce leverage and trade frequency during Greed regimes to avoid overexposure.
- Encourage structured trade sizing and consistency to improve long-term stability.
- Use sentiment-aware position sizing as a risk filter.

---

## How to Run

1. Clone repository:
