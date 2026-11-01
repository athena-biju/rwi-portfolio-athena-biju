# Athena Biju | Investment Research & Economic Analysis

**MSc Economics, London School of Economics (expected 2028)**  
**Experience:** short-term electricity-market forecasting, equity research, applied economic research, and quantitative teaching.

**Portfolio:** [Browse the research website](https://athena-biju.github.io/rwi-portfolio-athena-biju/) · [Selected investment research](research/README.md) · [All GitHub projects](https://github.com/athena-biju)

## Featured research: first three items to read

| Project | What I investigated | Techniques | What is actually available |
| --- | --- | --- | --- |
| [Index-Inclusion Event Study](research/index-inclusion-event-study.md) | Market-model abnormal equity returns and volume around S&P 500 additions | OLS, event windows, cumulative abnormal returns, residual bootstrap | Research note and [source-only notebook](research/notebooks/sp500-inclusion-eventstudy-exploratory.ipynb) |
| [US GDP and Financial Uncertainty](research/gdp-uncertainty-var.md) | Whether an uncertainty proxy adds information to quarterly GDP forecasts | FRED, ADF, VAR(5), impulse responses, Granger testing, holdout versus AR(1) | Methodological note summarising an original research notebook; public source release pending |
| [Unilever Financial Diagnostics](research/unilever-financial-diagnostics.md) | Whether strong operating performance coexists with liquidity risk | SEC/XBRL-style data, financial ratios, peer comparison, sentiment, stress scenarios | Research note based on a **four-author academic group report**; full report not republished |

## Directly inspectable GitHub work

- **[MAAT Financial Engine](https://github.com/athena-biju/financial-engine-valuation-simulator):** illustrative operating and valuation scenarios, Monte Carlo and sensitivity analysis. Code is exploratory, not an investment track record; some accounting and valuation assumptions require refinement.
- **[Behavioural Macro-Friction](https://github.com/athena-biju/behavioural-macro-friction):** simple production-function and welfare simulations involving a norm-induced labour friction. These do not comprise a fully estimated OLG model.
- **[ASPASIA](https://github.com/athena-biju/aspasia):** traceable policy-rule evaluation with Python, FastAPI and Streamlit demonstrators; not production compliance software.
- **[Institutional NLP](https://github.com/athena-biju/nlp-institutional-benchmarking):** exploratory sentiment and topic-modelling research involving public discourse and sampling limitations.
- **[Biodiversity finance data](https://github.com/athena-biju/mlr-biodiversity-finance):** dataset mapping and research-source evaluation.
- **[Research visualisation](https://github.com/athena-biju/green-lit-review):** exploratory dashboards and literature summaries.

## Research philosophy

The question is not just *what does the model predict?* but *what does the result permit us to conclude?* I separate exploratory analysis from out-of-sample validation; descriptive event studies from tradable returns; and conceptual simulations from empirically identified causal claims.

The site and README are a **research portfolio**, not a record of investments deployed, risk-adjusted trading returns, or a certification that every historical notebook can be rerun unchanged.

## Provenance, attribution and privacy

Group research is identified as such; shared institutional data and proprietary work are not reproduced without clearance. The site does not include private contact details beyond a professional correspondence channel, unredacted academic records, or confidential employer materials. AI assistance has been used in selected technical implementations and documentation as disclosed in individual repositories.

## Website implementation

- `site.html` — portfolio content and selected projects.
- `index.html` — entrance page and display enhancements.
- `design-v2.css` — site visual styling.
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow.

For deployment, enable GitHub Pages with **GitHub Actions** as source and confirm the workflow succeeds. A repository URL being present is not proof that GitHub Pages has been enabled.

[LinkedIn](https://www.linkedin.com/in/athenabiju) · [GitHub](https://github.com/athena-biju)
