# Multi-Asset Carry and Momentum Strategy

This project implements a quantitative trading strategy combining carry and momentum factors across multiple asset classes, including G10 FX currency pairs, Gold, and Government Bond ETFs.

## Project Overview

- **Objective:** To design and backtest a multi-asset carry and momentum strategy with robust out-of-sample performance using walk-forward testing.
- **Assets:** G10 FX pairs, Gold ETF, Government Bond ETFs.
- **Methodology:** 
  - Construct carry signals based on forward returns and momentum signals based on price trends.
  - Normalize and combine signals for portfolio construction.
  - Perform rolling walk-forward backtesting over a 20-year dataset for realistic performance evaluation.
  - Benchmark results against academic research standards.
- **Results:** Achieved credible risk-adjusted returns with a Sharpe ratio of approximately 0.17 and manageable drawdowns.

## Tools and Technologies

- Python programming language
- Jupyter Notebook for interactive development and reporting
- Libraries: pandas, numpy, matplotlib, yfinance (for data retrieval)

## Repository Structure

- `notebooks/` - Jupyter notebooks containing data analysis, signal construction, backtesting, and visualization.
- `scripts/` - Python scripts for data processing and strategy implementation.
- `data/` - (Optional) sample data or data retrieval scripts.
- `README.md` - This file.

## How to Run

1. Clone the repository.
2. Ensure Python 3.x is installed with the required libraries (`pandas`, `numpy`, `matplotlib`, `yfinance`).
3. Open the main Jupyter notebook in `notebooks/` and run the cells sequentially.
4. Review the outputs and visualizations for insights into strategy performance.

## Future Work

- Incorporate transaction costs and slippage modeling.
- Implement volatility scaling and dynamic risk management.
- Extend asset coverage to emerging market currencies and additional ETFs.
- Explore machine learning techniques while maintaining interpretability.
- Conduct regime-specific analysis and advanced validation techniques.
