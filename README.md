![Python](https://img.shields.io/badge/Python-3.11-blue)
![NumPy](https://img.shields.io/badge/NumPy-Numerical_Computing-orange)
![Monte Carlo](https://img.shields.io/badge/Monte_Carlo-Simulation-green)
![Quant Finance](https://img.shields.io/badge/Quantitative_Finance-Options_Pricing-red)

# Black–Scholes Option Pricing & Monte Carlo Engine

A practical quantitative finance project implementing the Black–Scholes framework, option Greeks, implied volatility estimation, volatility smile analysis, and Monte Carlo simulation techniques.

This project combines analytical pricing models with stochastic numerical methods to explore both theoretical and real-world option pricing behavior.

---

## Features

### Black–Scholes Pricing
- European call option pricing
- Closed-form analytical solution
- Risk-neutral valuation framework

### Greeks Calculation
- Delta
- Gamma
- Vega
- Theta

### Implied Volatility Estimation
- Recover implied volatility from observed market prices
- Numerical root-finding approach

### Volatility Smile Simulation
- Simulated implied volatility smile across strike prices
- Demonstrates deviations from constant volatility assumptions

### Monte Carlo Simulation
- Monte Carlo option pricing
- Convergence analysis against Black–Scholes analytical pricing
- Numerical validation framework

### Variance Reduction Techniques
- Antithetic variates implementation
- Improved convergence stability
- Reduced simulation variance

---

## Project Structure

```text
QUANT-LAB/
│
├── .gitignore
├── requirements.txt
├── README.md
├── black-scholes-monte-carlo-engine.ipynb
│
└── .venv/