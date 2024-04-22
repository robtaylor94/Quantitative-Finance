# Quantitative-Finance
A repository of active or partial projects pertaining to computational and quantitative finance.

Notebooks in this repo predominantly derive from a multi-asset MVO-like momentum strategy used to allocate personal funds c. 2022-2023, which used LightGBM for the trend component and Stochastic GPR for the noise term as portfolio optimisation return input params, and used higher moments and drawdown measures for risk targeting. ETF closing prices were retrieved from a MS SQL Server instance with tables populated with AlphaVantage's API but these are made to run from flat files for the sake of replication.
