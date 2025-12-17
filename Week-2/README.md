# Week 2 – Kalman Filtering for Trading

## Goal  
The goal of this learning module is to build a solid theoretical and practical foundation in Kalman Filters, with an emphasis on their application to financial time series and trading strategies. Learners will understand how Kalman Filters model noisy observations and estimate latent variables such as fair value, trend, volatility, and dynamic relationships. The module aims to bridge intuition, mathematics, and implementation by enabling participants to confidently apply Kalman Filters in Python. By the end of the module, learners will be able to interpret model outputs, evaluate assumptions, and assess the suitability of Kalman Filter–based methods in real trading environments.

## What You Will Learn
By the end of the week, you will understand the mathematical foundations of Kalman filtering, including state-space models, prediction–update equations, and covariance dynamics. You will learn how to implement one-dimensional and multi-dimensional Kalman Filters in Python and apply them to estimate trends, volatility, and dynamic relationships in financial data. You will also gain hands-on experience using Kalman Filters for trading applications such as mean-reversion, trend estimation, and dynamic regression, along with an understanding of their limitations and practical considerations.

---

## Recommended Resources

- The booklet for week 2. The pdf has been uploaded within the Week 2 folder itself. 

- ADF_Test_Examples.ipynb: This file contains examples of the Augmented Dickey-Fuller (ADF) test, a statistical test for stationarity. Refer to this for understanding how stationarity is crucial for trading.

- https://kalmanfilter.net: Intuitive tutorial explaining Kalman Filter via numerical examples and real-world scenarios like radar tracking.​

- https://blog.quantinsti.com/kalman-filter/ :Python tutorial on Kalman Filter for trading, covering pairs trading, volatility estimation, and code examples with stock data.​

- https://www.cs.cmu.edu/~motionplanning/papers/sbp_papers/kalman/kleeman_understanding_kalman.pdf :Academic paper detailing Kalman Filter fundamentals, equations, covariance matrices, and implementations like falling body example.​

- https://medium.com/@serdarilarslan/implementing-a-kalman-filter-based-trading-strategy-8dec764d738e :Practical guide to building a Kalman Filter-driven trading strategy, focusing on dynamic hedge ratios for pairs trading.

For a deeper understanding of **Kalman filtering in trading**, we recommend the following resources:

- **Books on Kalman Filtering**:

- *Kalman Filtering: Theory and Practice Using MATLAB by Mohinder S. Grewal and Angus P. Andrews* (very high level, can skip)
    - Chapter 1: Introduction to Kalman Filtering (pages 1–22)
    - Chapter 3: One-Dimensional Kalman Filter (pages 45–69)
    - Chapter 4: Multi-Dimensional Kalman Filter (pages 71–100)
- *Bayesian Filtering and Smoothing by Simo Särkkä* (explores the Control Theory aspects of Kalman Filters as well)
    - Chapter 2: Kalman Filter for Linear Systems (pages 9–24)
    - Chapter 4: Introduction to the Extended Kalman Filter (pages 57–75)
- *An Introduction to the Kalman Filter by Greg Welch and Gary Bishop*
    - Section 2: Kalman Filter Equations (pages 2–10)
    - Section 3: Implementation of a Simple Kalman Filter (pages 11–18)

• **Kalman Filtering in Python**: For a practical, hands-on guide to implementing Kalman filters in Python, refer to the following resource:
[Kalman and Bayesian Filters in Python - 1D Kalman Filter](https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python/blob/master/04-One-Dimensional-Kalman-Filters.ipynb)

• **Additional Resource**:

-[Kalman Filter for Linear Regression](https://letianzj.github.io/kalman-filter-linear-regression.html): A great resource for understanding how Kalman filtering can be applied to linear regression, helping you deepen your understanding of Kalman filtering in the context of pairs trading.

-[How a Kalman Filter Works in Pictures](https://www.bzarg.com/p/how-a-kalman-filter-works-in-pictures/): A visual guide to understanding how Kalman filters operate.



### Assignment
**By completing this assignment, you will be able to:** 
- Model non-stationary financial time series using Kalman Filters instead of static assumptions

- Formulate and implement a state-space model for real market data

- Use practical feature engineering for financial markets and understanding which features carry predictive power

- Integrate machine learning with probabilistic filtering (Kalman-filtered states → ML prediction)

- Design causal, leakage-free trading signals suitable for real backtesting

- Build a complete end-to-end trading pipeline: data → model → signals → PnL

- Implement and interpret backtesting metrics like Sharpe ratio and drawdown

- Understand the gap between predictive accuracy and trading profitability

- Develop intuition for risk management and robustness in systematic strategies

Ensure that the code is detailed and well commented. Make sure the report includes the proper solutions, required code and include all relevant plots, explanations and corresponding output. 

Reach out to anyone of us if you are stuck somewhere and need help. 

Submit your work by 23rd December, 2025 via webmail to 24b3935@iitb.ac.in and 24b3962@iitb.ac.in

May the Profit be with you!

---