# ⏱️ Time Series Analysis Project

This project presents an end-to-end analysis of both **seasonal** and **non-seasonal** time series data using statistical modeling techniques such as ARIMA, SARIMA, and GARCH. It showcases exploratory analysis, model diagnostics, forecasting, and volatility modeling with clean, reproducible notebooks.

---

## 📁 Repository Structure

```
Time-Series-Forecasting/
│
├── seasonal/
│   ├── SARIMA_CrudeOil.ipynb      # Seasonal SARIMA forecasting notebook
│   └── data.csv.zip               # Monthly crude oil import dataset (compressed)
│
├── non-seasonal/
│   ├── ARIMA_GARCH_DBK.ipynb      # ARIMA + GARCH forecasting notebook
│   └── DBK.DE.csv                 # Deutsche Bank stock price dataset
│
├── Detailed Report/
│   └── Detailed Report.pdf        # Comprehensive analysis & findings
│
├── requirements.txt               # Python dependencies
├── .gitignore                     # Git ignore file
└── README.md                      # Project documentation
```


## 🔗 Dataset Sources

- 📉 **Non-Seasonal Dataset – Deutsche Bank Stock**  
  [Kaggle – DBK.DE from Frankfurt](https://www.kaggle.com/datasets/sandhyakrishnan02/deutsche-bank-equity-nyq-ger-and-fra-from-2010?select=DB.csv)

- 🛢️ **Seasonal Dataset – U.S. Crude Oil Imports**  
  [Kaggle – U.S. Crude Oil Imports](https://www.kaggle.com/datasets/alistairking/u-s-crude-oil-imports/data)

---

## 🛠 Tools & Libraries

- Python, Jupyter Notebook
- `pandas`, `numpy`, `statsmodels`, `arch`, `matplotlib`, `seaborn`, `sklearn`
- ADF test, Ljung-Box, GARCH, SARIMA, and Box-Jenkins methodology

---

## 📌 Project Highlights

- End-to-end time series forecasting workflow
- Proper stationarity transformation and diagnostics
- Volatility modeling for financial series using GARCH
- Clean directory structure for reproducibility

---

## 👨‍💻 Author

**Shreyas Reddy**  
_Time Series Analysis Project_  
[LinkedIn](https://www.linkedin.com/in/shreyas-reddy-a0b975197)
