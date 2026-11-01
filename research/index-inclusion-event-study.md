# S&P 500 Index-Inclusion Announcements: An Event-Study Exercise

**Area:** Event-driven equities / capital markets  
**Research status:** Retrospective empirical exercise; not a backtested trading strategy.

## Question

Do equity index-inclusion announcements coincide with statistically distinguishable abnormal returns or trading-volume changes? How do measured reactions differ between the pre-announcement, announcement and subsequent trading-day windows?

## Research implementation

The original Jupyter notebook (`EventStudyICM.ipynb`, March 2026) implements:

1. An event list of **19 candidate S&P 500 inclusion announcements** from 2024–2026.
2. Historical adjusted prices and volumes requested using `yfinance` for each stock and the **S&P 500 index (`^GSPC`)**.
3. Stock and benchmark daily returns, with a market model estimated using OLS on a preceding window (in the cross-event implementation, trading days **−131 to −11**).
4. Abnormal return `AR_t = R_stock,t − (alpha + beta × R_market,t)`, cumulative abnormal returns and abnormal log volume over an event window of **−10 to +10**.
5. Event-level pre-/post-window summaries, one-sample tests and bootstrap residual-based null envelopes for cumulative abnormal returns.

A saved run successfully constructed panels for **14 of the 19 candidate events**. This is a retained notebook result, *not* an independently repeated data pull.

## Investment interpretation

Index reconstitutions can change mechanical demand, attention and liquidity. An event-study framework is relevant to understanding whether an observed stock move exceeds its market-model expectation. But abnormal announcement-window returns are **not** equivalent to returns available to an investor who observes the public announcement and then trades.

## Principal limitations

- Candidate announcement dates and effective dates require source-by-source verification against original index announcements. After-hours timing and the precise first tradable moment matter.
- Five candidate events were excluded by data availability or window completeness; results may be sensitive to sample selection.
- `^GSPC` is an index-return proxy. A tradable benchmark, costs and execution assumptions would require separate testing.
- Events may coincide with earnings, corporate actions or other confounders. Cross-event independence should not be assumed.
- Null-bootstrap envelopes and t-tests depend on model and residual assumptions; no claim of causal identification or profitable alpha is made.

## What this demonstrates

Event definition; data joining; expected-return modelling; event-window design; sample-eligibility rules; visualisation; uncertainty quantification; and appropriate caution in translating statistical evidence into an investment claim.

**Source availability:** The full original notebook is retained in the author's research files. A cleaned public source release is pending a separate event-date, licensing and reproducibility review. This page is a methodological research note, not proof of an executable trade.

[All selected research](README.md)
