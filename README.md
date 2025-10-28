# Data Science Assignment – Web3 Trading Team
**Candidate:** Vipin Mishra  
**Project Folder:** ds_vipin_mishra  
**Google Colab Link:** [Open in Colab](https://colab.research.google.com/drive/1_W1Z8N7dHUfJORpDnH7qZpMph6yUelxz?usp=sharing)

---

## Objective
The goal of this project is to analyze how trader behavior — including profitability, leverage, and risk — aligns or diverges from overall market sentiment (Fear vs. Greed).  
By examining the Bitcoin Market Sentiment dataset and Historical Trader Data, the analysis aims to uncover behavioral patterns that could inform smarter, sentiment-aware trading strategies.

## Key Findings Summary
- Sentiment Distribution: Market dominated by Fear (72.65%), followed by Greed (19.69%), Neutral (3.88%), and Extreme Greed (3.78%).
- Trading Behavior: Extreme Greed shows the highest mean trade size ($5,660.27); Fear shows the highest total volume ($704M USD).
- Profitability: Greed periods yield higher average Closed PnL ($87.89) vs Fear ($50.05).
- Risk Patterns: Extreme Greed has the highest profitable trades (49.01%) but also higher losses (13.21%).
- Correlation: Trade volume negatively correlated (-0.572) with sentiment index, indicating lower volume as greed increases.
- Hypothesis Test: Statistically significant difference in mean PnL between Fear and Greed (p < 0.001).
- Clustering: K-Means reveals sentiment-driven trading clusters with distinct risk and PnL patterns.

---

## Tools and Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- SciPy  

Environment: Google Colab

---

## Conclusion
Fear dominates most market periods but shows higher volatility and participation.  
Greed periods result in fewer but more profitable trades.  
Integrating sentiment analysis into trading models can improve strategy performance by dynamically adjusting leverage and risk exposure.

---

## References
- Fear & Greed Index Dataset: https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing  
- Historical Trader Data: https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing  

---

© 2025 Vipin Mishra | Web3 Trading Team Data Science Assignment
