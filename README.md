<img src="assets/banner.svg" width="100%" alt="Retail: from EDA to Forecast. A complete exploratory analysis of an extensive online-retail dataset, carried all the way to a forecast with uncertainty.">

## The question

A complete **exploratory data analysis** of an extensive online-retail dataset, carried through to **classification and time-series forecasting**. The goal is insight for the business teams responsible for decisions, with techniques that apply to any marketing dataset.

## The chapters

1. Sales and revenue analysis
2. Customer segmentation
3. Cross-country analysis
4. Forecasting

## Methods

- Interactive dashboards
- **Dask** for larger-than-comfortable data
- Classification with **extreme gradient boosting** (XGBoost)
- Forecasting with **Prophet**

## Figures

<table>
<tr><td width="100%" valign="top"><img src="graphs/Actual%20vs%20Predicted%20Price%20for%202%20Years.png" width="100%" alt="Actual vs predicted total price over two years"><br><sub>Actual vs predicted total price over two years</sub></td></tr>
<tr><td width="100%" valign="top"><img src="graphs/Uncertainty%20Levels%20for%20Price%20Range%20for%202%20Years.png" width="100%" alt="Forecast with its uncertainty interval"><br><sub>Forecast with its uncertainty interval</sub></td></tr>
<tr><td width="100%" valign="top"><img src="graphs/total_price_comparison.png" width="100%" alt="Total price, year against year"><br><sub>Total price, year against year</sub></td></tr>
</table>

## Run it

1. Download `requirements.txt`.
2. Follow the instructions in [`Conda_Virtual_Env.txt`](Conda_Virtual_Env.txt).

`requirements.txt` is a full freeze of the original environment, and some entries point to local conda builds. If pip cannot resolve them, install the packages listed under *Built with* below.

Then open [`online_retail.ipynb`](online_retail.ipynb).

## Built with

`Python` · `NumPy` · `pandas` · `Matplotlib` · `Seaborn` · `Plotly` · `scikit-learn` · `Dask` · `Joblib` · `XGBoost` · `itertools` · `Prophet`

<br>

<p align="center"><sub><a href="https://github.com/johnnyk1090">← back to the profile</a></sub></p>
