
# Crypto Market Pulse

A professional crypto market data visualizer and analyzer that scrapes real-time cryptocurrency statistics and generates a heatmap for easy insight.

## 🔍 Features
- Real-time data scraping (simulated in this version)
- Heatmap of 24-hour % changes in top cryptocurrencies
- Clean CSV output with prices, volume, and percentage change
- Python-based, easily customizable

## 🧰 Technologies Used
- Python 3
- pandas
- seaborn
- matplotlib

## 📦 Output
- CSV: `crypto_prices.csv`
- PNG: `heatmap.png`

## ▶️ How to Run

1. Install the required libraries:
```
pip install -r requirements.txt
```

2. Run the script:
```
python crypto_scraper.py
```

3. View output:
- `crypto_prices.csv` contains the clean data
- `heatmap.png` is the heatmap visualization

## ⚠️ Disclaimer
This demo uses simulated data. In a real-world application, CoinGecko’s free API can be used for real-time crypto market stats.

---

📌 Created with care by a freelance data engineer for demonstration purposes.
