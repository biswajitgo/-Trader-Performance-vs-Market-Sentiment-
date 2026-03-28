# 📊 Trader Performance vs Market Sentiment Analysis

## 📌 Overview

This project analyzes the relationship between **market sentiment (Fear vs Greed)** and **trader behavior and performance** using historical trading data.

The objective is to uncover patterns and generate actionable insights for smarter trading strategies.

---

## 📂 Datasets

1. **Bitcoin Market Sentiment Dataset**

   * Columns: Date, Classification (Fear/Greed)

2. **Trader Data (Hyperliquid)**

   * Includes: account, symbol, price, size, side, time, leverage, closedPnL, etc.

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🚀 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/trader-sentiment-analysis.git
cd trader-sentiment-analysis
```

---

### 2️⃣ Ensure Required Libraries Are Installed

If not already installed, run:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

*(Note: Libraries are already installed in Jupyter environment.)*

---

### 3️⃣ Add Dataset Files

Place the dataset files inside the project folder:

```
/data
   ├── fear_greed.csv
   ├── trader_data.csv
```

---

## ▶️ How to Run

### Run Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```
project.ipynb
```

Run all cells step-by-step.

---

## 📊 Project Workflow

1. Data Loading
2. Data Cleaning
3. Feature Engineering
4. Data Merging
5. Exploratory Data Analysis (EDA)
6. Insights Generation
7. Strategy Recommendations

---

## 💡 Key Insights

* Trader performance varies between Fear and Greed market conditions
* High leverage traders face higher risk during volatile periods
* Trade frequency and position sizes change based on sentiment

---

## 🎯 Strategy Recommendations

* Reduce leverage during Fear markets
* Use controlled position sizing during high volatility
* Adjust trade frequency based on sentiment signals

---

## 📈 Output

* Data visualizations (PnL, leverage, trade patterns)
* Insights backed by analysis
* Strategy recommendations

---

## 📌 Future Improvements

* Build predictive models for trader profitability
* Perform clustering of traders
* Develop a dashboard using Streamlit

---

## 📬 Submission

This project is submitted as part of a Data Science Intern assignment.

---
