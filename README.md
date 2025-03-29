# Poker RL Agent 

This project implements a reinforcement learning (RL) agent that plays simplified poker using Q-learning. It was developed as a semester-long final project exploring opponent modeling, multi-round betting strategies, and dynamic opponent adaptation.

## Project Overview

- **Environment:** Custom Python-based poker environment with simulated betting rounds and three distinct opponent types (conservative, aggressive, balanced).
- **Agent:** Tabular Q-learning agent that learns optimal betting strategies over time.
- **Opponent Modeling:** Tracks win/loss rates, bluffing tendencies, betting aggressiveness, and fold rates for each opponent profile.
- **Evaluation:** Includes training metrics, opponent behavior visualizations, and per-opponent performance analysis.

## 📊 Features

- Multi-round betting logic (pre-flop, flop, turn, river)
- Simulated bluffing and adaptation in opponent behavior
- Detailed reward engineering based on hand strength and context
- Performance visualizations (reward curves, win/loss rates, bluffing trends)
- Hand logs for key analysis (big wins, risky moves, close calls)

## 📁 Files

- `PokerRL.ipynb`: Main notebook containing environment, agent, training loop, plots, and analysis
- `README.md`: Project summary and instructions

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/) or Jupyter.
2. Run all cells to:
   - Initialize the environment
   - Train the agent over thousands of episodes
   - Visualize performance and behavior metrics

## 📌 Requirements

- Python 3
- NumPy
- Matplotlib

(If running locally, install dependencies via `pip install -r requirements.txt`)

## 🧪 Sample Results

- Smoothed rewards show steady learning
- Win rates improve against all opponent types
- Dynamic bluffing detection and counter-strategies

## 📚 References

- Sutton, R. S., & Barto, A. G. (2018). *Reinforcement Learning: An Introduction*
- Heinrich, J., & Silver, D. (2016). *Deep Reinforcement Learning from Self-Play in Imperfect-Information Games*
- [NeurIPS Poker RL papers](https://papers.nips.cc/)

---

Made as a final project for my reinforcement learning course.
