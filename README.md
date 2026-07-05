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
themes below. Currently publishing **1 S-tier** and **302 A-tier** papers.

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
| Relevant papers screened | 2560                                    |
| S-tier (published)       | 1                                       |
| A-tier (published)       | 302                                     |
| Sub-domains              | 13                                      |
| Scoring                  | 5-dimension composite (domain-weighted) |

## Highlights

The highest-scoring papers across all domains:

- [RED-2400: A Public Benchmark of Algorithmically-Rejected Trading Events with Outcome Labels](https://arxiv.org/abs/2605.12151) - RED-2400 is a public benchmark of 6,660 algorithmically-rejected trading events from a live Solana decentralised-exchange filter stack, observed continuously over 22 calendar days (2026-04-10T21:10Z through.
- [Kronos: A Foundation Model for the Language of Financial Markets](https://arxiv.org/abs/2508.02739) - The success of large-scale pre-training paradigm, exemplified by Large Language Models (LLMs), has inspired the development of Time Series Foundation Models (TSFMs).
- [Evaluating Structured Strategy Backtests: Peer Benchmarks, Regime Timing, and Live Performance](https://arxiv.org/abs/2604.18821) - Institutional allocators often evaluate structured strategies on the basis of marketed backtests -- hypothetical track records constructed by applying a strategy's rules to historical data prior to any live trading.
- [Spurious Predictability in Financial Machine Learning](https://arxiv.org/abs/2604.15531) - Adaptive specification search generates statistically significant backtests even under martingale-difference nulls.
- [Fast reliable pricing and calibration of the rough Heston model](https://arxiv.org/abs/2508.15080) - The paper is an extended and modified version of the preprint S.Boyarchenko and S.Levendorskiĭ ``Correct implied volatility shapes and reliable pricing in the rough Heston model".
- [DatedGPT: Preventing Lookahead Bias in Large Language Models with Time-Aware Pretraining](https://arxiv.org/abs/2603.11838) - In financial backtesting, large language models pretrained on internet-scale data risk introducing lookahead bias that undermines their forecasting validity, as they may have already seen the true outcome during.
- [Myopic Optimality: why reinforcement learning portfolio management strategies lose money](https://arxiv.org/abs/2509.12764) - Myopic optimization (MO) outperforms reinforcement learning (RL) in portfolio management: RL yields lower or negative returns, higher variance, larger costs, heavier CVaR, lower profitability, and greater model risk.
- [Implementation Risk in Portfolio Backtesting: A Previously Unquantified Source of Error](https://arxiv.org/abs/2603.20319) - Portfolio backtesting is the primary tool for evaluating investment strategies before deployment, yet practitioners implicitly assume that different engines produce identical results for the same strategy.
- [V4FinBench: Benchmarking Tabular Foundation Models, LLMs, and Standard Methods on Corporate Bankruptcy Prediction](https://arxiv.org/abs/2605.10896) - Corporate bankruptcy prediction is a high-stakes financial task characterized by severe class imbalance and multi-horizon forecasting demands.
- [CTBench: Cryptocurrency Time Series Generation Benchmark](https://arxiv.org/abs/2508.02758) - Synthetic time series are essential tools for data augmentation, stress testing, and algorithmic prototyping in quantitative finance.

## Research Themes

Clusters auto-detected from the paper co-occurrence graph: large language model · multi agent system · retrieval augmented generation; neural network · deep learning · option pricing; reinforcement learning · deep reinforcement learning · multi agent reinforcement learning; limit order book · arbitrage · market making; transformer · regime shift · lstm; portfolio optimization · risk management · mean variance optimization; machine learning · portfolio optimization · portfolio construction; transaction cost · stochastic control · hedging.

## Contributing

Corrections and paper suggestions are welcome — see [contributing.md](contributing.md).
