# Awesome AI Trading Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Academic research on system trading, quantitative finance, and AI/ML-powered trading, curated and tier-ranked from arXiv.

A curated reading list of the strongest recent papers on **system trading**, **quantitative finance**, and
**AI/ML-powered trading**. The full list, grouped by sub-domain and tier, is in [papers.md](papers.md), and the
research landscape is mapped in [research-map.md](research-map.md).

## Contents

- [How This List Is Built](#how-this-list-is-built)
- [Research Domains](#research-domains)
- [Statistics](#statistics)
- [Highlights](#highlights)
- [Research Themes](#research-themes)

## How This List Is Built

The goal is a high-signal reading list: only papers a quant researcher would genuinely want to read.
Candidate papers are collected daily from arXiv (with a monthly backfill of older months) and filtered for
genuine finance/trading relevance. Each is then **pre-scored** 0–100 on five dimensions — novelty, applicability,
rigor, reproducibility, and insight — with domain-specific weights, yielding a composite score and tier (S/A/B/C/D)
computed in code.

Before any paper appears here, its S/A pre-score is **re-evaluated with a frontier model and reviewed and approved
by a human curator** at [OHSE AI Lab](https://ohselab.com). Only the approved S- and A-tier papers are published;
lower tiers stay internal. Entities (methods, concepts, datasets) are extracted and clustered into the research
themes below. Currently publishing **2 S-tier** and **169 A-tier** papers.

## Research Domains

```
Systems Trading & Quant R&D
├── A. System Trading (Rule-Based)
│   ├── A1. Technical Analysis (chart patterns, technical indicators, trading rules)
│   ├── A2. Algorithmic Trading (execution algorithms, order splitting, slippage)
│   ├── A3. High-Frequency Trading (HFT) (ultra-low latency, market making, colocation)
│   └── A4. Market Microstructure (order book, liquidity, price discovery)
├── B. Quantitative Trading (Statistics-Based)
│   ├── B1. Factor Investing (asset pricing, Fama-French, momentum, value, smart beta)
│   ├── B2. Statistical Arbitrage (pairs trading, mean reversion, cointegration)
│   ├── B3. Portfolio Optimization (risk parity, asset allocation, Black-Litterman)
│   └── B4. Financial Econometrics (GARCH, volatility modeling, cointegration, time series)
├── C. AI/ML Trading
│   ├── C1. Deep Learning Price Prediction (LSTM, Transformer, time-series forecasting)
│   ├── C2. Reinforcement Learning Portfolio Management (deep RL, dynamic allocation)
│   ├── C3. NLP / Sentiment Analysis (news, social media, earnings, financial text)
│   ├── C4. LLM-based Trading Agents (financial LLMs, agentic systems, reasoning)
│   └── C5. Generative Models / Synthetic Data (GAN, VAE, diffusion, data augmentation)
```

## Statistics

| Metric                   | Value                                   |
| ------------------------ | --------------------------------------- |
| Relevant papers screened | 1262                                    |
| S-tier (published)       | 2                                       |
| A-tier (published)       | 169                                     |
| Sub-domains              | 13                                      |
| Scoring                  | 5-dimension composite (domain-weighted) |

## Highlights

The highest-scoring papers across all domains:

- [When Alpha Disappears: A One-Switch Benchmark for Decision-Time Leakage in Financial Backtests](https://arxiv.org/abs/2605.23959) - We introduce When Alpha Disappears, a paired evaluation benchmark for diagnosing decision-time leakage in financial machine-learning backtests.
- [Spurious Predictability in Financial Machine Learning](https://arxiv.org/abs/2604.15531) - Adaptive specification search generates statistically significant backtests even under martingale-difference nulls.
- [Evaluating Structured Strategy Backtests: Peer Benchmarks, Regime Timing, and Live Performance](https://arxiv.org/abs/2604.18821) - Institutional allocators often evaluate structured strategies on the basis of marketed backtests -- hypothetical track records constructed by applying a strategy's rules to historical data prior to any live trading.
- [Implementation Risk in Portfolio Backtesting: A Previously Unquantified Source of Error](https://arxiv.org/abs/2603.20319) - Portfolio backtesting is the primary tool for evaluating investment strategies before deployment, yet practitioners implicitly assume that different engines produce identical results for the same strategy.
- [An Explicit Solution to Black-Scholes Implied Volatility](https://arxiv.org/abs/2604.24480) - Black-Scholes implied volatility is a quantile.
- [When Forecast Accuracy Fails: Rank Correlation and Decision Quality in Multi-Market Battery Storage Optimization](https://arxiv.org/abs/2604.12082) - Battery energy storage systems (BESS) participating in multi-market electricity trading require price forecasts to optimize dispatch decisions.
- [Optimal execution on Uniswap v2/v3 under transient price impact](https://arxiv.org/abs/2601.03799) - We study the optimal liquidation of a large position on Uniswap v2 and Uniswap v3 in discrete time.
- [DatedGPT: Preventing Lookahead Bias in Large Language Models with Time-Aware Pretraining](https://arxiv.org/abs/2603.11838) - In financial backtesting, large language models pretrained on internet-scale data risk introducing lookahead bias that undermines their forecasting validity, as they may have already seen the true outcome during.
- [A Deterministic Limit Order Book Simulator with Hawkes-Driven Order Flow](https://arxiv.org/abs/2510.08085) - We present a reproducible research framework for market microstructure combining a deterministic C++ limit order book (LOB) simulator with stochastic order flow generated by multivariate marked Hawkes processes.
- [Orthogonal reparametrization of the Nelson-Siegel-Svensson interest rate curve model: conditioning, diagnostics, and identifiability](https://arxiv.org/abs/2604.19290) - The Nelson-Siegel-Svensson (NSS) interest rate curve model yields a separable nonlinear least-squares problem whose inner linear block is often ill-conditioned because the basis functions become nearly collinear.

## Research Themes

Clusters auto-detected from the paper co-occurrence graph: large language model · multi agent system · benchmarking; reinforcement learning · option pricing · neural network; transformer · deep learning · regime shift; machine learning · portfolio optimization · portfolio construction; transaction cost · market impact · hedging; portfolio optimization · mean variance optimization · deep reinforcement learning; stochastic control · market making · liquidity provision; systemic risk · monte carlo · contagion.

## Contributing

Corrections and paper suggestions are welcome — see [contributing.md](contributing.md).
