# 🐋 Do Whales Move the Market? — Analyzing Large Transfers vs Price Movements on Arbitrum

## 📌 Project Overview
This project investigates whether large **"whale" transactions** on the **Arbitrum blockchain** have a measurable impact on the **ARB token price**.  
Over a **30-day period**, we analyzed **$1+ billion** worth of ARB transactions, combining **on-chain activity data** with **market price data**.

---

## 📊 Data Sources
- **[Dune API](https://dune.com/docs/api/)** — For fetching whale transaction data from the Arbitrum blockchain.  
- **[CoinGecko API](https://www.coingecko.com/en/api)** — For historical ARB token price data.

---

## 🛠️ Tech Stack
- **Language**: Python 3.x  
- **Libraries Used**:
  - `requests` — API data fetching  
  - `pandas` — Data wrangling & cleaning  
  - `numpy` — Numerical computations  
  - `scipy` — Statistical analysis (Pearson correlation)  
  - `matplotlib` & `seaborn` — Data visualization  

---

## 🔍 Methodology
1. **Data Collection**  
   - Queried Dune API for whale transaction data.  
   - Queried CoinGecko API for historical ARB price data.
   
2. **Data Processing**  
   - Merged datasets by timestamp.  
   - Normalized values for comparison.

3. **Statistical Analysis**  
   - Calculated Pearson’s correlation coefficient and p-value.  
   - Created scatter plots and line–bar visualizations.

4. **Visualization**  
   - Scatter plot for whale transactions vs. price impact.  
   - Line–bar plot comparing whale transaction volume with price change.

---

## 📈 Key Findings
| Metric                  | Value     | Interpretation                            |
|------------------------|-----------|--------------------------------------------|
| Correlation coefficient | -0.0246   | Very weak negative relationship           |
| P-value                 | 0.8973    | Not statistically significant              |

- **Conclusion**: Whale transactions showed no meaningful short-term effect on ARB price movement during the 30-day period analyzed.

---


## 🚀 How to Run the Project
1. **Clone the repository**  .
   
