# quantml

ML-powered quantitative trading strategies and backtests.

## momentum-strategy

A weekly long-only momentum strategy using an ensemble of Random Forest and Logistic Regression to predict positive next-week returns across 10 large-cap US stocks (2017–2025).

**Approach:** 8 momentum/technical features → ML classifier → rank stocks weekly → hold top 2 in equal weight → rebalance with transaction costs

**Out-of-sample results (2023–2025):**
- Cumulative Return: 92.89%
- Annualized Return: 38.88%
- Sharpe Ratio: 2.54
- Max Drawdown: -14.64%
- Hit Rate: 61.54%

**Stack:** Python · yfinance · scikit-learn · pandas · matplotlib

## View the notebook
[Click here to view the full analysis](https://github.com/spideyguy09/quantml/blob/main/momentum-strategy/Abhijeet_QuantQuest_ESummit26.ipynb)
