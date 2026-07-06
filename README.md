# 📊 Trader Behavior vs Market Sentiment Analysis

## Project Overview

This project analyzes historical cryptocurrency trading data alongside the Fear & Greed Index to understand how market sentiment influences trader behavior and profitability. The analysis combines multiple datasets, performs exploratory data analysis (EDA), and generates business insights through statistical summaries and visualizations.

---

## Objective

The primary objectives of this project are:

* Analyze historical trader performance.
* Explore the relationship between market sentiment and trading behavior.
* Identify profitability trends under different market conditions.
* Generate actionable business insights using data analysis.

---

## Dataset

### 1. Historical Trading Data

**File:** `historical_data.csv`

Contains information about cryptocurrency trades, including:

* Account
* Coin
* Execution Price
* Trade Size
* Trade Direction
* Closed Profit & Loss (PnL)
* Fees
* Timestamp

### 2. Fear & Greed Index

**File:** `fear_greed_index.csv`

Contains daily market sentiment information:

* Date
* Fear & Greed Value
* Sentiment Classification

---

## Tools & Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Structure

```text
trader-sentiment-analysis/
│
├── data/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── outputs/
│   ├── final_merged_dataset.csv
│   ├── profit_by_sentiment.csv
│   ├── volume_by_sentiment.csv
│   ├── win_rate.csv
│   ├── top_10_coins.csv
│   ├── sentiment_distribution.png
│   ├── pnl_by_sentiment.png
│   ├── top_10_traded_coins.png
│   └── daily_profit_trend.png
│
├── src/
├── venv/
└── README.md
```

---

## Workflow

### 1. Data Loading

* Imported historical trading data.
* Imported Fear & Greed Index data.

### 2. Data Understanding

* Checked dataset shape.
* Reviewed column names.
* Verified data types.
* Generated descriptive statistics.

### 3. Data Cleaning

* Checked missing values.
* Removed duplicate records.
* Converted timestamp columns to datetime.
* Created a common `Date` column for merging.

### 4. Data Integration

* Merged trading data with Fear & Greed Index using the `Date` column.
* Verified successful matching of records.

### 5. Exploratory Data Analysis (EDA)

Performed analyses including:

* Distribution of Closed PnL
* Distribution of Market Sentiment
* Buy vs Sell analysis
* Long vs Short positions
* Trading Volume analysis
* Top 10 traded coins
* Correlation analysis
* Daily profit trend

### 6. Business Analysis

Generated:

* Profit by Market Sentiment
* Trading Volume by Sentiment
* Win Rate by Sentiment
* Overall trading statistics

---

## Output Files

The project generates:

* `final_merged_dataset.csv`
* `profit_by_sentiment.csv`
* `volume_by_sentiment.csv`
* `win_rate.csv`
* `top_10_coins.csv`

Charts:

* Market Sentiment Distribution
* Closed PnL by Sentiment
* Top 10 Traded Coins
* Daily Profit Trend

---

## Key Findings

This project helps answer questions such as:

* Does market sentiment influence trader profitability?
* During which market conditions do traders execute more trades?
* Which cryptocurrencies are traded most frequently?
* How does trading volume change across Fear and Greed market phases?

---

## Future Improvements

Potential enhancements include:

* Predict trader profitability using machine learning.
* Forecast market sentiment trends.
* Build an interactive dashboard using Power BI or Tableau.
* Perform coin-specific profitability analysis.
* Add advanced risk metrics and portfolio analysis.

---

## Author

**Valishetty Anusha**

Data Analytics & Python Project

---

## License

This project is intended for educational purposes and internship portfolio demonstrations.

This README is suitable for an internship submission and clearly documents the project's purpose, workflow, outputs, and deliverables.
