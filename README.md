# 📊 Fear vs Greed Trader Analysis

## 📌 Overview

This project analyzes how market sentiment (Fear vs Greed) impacts trader performance and behavior.
It focuses on key metrics such as:

* Profit & Loss (PnL)
* Win Rate
* Trade Frequency
* Position Size
* Long/Short Bias

The goal is to understand whether traders perform differently and change behavior under different sentiment regimes.

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/fear-vs-greed-trader-analysis.git
cd fear-vs-greed-trader-analysis
```

### 2. Create virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

### Option 1: Run Jupyter Notebook

```bash
jupyter notebook
```

* Open the notebook inside `/notebooks`
* Run cells step by step to reproduce analysis and charts

---

### Option 2: Run Python Script (if applicable)

```bash
python src/main.py
```

---

## 📊 Key Analysis Performed

* PnL distribution across sentiment regimes
* Win rate comparison (Fear vs Greed)
* Trade frequency and activity patterns
* Position sizing behavior
* Long vs Short bias analysis
* Trader segmentation (e.g., high vs low win rate)

---

## 📈 Outputs

* Boxplots (PnL distribution)
* Bar charts (Win rate, trade size, frequency)
* Summary tables for sentiment comparison

---

## 🧠 Key Insights

* Win rate remains relatively stable across sentiment regimes
* PnL variability increases during Fear periods
* Traders are more active and take larger risks during Fear
* Greed phases show more controlled and cautious behavior

---

## 📌 Requirements

* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn
* jupyter

---

## 🚀 Future Improvements

* Add statistical significance tests
* Include leverage analysis
* Build predictive sentiment-based trading model

---

## 👤 Author

Manish Chaudhary

---
