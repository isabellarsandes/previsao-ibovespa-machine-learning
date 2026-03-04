# IBOVESPA Trend Prediction

Machine learning model to predict whether the IBOVESPA index will close higher or lower on the next day using historical market data.

---

## Project Context

This project simulates the work of a data scientist in an investment fund, where the goal is to develop a predictive model capable of identifying the next-day trend of the IBOVESPA index.

The model is designed to support internal dashboards used by quantitative analysts, helping them interpret market behavior and assist decision-making processes.

---

## Objective

The main objective of this project is to build a predictive model that determines whether the IBOVESPA closing price on the next trading day will be higher or lower than the current day.

---

## Dataset

Historical IBOVESPA data was collected from:
https://br.investing.com/indices/bovespa-historical-data

Configuration used:

- Frequency: Daily
- Period: At least 2 years of historical data

Main variables include::

- Date -> Trading date
- Last -> Closing price of the IBOVESPA index for the day
- Open -> Opening price at the beginning of the trading session
- High -> Highest price reached during the trading day
- Low -> Lowest price reached during the trading day
- Vol. -> Trading volume during the day
- Var% -> Daily percentage variation of the index
