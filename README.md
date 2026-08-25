# Residential Property Markets: Predictive Analytics

This group project applies predictive analytics and time-series forecasting to residential property markets in **Accra, London, and Mumbai**. The notebooks document data understanding, preparation, visualization, regression modeling, and forecasting workflows.

## Project objectives

The project compares property-market behavior across a developing economy, a developed economy, and an emerging economy. The analysis explores which property and market characteristics are associated with price and evaluates methods for forecasting average prices over time.

## Analysis included

| City | Main work | Methods explored |
|---|---|---|
| Accra, Ghana | Greater Accra property-price analysis | Linear regression, Lasso regression, three-month simple moving average, and ARIMA-style time-series analysis |
| London, United Kingdom | Borough-level property-price analysis | Linear regression, Ridge regression, three-month simple moving average, and Holt exponential smoothing |
| Mumbai, India | Property-price analysis and forecasting | Linear regression, Ridge regression, ARIMA-style analysis, and simple moving average forecasting |

## Workflow

The notebooks follow a practical predictive-analysis workflow: importing and understanding the data, checking data quality, preparing and encoding variables, handling outliers, engineering features, visualizing relationships, splitting data into training and testing sets, scaling features, fitting models, evaluating predictions, and producing recommendations.

The Accra notebook, for example, filters the records to Greater Accra, engineers variables such as price per square metre and distance from the central business district, and saves a regression-ready dataset. The London notebook works with borough-level records and includes crime-related information, while the Mumbai notebook combines regression and time-series techniques for property-price analysis.

## Repository contents

- `notebooks/accra.ipynb` — Accra property-sales analysis.
- `notebooks/london.ipynb` — London property-sales analysis.
- `notebooks/mumbai.ipynb` — Mumbai property-sales analysis.

## How to use the notebooks

Open the notebooks with Jupyter Notebook, JupyterLab, or Google Colab. The original data files referenced by the notebooks are not included in this upload, so the CSV files must be placed in the working directory before running the code. Do not upload datasets containing private, restricted, or confidential information.

The main Python libraries used include `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`, and `pmdarima`.

## My contribution

My contribution focused on **data sourcing and exploratory analysis**. I helped provide and organize datasets for the group, reviewed selected data for structure and analytical usefulness, and contributed to analysis of patterns in the property-market data. I worked collaboratively with the team to support the broader workflow from data preparation and exploration through to the interpretation of predictive results.

This was completed as a group project for a predictive-analysis class. The notebooks represent collaborative group coursework, while this section identifies the areas to which I personally contributed. The project strengthened my ability to work with real-world data, communicate analytical observations, and contribute effectively to a team-based data project.

## Learning outcomes

This project provided practical experience in exploratory data analysis, feature engineering, regression, regularization, time-series forecasting, model evaluation, and communicating analytical recommendations to a property-investment audience.

## Status

**Completed academic group project; portfolio documentation in progress.** This repository demonstrates my early experience contributing to a collaborative predictive-analytics workflow. Future improvements may include cleaned and reproducible data where permitted, clearer model-comparison tables, additional visualizations, and a more detailed discussion of limitations and business implications.
