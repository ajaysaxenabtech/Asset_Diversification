
# Asset Diversification & Portfolio Risk Optimization (Python OOP)

This repository demonstrates how to **analyze diversification** in a portfolio through **covariance and correlation** among assets, and then **optimize the portfolio for minimum risk** using Python and Object-Oriented Programming (OOP).

---

## 🔹 Motivation
In portfolio theory, risk is not just about individual asset volatility — it depends on **how assets move together**.  
This project implements a **Portfolio Optimizer** that:

1. Calculates **covariance and correlation matrices**
2. Builds portfolios (equal-weight & optimized)
3. Shows how diversification reduces risk
4. Finds the **optimal risk-minimizing portfolio** using numerical optimization

---

## 🔹 Mathematical Background

### Portfolio Variance
For *n* assets with weights \( w \), covariance matrix \( \Sigma \):

\[
\sigma_p^2 = w^T \Sigma w
\]

### Portfolio Volatility
\[
\sigma_p = \sqrt{w^T \Sigma w}
\]

### Optimization Problem
We minimize risk subject to full investment:

\[
\min_w \, \sigma_p \quad \text{s.t.} \quad \sum_{i=1}^n w_i = 1, \, w_i \geq 0
\]

---

## 🔹 Project Structure

