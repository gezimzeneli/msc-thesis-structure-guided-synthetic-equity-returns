# Synthetic Equity-Price Scenario Generation

This repository serves as the computational appendix to the thesis on generating and evaluating synthetic equity-price scenarios under oil-price and interest-rate shocks.

The project compares a structured model approach with a regression-based benchmark. The structured model connects company financial statements, shock exposures, accounting relationships and equity valuation to simulated stock-price paths. The regression model uses historical relationships between stock returns, oil prices and interest rates to generate comparison scenarios.

The analysis evaluates the models at both company and portfolio levels. It examines accounting consistency, responses to shocks, return distributions, volatility behaviour and historical comparisons. Portfolio analysis considers cross-company dependence, value at risk, expected shortfall, risk contributions and drawdown.

The notebooks document the implementation and supporting analyses. The thesis provides the theoretical background, methodological assumptions and interpretation of the results.

## Installation

Install the required libraries and JupyterLab with:

```bash
python -m pip install jupyterlab numpy pandas matplotlib scipy modelx pandas-market-calendars pyarrow nbformat nbclient ipykernel ipython
```

Running the notebooks also requires the corresponding project data and supporting Python files.
