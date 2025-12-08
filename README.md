# Kalman-Filtered Trend Trader: A Deep Reinforcement Learning Agent for Portfolio Optimization

This repository is part of **WiDS (Winters in Data Science)** conducted by **The Analytics Club, IIT Bombay**.

This project blends **machine learning**, **finance**, and **signal processing** into a single hands-on system.  
You’ll gain the technical and conceptual depth needed for **quantitative trading**, **AI research**, and **data-driven financial modeling** — all while learning to see through noise and act intelligently.

Hopefully, you find this endevour both rewarding and entertaining :)


---

## Project Overview

**Problem Statement:**  
This project aims to design an **autonomous trading agent** that makes intelligent, long-term portfolio decisions based on the *true underlying market trend* — not just daily volatility.

**Goal:**  
Build a Deep Reinforcement Learning (RL) agent that allocates between a **risky asset** and a **stable asset** (cash) to maximize portfolio value over time.

**Core Idea:**  
Instead of feeding noisy prices to the agent, use a **Kalman Filter** to estimate the true price and its trend (velocity).  
The RL agent learns an optimal policy — when to buy, sell, or hold — from these filtered signals.


### Key Learning Outcomes

By completing this project, you will learn:

- Reinforcement Learning fundamentals (state, action, reward, policy)
- Financial portfolio optimization and backtesting
- Kalman Filtering and state-space modeling
- Time-series noise reduction and trend estimation
- Training RL agents 
- Performance evaluation with transaction costs and benchmarks


## Evaluation Criteria
> _"The Simplicity of your explanation is indicative of the depth of you undestanding"_


You must have heard people say, if you can teach something then you know it very well. That idea is based on the above statement.
Throughout the project, we will ask you to explain what you think is going on - **with a Twist!** You wont be allowed to use any  of the technical terms to explain it. Using everyday Layman language, try to tell whats going on.

This one exercise is the only time I ask you **not** to use AI `(~_~;)` 

Everywhere else, use AI as you see fit. Afterwards write a short paragraph explaining:
- What you did 
- What problems you encountered
- How you solved them

and most importantly, **What do you think you learned?** (^o^)

From my side, I hope to show you more than just the numbers at play. Every topic has a perspective behind it, a history of its ideas and I really like to share that. So ill try to tell about the history of Machine Learning and Stock Markets too! (Maybe there will be history questions lol (^m^))


There will be 3 assignments and the Final Project.
- Machine Learning
- Kalman Filtered Trading
- Reinforcement Learning
- The final project encompassing everything

For those who already know Machine Learning or Kalman Filter, you dont need to do the assignment in ernest, just share some thoughts about how you would go about solving the problems, only the framework.
Please be sure to complete the RL assignment and the Final Project otherwise we wont pass you (ー_ー)!!

---

## Weekly Contents

### **Week 1 – Foundations of Machine Learning**
**Goal:** Build a rigorous intuition and mathematical understanding of main machine learning methods— linear regression models, neural network architectures, and deep learning techniques—while actually being able to **implement** and **evaluate** these models on real datasets. 

**Learn:**  
- Learn Linear Regression from the absolte basics - The Math! 
The various techiniques we use and all the technical jargon. 
- Implement an actual network for a simple task
- Learn of Deep Neural networks and their power through MNIST Handwritten Dataset.


### **Week 2 – Kalman Filter & Trend Estimation**
**Goal:** Implement a Kalman Filter to extract the true trend from noisy data.  
**Learn:**  
- Hidden-state modeling: [price, velocity] 
- Process vs measurement noise  
- Implementing Kalman Filter (`numpy` or `filterpy`)  
- Tuning parameters and visualizing results  


### **Week 3 – Learning Reinforcement Learning**
**Goal:** Build a simple RL agent that can play and improve at a game
**Learn:**  
- RL basics: state, action, reward, policy
- Different Learning Strategies
- How an agent explores and learns overtime


### **Final Project: RL Trend Trader**

A **complete end-to-end beast** that earns money!

[Stock Data] → [Kalman Filter] → [Trend Estimate] → [RL Agent] → [Allocation %] → [Portfolio Value]



> *“An intelligent trading agent doesn’t just follow prices — it understands the market’s rhythm.”*
