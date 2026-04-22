# 📊 Trader Sentiment Analysis

## 📌 Overview

This project analyzes how market sentiment (Fear vs Greed) impacts trader behavior and performance.
By combining trading data with the Fear & Greed Index, we uncover patterns in profitability, risk-taking, and trading activity.

---

## 🎯 Objectives

* Analyze trader performance across different market sentiments
* Understand behavioral changes during Fear vs Greed
* Identify patterns in trade size, frequency, and win rate
* Segment traders based on activity levels

---

## 📂 Dataset

* **Fear & Greed Index** (`fear_greed_index.csv`)
* **Trading Data** (`historical_data.csv`)

---

## ⚙️ Workflow

1. **Data Loading**

   * Loaded sentiment and trade datasets using Pandas

2. **Data Cleaning**

   * Converted timestamps to datetime format
   * Standardized date columns for merging

3. **Feature Engineering**

   * Created `win` column (profitability indicator)
   * Extracted date from timestamps
   * Merged datasets on date

4. **Analysis**

   * Average PnL by sentiment
   * Win rate by sentiment
   * Trade count distribution
   * Average trade size

5. **Visualization**

   * Boxplot: PnL vs Sentiment
   * Bar charts: Win rate & Trade count

---

## 📈 Key Insights

### 1. Risk-taking increases during Greed phases

Traders not only trade more frequently but also increase their position sizes, indicating higher risk appetite.
This leads to higher average PnL but also greater variability in returns.

### 2. Fear leads to defensive trading behavior

During Fear periods, trade frequency and position sizes decline, suggesting that traders become cautious and reduce exposure to the market.

### 3. Performance asymmetry across sentiment regimes

While Greed periods show higher profitability, Fear periods are associated with lower win rates and more inconsistent outcomes, likely due to panic-driven decisions.

---

## 🧠 Trader Segmentation

* **Frequent Traders**
* **Infrequent Traders**

### Findings:

* Frequent traders tend to generate higher PnL during Greed phases
* Infrequent traders show more stable but lower returns

---

## 📊 Results Summary

| Metric          | Observation               |
| --------------- | ------------------------- |
| Average PnL     | Higher in Greed           |
| Win Rate        | Higher in Greed           |
| Trade Frequency | Peaks during Fear & Greed |
| Trade Size      | Larger during Greed       |

---

## 💡 Strategy Recommendations

### During Fear:

* Reduce position size
* Avoid overtrading
* Focus on risk management

### During Greed:

* Increase activity cautiously
* Avoid overconfidence
* Use stop-loss strategies

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/trader-sentiment-analysis.git
```

2. Open the notebook:

```bash
trader-sentiment-analysis.ipynb
```

3. Run all cells

---

## 📌 Conclusion

Market sentiment has a strong influence on trader behavior and performance.
Greed drives higher risk and returns, while Fear leads to cautious and inconsistent trading outcomes.

---

## 👤 Author

**Rahi Basu**
