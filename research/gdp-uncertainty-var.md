# US GDP and Financial Uncertainty: An Exploratory VAR Forecast

**Area:** Fixed income and macro research  
**Research status:** Historical time-series exercise; not a structural causal estimate or a live market signal.

## Question

Can a measure of financial-market uncertainty add information to a simple autoregressive forecast of changes in US real GDP?

## Data and modelling choices

The original `Forecast with Uncertainty (4).ipynb` notebook requests **real GDP (FRED: GDPC1)** and **daily VIX (FRED: VIXCLS)** over a 2000–2024 sample. It constructs a quarterly standard-deviation measure from VIX observations, aligns it with quarterly GDP, and works with differenced series.

Implemented methods include:

- ADF stationarity checks and time-series visualisation.
- Lag-order inspection, a **five-lag bivariate VAR**, equation coefficients and residual diagnostics.
- Generalised/estimated impulse-response visualisations, forecast-error variance decomposition and Granger causality tests.
- A holdout exercise comparing an **eight-quarter VAR forecast** with an **AR(1)** GDP benchmark.

The saved notebook prints an eight-quarter GDP-difference RMSE of approximately **80.28** for the VAR versus **83.71** for the AR(1). These are original saved-output values in the notebook's GDP-difference units, not a new independent evaluation.

## Interpretation for an investment audience

The exercise explores the relationship between real activity, financial-market volatility and forecasting uncertainty. It provides a starting point for studying which data help form a macro view; it **does not** by itself specify a rates, FX or equity position.

## Limitations and next validation steps

- A quarterly standard deviation of VIX is a **constructed volatility proxy**, not a directly observed or exogenous uncertainty shock. Economic interpretation depends on this choice.
- The eight-quarter holdout is small. The modest RMSE difference should not be advertised as durable predictive superiority.
- Granger predictability does not imply structural causality; orthogonalisation and variable ordering need care.
- Some exploratory VARMAX/rolling-forecast cells in the original notebook contain alignment problems or recorded errors. They are excluded from headline claims.
- A stronger release would use fixed transformations, a longer rolling-origin evaluation, multiple benchmark models, documented vintage handling and formal checks of residual stability.

## Evidence of skills

Economic data retrieval; frequency aggregation; stationarity; multivariate time-series modelling; forecast benchmarking; statistical interpretation; identification limitations; and research communication.

**Source:** [Inspect the source-only exploratory notebook](notebooks/gdp-uncertainty-var-exploratory.ipynb). The original code and research narrative are public without saved outputs; unresolved exploratory VARMAX cells mean it is **not yet a verified end-to-end reproducible release**.

[All selected research](README.md)
