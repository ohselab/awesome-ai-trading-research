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
themes below. Currently publishing **0 S-tier** and **524 A-tier** papers.

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
| Relevant papers screened | 7484                                    |
| S-tier (published)       | 0                                       |
| A-tier (published)       | 524                                     |
| Sub-domains              | 13                                      |
| Scoring                  | 5-dimension composite (domain-weighted) |

## Highlights

The highest-scoring papers across all domains:

- [FinRL-Meta: Market Environments and Benchmarks for Data-Driven Financial Reinforcement Learning](https://arxiv.org/abs/2211.03107) - Finance is a particularly difficult playground for deep reinforcement learning.
- [Time-Causal VAE: Robust Financial Time Series Generator](https://arxiv.org/abs/2411.02947) - We build a time-causal variational autoencoder (TC-VAE) for robust generation of financial time series data.
- [Distributional Model Equivalence for Risk-Sensitive Reinforcement Learning](https://arxiv.org/abs/2307.01708) - We consider the problem of learning models for risk-sensitive reinforcement learning.
- [CTBench: Cryptocurrency Time Series Generation Benchmark](https://arxiv.org/abs/2508.02758) - Synthetic time series are essential tools for data augmentation, stress testing, and algorithmic prototyping in quantitative finance.
- [Distributionally robust risk evaluation with a causality constraint and structural information](https://arxiv.org/abs/2203.10571) - This work studies the distributionally robust evaluation of expected values over temporal data.
- [TriAgent: Divergence-Aware Multi-Agent Committees for Cost-Efficient Financial Sentiment Analysis](https://arxiv.org/abs/2607.19794) - Production LLM-based financial sentiment analysis faces a structural cost trap: most queries are trivially classifiable, yet expensive cloud reasoners process them all, and the bill scales linearly with user count.
- [JAX-LOB: A GPU-Accelerated limit order book simulator to unlock large scale reinforcement learning for trading](https://arxiv.org/abs/2308.13289) - Financial exchanges across the world use limit order books (LOBs) to process orders and match trades.
- [Sell Me This Stock: Unsafe Recommendation Drift in LLM Agents](https://arxiv.org/abs/2603.12564) - People increasingly use LLM agents for multi-turn financial recommendations, where the agent pulls market data through tools and tracks user preferences across turns.
- [Time Travel is Cheating: Going Live with DeepFund for Real-Time Fund Investment Benchmarking](https://arxiv.org/abs/2505.11065) - Large Language Models (LLMs) have demonstrated notable capabilities across financial tasks, including financial report summarization, earnings call transcript analysis, and asset classification.
- [Asymmetry PRISM: A CPU/GPU Portfolio Optimization Engine for Deadline-Bounded Institutional Rebalancing](https://arxiv.org/abs/2606.23367) - Institutional rebalancing is a batched optimization workload with a hard operating deadline: hundreds of accounts need new weights under budget, turnover, exposure, exclusion, and tax-aware controls before trading.

## Research Themes

Clusters auto-detected from the paper co-occurrence graph: reinforcement learning · portfolio optimization · stochastic control; deep learning · neural network · option pricing; large language model · transformer · sentiment analysis; limit order book · liquidity provision · decentralized finance; machine learning · graph neural network · systemic risk; electricity price forecasting · online learning · probabilistic forecasting; clustering · wasserstein distance · distributionally robust optimization; factor model · statistical arbitrage · factor model.

## Contributing

Corrections and paper suggestions are welcome — see [contributing.md](contributing.md).
