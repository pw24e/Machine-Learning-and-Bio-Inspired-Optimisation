# 🎰 Multi-Armed Bandit Assignment – Reinforcement Learning (Sutton & Barto)

## 📚 Overview

This repository contains my solution for **Problem 1 (40 marks)** of a reinforcement learning assignment. The task involves implementing a **multi-armed bandit** algorithm inspired by Figure 2.1 from Sutton & Barto’s *Reinforcement Learning: An Introduction* (2nd Edition).

The goal is to explore how different **ε-greedy strategies** influence the balance between **exploration and exploitation**, and to compare their performance across repeated trials.

---

## 🎯 Objectives

- Implement a **multi-armed bandit algorithm** with ε-greedy action selection.
- Simulate an **n-armed bandit** problem (n = 5, 10, or 20).
- Run the simulation for **2000 plays (steps)** and track performance.
- Compare results for different ε values (e.g., 0, 0.01, 0.1).
- Plot:
  - **Average reward over time**
  - **% Optimal action selection over time**
- Interpret the effectiveness of different strategies based on results.

---

## 📌 Key Topics Covered

- Reinforcement Learning (RL)
- Action-value methods
- ε-greedy exploration
- Exploration vs. Exploitation trade-off
- Simulations and performance evaluation
- Result visualization and analysis

---

## 🛠️ Steps Taken

1. **Environment Setup**:
   - Defined a multi-armed bandit environment with variable `n` arms.
   - Each arm has a stationary reward distribution.

2. **Algorithm Design**:
   - Implemented ε-greedy action selection with ε ∈ {0 (greedy), 0.01, 0.1}.
   - Used sample averages to estimate action values.

3. **Simulation Execution**:
   - Ran simulations for 2000 steps.
   - Repeated experiments across multiple trials (to average results).

4. **Result Analysis**:
   - Calculated and plotted average reward vs. steps.
   - Calculated and plotted % of optimal action selection over time.
   - Interpreted the impact of different ε values on learning performance.

5. **Report Preparation**:
   - Explained implementation details, presented graphs, and discussed findings in a written report.
   - Source code provided as `.ipynb` notebook file.

---

## 📎 Reference

Sutton, R. S., & Barto, A. G. (2018). *Reinforcement Learning: An Introduction* (2nd ed.).  
Figure 2.1, Average performance of ε-greedy methods:  
[📖 Link to Book (Stanford)](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf)

---

## 🗂️ Files Included

- `multi_armed_bandit.ipynb`: Source code notebook  
- `report.pdf`: Written report explaining the solution, analysis, and results  
- `README.md`: This file

---
## 👥 Contributors

This was a collaborative effort by students enrolled in the MSc Data Science and AI programme:

- Castelino, Shane 
- Wijesinghe, Prathusha
- Kim, Suyeon 
- Yiu, Benjamin 
- Yenidunya, Defne

---

## ⚠️ Disclaimer

All work is original and submitted as part of **assessed coursework** for the MSc in Data Science and Artificial Intelligence at the University of Liverpool.
Do not copy, redistribute, or reuse without explicit permission.
