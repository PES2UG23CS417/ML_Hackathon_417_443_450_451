# ML_Hackathon_417_443_450_451
# 🧠 Hangman ML Agent — Machine Learning Hackathon

### Department of Computer Science and Engineering  
**Course:** UE23CS352A – Machine Learning Hackathon  

## 📘 Project Overview

This repository contains our implementation for the **Machine Learning Hackathon** focused on developing an intelligent agent to play **Hangman** using **Hidden Markov Models (HMM)** and **Reinforcement Learning (Q-Learning)**.

Our hybrid approach leverages:
- **HMM** for probabilistic inference of letter likelihoods.
- **Q-Learning** for adaptive decision-making through trial and reward-based exploration.
- **Integration of both** to balance model-driven prediction and experience-driven strategy.

---

## 🧩 Key Files
- `417_443_450_451.ipynb` — Main Jupyter Notebook with all training, evaluation, and visualizations.
- `Analysis_Report_417_443_450_451.pdf` — Detailed report covering design choices, observations, insights, and future improvements.

---

## ⚙️ How It Works
1. **HMM Training:**  
   Discrete HMMs are trained for words of varying lengths using the Baum-Welch algorithm.
2. **Reinforcement Learning:**  
   The Q-Learning agent learns optimal letter-guessing policies with rewards/penalties for correct, incorrect, or repeated guesses.
3. **Hybrid Agent:**  
   Combines HMM probabilistic hints and learned Q-values to maximize performance in Hangman gameplay.

---

## 🚀 Results Summary
- Pure HMM agents performed competitively in greedy scenarios.  
- Hybrid HMM-RL models achieved better generalization and adaptability.  
- Major challenges: HMM convergence, state representation, exploration-exploitation balance.  

---

## 🔮 Future Work
- Deep RL with neural policies.  
- Improved reward shaping and feature encoding.  
- Interactive visualization for explainability.  

---

## 🧭 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Hangman-ML-Agent.git
   cd Hangman-ML-Agent

2. Open Notebook:
   ```bash
   jupyter notebook 417_443_450_451.ipynb

3. Run all cells sequentially to train and evaluate the agent.

