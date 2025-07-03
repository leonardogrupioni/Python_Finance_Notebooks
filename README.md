# Quick‑Start Finance Notebook Pack 📈

A mini‑collection of **Jupyter notebooks** that demonstrate a typical market‑data workflow:

1. **Connect to Yahoo Finance** via its unofficial API  
2. **Retrieve & clean price series with Pandas**  
3. **Visualise the data** – including full OHLC *candlestick* charts

> 🏫 *Project developed during the **Imersão Python com Dados** by **Alura** (2024).*  

---

## 🗂️ Notebook Line‑Up

| Notebook | What it covers |
|----------|----------------|
| **`API_Connect_YahooFinance.ipynb`** | Plain requests call to fetch historical prices (JSON → DataFrame). |
| **`API_Connect_YahooFinance_Pandas.ipynb`** | Same task using *`pandas‑datareader`* for a cleaner pipeline. |
| **`CandleSticks_API.ipynb`** | Prepares an OHLC DataFrame (resampling, timezone fixes). |
| **`Plot_CandleSticks.ipynb`** | Draws interactive candlesticks with *plotly* / *mplfinance*. |

Run them in order or pick the one you need.

---

## 🚀 Quick Start

```bash
git clone ...
cd finance‑notebooks

python -m venv .venv          # optional virtual env
source .venv/bin/activate     # Windows: .venv\Scripts\activate

pip install -r requirements.txt
# (pandas yfinance pandas-datareader mplfinance plotly notebook)
```

Launch Jupyter:

```bash
jupyter lab            # or  jupyter notebook
```

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Jupyter Lab / Notebook**
- **pandas** & **numpy**
- **yfinance** *or* **pandas‑datareader**
- **mplfinance** & **plotly**

---

## 🙌 Credits

- **Alura** — *Imersão Python com Dados* bootcamp  
- Inspiration & teaching materials by the Alura data team
- Developed by **Leonardo Grupioni** as a learning exercise
