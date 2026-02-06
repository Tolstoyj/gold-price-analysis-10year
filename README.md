# Gold Price Analysis — 10-Year Historical Data

Exploratory analysis and time-series forecasting on 10 years of gold price data: EDA, feature engineering, baselines, and a comprehensive forecasting benchmark (statistical, Prophet, ML, LSTM).

---

## Data & attribution

**Dataset:** [Gold Price analysis 10-Year Historical Data](https://www.kaggle.com/datasets/sanaijlalshahrukh/gold-price-analysis-10-year-historical-data)  
**Source:** Kaggle  
**Author:** [Sana Ijlal Shahrukh](https://www.kaggle.com/sanaijlalshahrukh)  
**Description:** Comprehensive gold futures analysis with 50+ engineered features.

This project uses the above dataset. All credit for the dataset goes to **Sana Ijlal Shahrukh**. If you use this repository or the dataset, please acknowledge the dataset owner and link to the Kaggle dataset page.

---

## Repository structure

```
.
├── README.md
├── gold_historical_data.csv    # Dataset (or add via Kaggle input)
└── notebooks/
    ├── 01_gold_price_eda.ipynb
    ├── 02_feature_engineering_and_baselines.ipynb
    ├── 03_comprehensive_time_series_forecasting.ipynb
    └── 04_seasonality_and_calendar_effects.ipynb
```

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| **01_gold_price_eda** | Data load, quality checks, feature engineering (returns, rolling stats, drawdown), distributions, trend/volume, seasonality. |
| **02_feature_engineering_and_baselines** | Temporal train/val split, technical indicators (RSI, MACD, ATR), naive/rolling/Ridge baselines, MAE/RMSE/MAPE. |
| **03_comprehensive_time_series_forecasting** | Full benchmark: baselines (naive, MA, drift), exponential smoothing, SARIMAX, Prophet, ML (Linear, RF, XGBoost, LightGBM, CatBoost), LSTM, leaderboard, 60-day projection. |
| **04_seasonality_and_calendar_effects** | Decomposition and calendar effects (month, weekday). |

---

## Setup & run

1. **Clone and enter the repo**
   ```bash
   git clone https://github.com/YOUR_USERNAME/gold-price-analysis-10year.git
   cd gold-price-analysis-10year
   ```

2. **Data**
   - Either place `gold_historical_data.csv` in the repo root (from [Kaggle](https://www.kaggle.com/datasets/sanaijlalshahrukh/gold-price-analysis-10-year-historical-data)), or  
   - On Kaggle: add the dataset as input; the notebooks resolve the path automatically.

3. **Environment**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels xgboost lightgbm catboost prophet tensorflow
   ```

4. **Run**
   - Open the notebooks in Jupyter or run on [Kaggle](https://www.kaggle.com/datasets/sanaijlalshahrukh/gold-price-analysis-10-year-historical-data/code) (recommended for data access).

---

## License

Code in this repository is shared for learning and reference. The dataset is subject to the terms and license on its [Kaggle page](https://www.kaggle.com/datasets/sanaijlalshahrukh/gold-price-analysis-10-year-historical-data); please credit **Sana Ijlal Shahrukh** when using or referencing the data.
