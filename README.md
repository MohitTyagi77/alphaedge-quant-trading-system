# AlphaEdge: Quantitative Multi-Stock Backtesting Engine

## 📊 Overview
AlphaEdge is a quantitative intraday trading system designed to evaluate rule-based strategies across multiple NSE stocks under realistic market conditions. The system integrates price-action signals, risk management, and full transaction cost modeling to simulate real-world trading performance.

---

## 🚀 Key Results
- **Net Profit:** ₹141,691  
- **Return:** 47.2% (on ₹3,00,000 capital)  
- **Total Trades:** 253  
- **Win Rate:** 58.9%  
- **Sharpe Ratio:** 2.63  
- **Max Drawdown:** 8.47%  
- **Profit Factor:** 1.47  

---

## ⚙️ Strategy Logic
- Multi-stock intraday trading (5-minute timeframe)  
- Candlestick pattern detection:
  - Bullish/Bearish Engulfing  
  - Morning / Evening Star  
  - Three White Soldiers / Three Black Crows  
- ATR-based profit targets  
- Fixed stop-loss + trailing stop  
- Time-based exit (30 minutes)  

---

## 💰 Realistic Backtesting
The system incorporates detailed transaction cost modeling to ensure realistic performance evaluation:
- Brokerage  
- Securities Transaction Tax (STT)  
- GST  
- Exchange charges  
- Slippage  

---

## 📉 Strategy Performance
![Tearsheet](tearsheet.png)

---

## 🧠 Key Insights
- Transaction costs and slippage significantly impact profitability  
- Not all candlestick patterns contribute equally to performance  
- Risk management is critical for controlling drawdowns  
- A large portion of trades exited via time-based rules indicates scope for strategy refinement  

---

## 🛠 Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  

---

## 📁 Project Structure
```
alphaedge-quant-trading-system/
│
├── alphaedge_backtest.ipynb
├── tearsheet.png
└── README.md
```

---

## 📌 Future Improvements
- Walk-forward optimization  
- Strategy filtering for weak signals  
- Live trading integration (API-based execution)  
- Advanced performance analytics  

---

## 🤝 Contributions
Open to feedback, improvements, and discussions on quantitative trading systems.

---
