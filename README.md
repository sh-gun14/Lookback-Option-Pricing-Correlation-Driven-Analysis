# Correlated Asset Analysis & Lookback Option Pricing

A Python-based project for analyzing correlated asset behavior and pricing exotic lookback options using Monte Carlo simulations.

## 🚀 Overview

- Conducts statistical correlation analysis across Gold, Oil, Bitcoin, and ICICI Bank price series  
- Prices floating-strike and fixed-strike lookback options via Geometric Brownian Motion Monte Carlo simulations  
- Computes option Greeks (Delta, Gamma, Vega, Theta, Rho) using variance reduction and finite-difference methods  
- Performs convergence and sensitivity analyses for numerical accuracy  
- Integrates real market parameters: volatility (from correlation insights), interest rates, dividend yields, and time to maturity

## 🛠 Features

- 📊 **Correlation Analysis**: Generates heatmaps and scatter plots to visualize asset relationships  
- 💹 **Option Pricing**: Simulates price paths and computes option values  
- 🧮 **Greeks Estimation**: Uses finite differences and variance reduction techniques  
- 📈 **Robust Validation**: Includes convergence and sensitivity tests  
- 🌍 **Real‑world Inputs**: Applied real market data in modeling

## 📦 Requirements

- Python 3.8+  
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scipy`

## 🧭 Setup & Usage

1. Clone the repo:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Execute scripts:
    - `correlation_analysis.py` – performs correlation study and visualizations  
    - `lookback_pricing.py` – runs Monte Carlo simulations for pricing  
    - `greeks_convergence.py` – computes Greeks and runs convergence/sensitivity tests

## 🧪 Results

- Heatmaps & scatter plots illustrating asset correlations  
- Option prices for different lookback structures  
- Greeks estimates with convergence behavior plots  
- Sensitivity analyses showcasing model robustness

## 🛠️ Extend & Contribute

- Support for other exotic option types  
- Integration of alternative underlying assets or volatility models  
- Optimization, parallelization, GPU acceleration

Contributions, enhancements, and feedback are welcome!

## 📄 License

This project is MIT‑licensed. See [LICENSE](LICENSE) for details.
