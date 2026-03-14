
# Hyperliquid Trader Sentiment Analysis

This project analyzes trader behavior on Hyperliquid in relation to Bitcoin market sentiment (Fear/Greed) and provides actionable insights. It includes a lightweight **Gradio dashboard** and an API for clients to explore trader metrics, top traders, and strategy rules.

---

## Features

- Clean and align **trader data** with **daily market sentiment**
- Calculate key metrics per trader per day:
  - Daily PnL
  - Number of trades
  - Average trade size
  - Average leverage
  - Win rate
  - Long/short ratio
  - Trader clusters (aggressive, conservative, balanced)
- Analyze trader behavior during **Fear vs Greed days**
- Provide **actionable trading rules**:
  - Adjust leverage and trade size/frequency based on sentiment
- Predict **next-day profitability** using simple models (optional)
- Interactive **Gradio dashboard** to explore metrics
- REST API for integration with client applications

---

## Dataset

1. **Bitcoin Market Sentiment (Fear/Greed)**  
   - Columns: Date, Classification  
   - Source: [Insert your link here]

2. **Hyperliquid Historical Trader Data**  
   - Columns: account, symbol, execution price, size, side, time, start position, event, closedPnL, leverage, etc.  
   - Source: [Insert your link here]

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/hyperliquid-analysis.git
cd hyperliquid-analysis
