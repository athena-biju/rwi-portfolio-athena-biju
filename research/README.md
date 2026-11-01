# Selected investment research | Athena Biju

**MSc Economics, London School of Economics (2026–2028 expected)**  
**Research interests:** macroeconomic uncertainty, event-driven asset pricing, company fundamentals, institutional risk and analytical decision-making.

This is a concise research index for investment recruiters. It links methods to investment questions, explicitly distinguishes completed empirical exercises from independently validated trading strategies, and provides pointers to public source material where available.

## Start here

| Research question | Project | Methods | Research status |
| --- | --- | --- | --- |
| How do index inclusion announcements relate to abnormal equity returns and volume? | [S&P 500 index-inclusion event study](index-inclusion-event-study.md) | Market-model OLS, abnormal returns, cumulative abnormal returns, volume, t-tests, residual bootstrap | Exploratory retrospective event study; event timing and execution assumptions require validation |
| Does a multivariate uncertainty proxy improve short-run US GDP forecasts? | [GDP and uncertainty VAR](gdp-uncertainty-var.md) | FRED, quarterly alignment, ADF, VAR(5), impulse responses, Granger tests, eight-quarter holdout versus AR(1) | Exploratory forecasting; small holdout and proxy limitations |
| What does company-level financial analysis reveal about liquidity resilience? | [Unilever financial diagnostics](unilever-financial-diagnostics.md) | SEC XBRL, ratio decomposition, peer comparisons, narrative text analysis, scenario analysis | Co-authored group report; predictive-model leakage identified and not promoted as validated forecasting |
| How do financing assumptions change the distribution of venture value? | [MAAT Financial Engine](https://github.com/athena-biju/financial-engine-valuation-simulator) | Python, cash-flow scenarios, Monte Carlo, terminal-value sensitivity | Public exploratory source; illustrative assumptions |
| How do norm-induced labour frictions affect counterfactual output? | [Behavioural Macro-Friction](https://github.com/athena-biju/behavioural-macro-friction) | Production functions, counterfactual paths, welfare simulation | Public conceptual simulations, not a fully estimated structural OLG model |
| Can financial transaction decisions be made inspectable? | [ASPASIA](https://github.com/athena-biju/aspasia) | Python, Streamlit, FastAPI, YAML policy rules, decision traces | Public prototype; not a production compliance system |

## Institutional signalling and political economy

- [How Capitalism Abstains — UN voting volatility, abstention and varieties of capitalism](how-capitalism-abstains-institutional-signalling.md) — completed 2025 course paper, documented as a descriptive comparative-political-economy exercise; explains how the separate exploratory V-Dem governance-indicator notebook may inform a later extension, without claiming an established empirical link.

## Methodological commitments

- Separate **description** from **causal inference**, and **in-sample fit** from **out-of-sample prediction**.
- Disclose model assumptions, target construction, missing data, look-ahead risks and failed specifications.
- Avoid publishing unsupported Sharpe ratios, simulated investment returns, and synthetic forecasts as realised performance.
- Respect academic collaborators' authorship and restrictions on institutional datasets.
- Describe investment implications as **research questions or hypotheses** unless an actionable trade and validation are documented.

Source-only notebooks are now public for the index-inclusion and GDP–uncertainty projects: [event-study code](notebooks/sp500-inclusion-eventstudy-exploratory.ipynb) and [macro VAR code](notebooks/gdp-uncertainty-var-exploratory.ipynb). These are **archival code snapshots with stored outputs removed**, not verified one-command reproductions. The co-authored Unilever report and its forecasting notebooks are not republished here.

## Supplementary research archives

- [GDELT global geographic graph exploration](notebooks/gdelt-global-graph-source-only.ipynb) — source-only notebook; source manifest and datasets are not bundled.
- [Stablecoin governance and fragility exploration](notebooks/stablecoin-rule-rigidity-source-only.ipynb) — source-only notebook; exploratory model assumptions and external-data requirements apply.

These supplementary archives have saved outputs removed. They are not independently reproduced empirical findings or investment-performance records.

[Main portfolio](../README.md) · [GitHub account](https://github.com/athena-biju)
