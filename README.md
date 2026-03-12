# 📊 S&P500 Market Direction Predictor

A machine learning model that predicts whether the S&P500 index will close higher or lower tomorrow. Built with Python and Jupyter, this project explores whether a machine learning model can uncover patterns in financial markets.<br>
This project was driven purely by my own self-curiosity and interest in the financial markets. 

## 👨🏼‍💻 Technologies
- `Python`
- `Jupyter Notebook`
- `pandas` (data manipulation)
- `sklearn` (Random Forest Classifier)
- `yfinance` (market data)
- `matplotlib` (visualisations)

## 📌 Features
- **Direction prediction** — *binary classifier for up/down days*
- **Feature engineering** — *created price ratios and momentum indicators across multiple time horizons (2,5,60,250,1000 days)*
- **Backtesting framework** — *rolling window validation to simulate real-world performance*
- **Probability threshold tuning** — *optimized for precision (60% confidence threshold)*
- **30+ years of data** — *trained on S&P500 data from 1990-2026*

## 📚 Results
- **57.7% precision** on up-day predictions (better than random 50%)
- Conservative strategy: only predicts "up" when model is highly confident
- Robust backtesting across thousands of trading days

## 🚀 Getting Started
To run this project locally:

1. Clone the repository
2. Install dependencies: `pip install yfinance pandas scikit-learn matplotlib jupyter`
3. Launch Jupyter: `jupyter notebook`
4. Open `sp500_predictor.ipynb` and run all cells


