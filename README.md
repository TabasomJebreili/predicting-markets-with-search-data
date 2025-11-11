# Search Trends vs Financial Data

This is a personal data analysis project exploring whether public search behavior on Google reflects or even predicts real-world economic and financial patterns.

Using search volume data from Google Trends for keywords like **"Unemployment Benefits"**, **"Tesla"**, and **"Bitcoin"**, I compared the trends with actual indicators such as:

- U.S. **Unemployment Rate**
- **Tesla (TSLA)** Stock Price
- **Bitcoin (BTC-USD)** Price

---

## 📊 Goal

To analyze and visualize whether spikes in Google search interest align with or lead changes in financial or economic data.

## 🔗 Data Sources

- [Google Trends](https://trends.google.com/trends/explore) – for keyword search volume  
- [FRED - Unemployment Rate](https://fred.stlouisfed.org/series/UNRATE)  
- [Yahoo Finance – Tesla (TSLA)](https://finance.yahoo.com/quote/TSLA/history?p=TSLA)  
- [Yahoo Finance – Bitcoin (BTC-USD)](https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD)

---

## 🧠 What I Did

- Collected and cleaned data from multiple sources  
- Merged Google search interest with financial and economic datasets  
- Calculated 3-month and 6-month rolling averages  
- Plotted and compared time-series data to examine lead/lag relationships  

---

## 📌 Tools Used

- Python  
- Pandas, Matplotlib, Seaborn  
- Pytrends  
- Yahoo Finance API  
- Jupyter Notebook

---

## 📈 Key Insight

Searches for **"Unemployment Benefits"** tend to increase **before** unemployment rates rise — suggesting a predictive signal.  
Similarly, search interest around **Tesla** and **Bitcoin** often tracks price volatility in those markets.

---

## 🚀 Future Ideas

- Add more keywords and regions  
- Try correlation analysis or time-lag cross-correlation  
- Train a simple predictive model based on search trends

---

Feel free to explore or build upon this project!
