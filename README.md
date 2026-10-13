# Week 4 Time-Series Forecasting — Ioannis Tzalas

Continues [Week 1](https://github.com/flappybird69/week1-financial-analysis-ioannis-tzalas), [Week 2](https://github.com/flappybird69/week2-data-hygiene-ioannis-tzalas) and [Week 3](https://github.com/flappybird69/week3-fintech-assignment-ioannis-tzalas), with SPY, EUR/USD, BTC, GLD and ETH.

- [`W4_assignment_Tzalas.ipynb`](W4_assignment_Tzalas.ipynb): executed assignment with the forecast code audit, stationarity tests, ARMA selection, mean and variance forecast comparisons, GARCH fan charts, eleven evaluation rules and the optional ETH/BTC cointegration experiment.
- [`W2_own_calendar_prices.csv`](W2_own_calendar_prices.csv): the frozen Week 2 price panel, retaining each asset’s observed dates independently, including crypto weekends.
- [`requirements.txt`](requirements.txt): dependencies for reproduction.

The holdout begins on 2024-10-01. Input data and the reused course functions are embedded in the notebook, so it runs offline. Use a Python 3 kernel and **Restart & Run All** after installing the dependencies. Results and charts regenerate in the current working directory.

The notebook contains the visible results and interpretations. Evaluation-rule FAIL states identify unsupported model claims; they are not execution errors. The lecturer’s unexecuted synthetic SPY reference was regenerated separately from the real five-asset analysis.
