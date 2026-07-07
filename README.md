# Crypto Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between cryptocurrency market sentiment (Fear & Greed Index) and trader performance using historical trading data. The objective is to understand how market sentiment influences trading behavior, profitability, and trading activity.

---

## Dataset

- **Historical Trading Data:** Contains trade details such as account, coin, trade size, direction, PnL, and timestamp.
- **Fear & Greed Index:** Contains daily market sentiment values and classifications.

---

## Methodology

1. Loaded both datasets using Pandas.
2. Checked for missing values, duplicate rows, and null values.
3. Converted timestamps into datetime format.
4. Created a common **Date** column for both datasets.
5. Merged the datasets using the **Date** column.
6. Calculated key metrics:
   - Daily PnL
   - Win Rate
   - Average Trade Size
   - Number of Trades per Day
7. Compared trader performance across different market sentiment categories.
8. Visualized the results using charts.

---

## Key Insights

- Trading performance varied across different market sentiment categories.
- Trading activity and average trade size changed depending on market conditions.
- Different trader segments were identified based on trading frequency and profitability.

---

## Strategy Recommendations

### Strategy 1
Trade more cautiously during Fear periods by reducing position size and focusing on high-confidence setups.

### Strategy 2
Maintain disciplined trading by avoiding overtrading and regularly reviewing trading performance.

---

## Project Structure

```
├── Task.ipynb
├── historical_data.csv
├── fear_greed_index.csv
├── charts/
├── README.md
```

---

## Requirements

Install the required libraries:

```bash
pip install pandas matplotlib numpy
```

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/balkrushnanaik/Crypto-Market-Sentiment-Analysis.git
```

2. Navigate to the project folder.

```bash
cd Crypto-Market-Sentiment-Analysis
```

3. Open the notebook.

```bash
jupyter notebook Task.ipynb
```

4. Run all cells to reproduce the analysis and charts.

---

## Output

The notebook generates:
- Cleaned and merged dataset
- Summary tables
- Performance metrics
- Charts comparing market sentiment with trader behavior
- Strategy recommendations
