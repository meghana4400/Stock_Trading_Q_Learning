# Q-Learning for Stock Trading

## 📌 Objective
Design a Q-learning agent that learns to trade stocks intelligently and outperform traditional strategies.

## 📊 Data Sourcing
Collect historical stock price data for Google, Amazon, Meta, IBM, and Apple using Alpha Vantage and Yahoo Finance APIs.

## 📈 EDA and Feature Engineering
Explore data and generate technical indicators:
- MACD
- RSI
- Bollinger Bands
- Volatility
- Moving Averages
- Price Levels

## ⚙️ Code Structure

### Environment Setup
Simulate a trading environment with historical price data.

### Q-Learning Agent
Implement an agent that learns optimal trading actions (buy, sell, hold) using a Q-table.

### Training Process
Train the agent over multiple epochs, refining the Q-table based on trading rewards.

## 💡 Insights
- The agent adapts to different market behaviors.
- Performs competitively against rule-based methods.
- Shows reinforcement learning’s flexibility in trading.

## 🚀 Future Work
- Integrate deep reinforcement learning (DQN).
- Add transaction costs/slippage for realism.
- Expand to multi-asset portfolios.

## 🧰 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn
- Alpha Vantage API, Yahoo Finance API
