# AUTONOMOUS STOCK TRADING AGENT USING AGENTIC AI AND DEEP Q-LEARNING

This project implements a Deep Q-Learning (DQN)-based AI agent trained to make stock trading decisions using historical market data. The goal is to maximize portfolio returns over time by learning optimal trading strategies through trial and error.

---

## 🚀 Features

- Custom OpenAI Gym trading environment
- Deep Q-Network (DQN) with experience replay and target networks
- Real-time portfolio simulation and performance tracking
- Visualizations:
  - Portfolio Value Over Time
  - Training Reward Trajectory
  - Agent Decision Confusion Matrix
  - Cumulative Rewards

---

## 🧠 Algorithm

- **Model**: Deep Q-Network (DQN)
- **State Inputs**: Stock prices, portfolio balance, shares held, technical indicators
- **Actions**: Buy, Sell, Hold
- **Reward**: Change in portfolio value per step
- **Libraries Used**: `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `torch`, `gym`

---

## 📊 Results

- Agent portfolio value improved over episodes.
- Cumulative reward trajectory increased steadily with training.
- Confusion matrix shows decision distribution between actions (Buy, Sell, Hold).

---



