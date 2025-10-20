# Stock Market Predictor 📊

Predict whether the **next day’s closing price** of an S&P 500 stock will rise or fall using a notebook-first workflow.

## 🧠 Overview
This project explores a complete ML pipeline inside one notebook:
- Download and clean historical stock data
- Engineer predictive features
- Train and evaluate a Random Forest Classifier
- Backtest accuracy across multiple years of S&P 500 data

---

## 📁 Repository Structure
stock-predictor/
├─ start.ipynb # Main notebook for data prep, training, and evaluation
└─ .ipynb_checkpoints/ # Auto-saved Jupyter checkpoints

## ⚙️ Setup & Usage
1. **Clone this repo**
   ```bash
   git clone https://github.com/Rohan1x/stock-predictor.git
   cd stock-predictor


(Optional) Create and activate a virtual environment

python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

source .venv/bin/activate

Install dependencies

pip install pandas numpy scikit-learn matplotlib yfinance


Open the notebook

jupyter lab    # or jupyter notebook


Run all cells in start.ipynb to reproduce the workflow.
