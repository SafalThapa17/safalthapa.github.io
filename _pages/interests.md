---
permalink: /interests/
title: "Quant Research"
author_profile: true
---

My interest in quantitative research began during my M.S. in Data Science and Engineering, when classroom lectures introduced me to how statistics and programming can be used to study financial markets. To learn more, I joined the WallStreetQuants bootcamp, where I work on mentored research projects. Outside the program, I read books on quantitative research and build personal projects to explore and test ideas on my own.

I want to apply my background in statistics and Python to financial problems, such as finding patterns in asset returns, measuring risk, and testing whether a signal holds up after accounting for realistic trading costs and evaluating it on out-of-sample data.

## Research

### Crypto Cross-Sectional Factor Research: Short-Term Reversal
*Mentored research project · WallStreetQuants · 2026*

**Question:** Does a cross-sectional reversal strategy work across liquid altcoins after removing Bitcoin exposure, and can it survive transaction costs?

**Design**
- **Universe:** 25 liquid altcoins, each with a pre-2022 90-day median dollar volume above $20M
- **Beta neutralization:** rolling 60-day OLS regression on BTC-USD to remove Bitcoin-driven returns
- **Evaluation:** signal research on 2022–2024; post-tuning evaluation on 2025 onward; 252-day annualization; 20 bps transaction costs per unit traded

**Findings**
- **The signal is real in-sample.** Short-term rank reversal was statistically significant: 3-day residual rank IC of −0.041 (t = −3.02), and −0.046 across all days with Newey–West errors (t = −4.4, n = 1,093).
- **It did not become a profitable strategy.** Despite a 52% daily win rate, the 3-day reversal spread was −8.7 bps/day (t = −1.12). Extreme moves hurt both legs: HBAR surges hit the shorts, and the SOL crash of 2022-11-08 hit the longs. Clipping individual coin returns turned the spread slightly positive (+1.6 bps/day), but not significantly (t = 0.25).
- **Volume conditioning was not a reliable fix.** Reversal looked stronger on high-volume days, but the difference was not significant in-sample (p = 0.77) or out-of-sample (p = 0.51).
- **The signal decayed out-of-sample.** From 2025, only the 1-day IC stayed significant (−0.027, t = −2.48). The selected 5-day strategy had net Sharpe ratios from −1.52 to −0.61 across five rebalance start days, losing about 8.4% a year before costs and 17.4% after.

**Limitations:** holding period and rebalance cadence were chosen from a 12-configuration grid (selection bias); the 2025+ period is post-tuning, not a strictly blind holdout; delisted coins such as FTT and LUNA were missing (survivorship bias); borrow fees and funding rates were not modeled.

**Takeaway:** A statistically significant ranking signal is not the same as a tradable strategy. Fat-tailed moves, weak return-level predictability, out-of-sample decay and costs together erased the edge.


## Quantitative Toolkit

| Area | Skills |
| --- | --- |
| Mathematics | Linear algebra, probability theory |
| Statistics | Regression, hypothesis testing, time-series analysis|
| Finance | Backtesting, portfolio construction, performance metrics (Sharpe ratio, drawdown) |
| Machine learning | Supervised learning, cross-validation, feature engineering |
| Programming | Python ([NumPy, pandas, scikit-learn]), SQL, C++ |
