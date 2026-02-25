📌 Project Title :
---

Hyperliquid Trader Behavior vs Bitcoin Fear/Greed Sentiment
---

🎯 Objective
---

Analyze how Bitcoin market sentiment (Fear/Greed Index) impacts trader behavior and performance on Hyperliquid.

The goal is to uncover actionable trading insights based on sentiment-driven behavior.

---

📊 Methodology
---
Data Preparation
---

Cleaned column names

Converted trade timestamps (milliseconds → datetime)

Aligned datasets at daily level

Inner join on date to ensure correct sentiment mapping

---

Key Metrics Created
---

Daily PnL per trader

Win rate

Trades per day

Long/Short ratio

Average leverage

Trader segmentation:
High vs Low leverage

Frequent vs Infrequent traders

---

📈 Key Findings
---
1️⃣ Fear Periods Show Highest Profitability
---

Highest average daily PnL

Highest win rate

Increased trade frequency

Interpretation:
Market panic creates volatility-driven inefficiencies.

---

2️⃣ Extreme Greed Reduces Edge
---

Lower win rate

Lower average PnL

High leverage traders underperform

---

3️⃣ Trader Segmentation Insight
---

High-leverage traders outperform in Fear

High-leverage traders underperform in Extreme Greed

Frequent traders show more stable performance across sentiments

Interpretation:
Overconfidence and crowded positioning reduce profitability.

---

🧠 Strategy Recommendations
---

Strategy 1 — Fear Exploitation Rule

During Fear:

Increase trade participation

Allow moderate leverage expansion

Focus on volatility-based strategies

---

Strategy 2 — Greed Risk Control Rule

During Extreme Greed:

Reduce leverage exposure

Reduce position size

Avoid breakout chasing

---

⚙️ Setup Instructions
---

Clone repository:
---

git clone <repo-link>
cd hyperliquid-sentiment-analysis

Create virtual environment:
---

python -m venv venv
venv\Scripts\activate

Install dependencies:
---

pip install -r requirements.txt

Run notebook:
---

jupyter notebook

---

requirements.txt
---

Run this in terminal:

pip freeze > requirements.txt

Make sure it contains at least:

pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter

---

📈 Outputs & Visualizations
---

1️⃣ Average Daily PnL by Sentiment
---

Observation:

Fear periods show highest average profitability.

Extreme Greed significantly reduces profitability.

<img width="597" height="455" alt="output" src="https://github.com/user-attachments/assets/4d4ae8e5-8892-477a-970e-7d99c768c725" />



2️⃣ Win Rate by Sentiment
---

Observation:

Win rate peaks during Fear.

Lowest win rate observed in Extreme Greed.

<img width="576" height="455" alt="output (1)" src="https://github.com/user-attachments/assets/755c438f-1647-415f-b986-c48d5910e81a" />


3️⃣ Leverage Segment Analysis
---

Observation:

High-leverage traders outperform in Fear.

High-leverage traders underperform in Extreme Greed.

Risk exposure becomes harmful during euphoric conditions.

<img width="597" height="455" alt="output (2)" src="https://github.com/user-attachments/assets/a86c7b01-7da1-468c-904f-3cc7d130c52f" />


---

📌 Executive Summary
---

This analysis demonstrates that trader profitability on Hyperliquid is significantly influenced by Bitcoin sentiment regimes.

Fear-driven markets create structured volatility and opportunity, while Greed-driven markets reduce edge and increase risk exposure.

Dynamic leverage and participation adjustment based on sentiment regime can improve risk-adjusted performance.
