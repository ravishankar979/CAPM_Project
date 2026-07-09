# 📈 CAPM Return Calculator

A web application built with **Python** and **Streamlit** that calculates the **expected return of stocks using the Capital Asset Pricing Model (CAPM)**. The application fetches real-time stock market data from **Yahoo Finance**, computes the Beta of selected stocks against a benchmark index, and estimates expected returns with interactive visualizations.

---

## 🚀 Features

- 📊 Calculate expected stock returns using the CAPM model
- 📈 Fetch real-time historical stock prices from Yahoo Finance
- 📉 Compute Beta values of stocks relative to a market index
- 📅 Select custom date ranges for analysis
- 📊 Interactive charts using Plotly
- ⚡ Fast and responsive Streamlit interface
- 🖥️ Simple and user-friendly web application

---

## 🛠️ Built With

- Python
- Streamlit
- Pandas
- NumPy
- Plotly
- yFinance
- pandas-datareader
- Matplotlib

---

## 📂 Project Structure

```
CAPM/
|-- pages
   |-- Calculate_beta.py
│── CAPM_Return.py          # Main Streamlit application
│── capm_functions.py       # Functions for CAPM calculations
│── README.md
│── .gitignore
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/CAPM-Return.git
cd CAPM-Return
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the application

```bash
streamlit run CAPM_Return.py
```

If `streamlit` is not recognized:

```bash
python -m streamlit run CAPM_Return.py
```

---

## 📖 How It Works

1. Enter one or more stock ticker symbols.
2. Select a benchmark market index.
3. Choose the analysis period.
4. The application downloads historical data from Yahoo Finance.
5. Beta values are calculated.
6. CAPM is applied to estimate the expected return.
7. Interactive charts and results are displayed.

---

## 📊 CAPM Formula

\[
E(R_i)=R_f+\beta_i(R_m-R_f)
\]

Where:

- **E(Rᵢ)** = Expected Return
- **R_f** = Risk-Free Rate
- **β** = Beta of the Stock
- **R_m** = Expected Market Return

---
## 📦 Dependencies

- streamlit
- pandas
- numpy
- plotly
- matplotlib
- yfinance
- pandas-datareader

Install them using:

```bash
pip install -r requirements.txt
```

---

## 👨‍💻 Author

**Ravishankar Kumar**
- GitHub: https://github.com/ravishankar979
