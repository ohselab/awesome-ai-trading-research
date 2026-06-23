# Awesome AI Trading Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green.svg)](LICENSE)

> A curated list of academic papers on **System Trading**, **Quantitative Finance**, and **AI/ML-powered Trading** — automatically collected from arXiv and scored on five dimensions. Maintained by [OHSE AI Lab](https://ohselab.com).

[![Last Updated](https://img.shields.io/badge/updated-2026--06--24-blue)](https://github.com/ohselab/awesome-ai-trading-research)
[![Papers](https://img.shields.io/badge/relevant%20papers-894-orange)](papers.md)
[![S/A tier](https://img.shields.io/badge/S%2FA%20curated-120-brightgreen)](papers.md)

---

## Contents

- [How This List Is Built](#how-this-list-is-built)
- [Research Domains](#research-domains)
- [Statistics](#statistics)
- [Highlights (Top S/A)](#highlights-top-sa)
- [Research Themes](#research-themes)
- [Full Curation](#full-curation)

---

## How This List Is Built

This is **not a hand-maintained list**. A pipeline runs daily:

1. **Collect** — new q-fin / cs papers from arXiv (daily + monthly backfill).
2. **Relevance filter** — an LLM drops papers with no real finance/trading relevance.
3. **5-dimension scoring** — each paper is scored 0–100 on **Novelty, Applicability, Rigor, Reproducibility, Insight**, with domain-specific weights; a composite score and tier (S/A/B/C/D) are computed in code.
4. **Knowledge graph** — entities (methods, concepts, datasets) are extracted, normalized, and clustered into research themes.

This list publishes the **S-tier (2) and A-tier (118)** papers. Lower tiers stay internal.

> ℹ️ **Auto-generated daily** from the pipeline. Issues/PRs are not actively monitored — the list regenerates on each run.

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

| Metric | Value |
|--------|-------|
| Relevant papers (KB) | 894 |
| S-tier | 2 |
| A-tier | 118 |
| Sub-domains | 13 |
| Scoring | 5-dim composite (domain-weighted) |

## Highlights (Top S/A)

- **[When Alpha Disappears: A One-Switch Benchmark for Decision-Time Leakage in Financial Backtests](https://arxiv.org/abs/2605.23959)** (2026) · `S` 81.0 — *machine learning, walk-forward validation* · decision-time leakage, backtest leakage, protocol-induced inflation, evaluation benchmark
- **[Spurious Predictability in Financial Machine Learning](https://arxiv.org/abs/2604.15531)** (2026) · `S` 80.1 — *machine learning, walk-forward analysis, specification search, falsification audit* · spurious predictability, martingale difference, backtest overfitting, selection bias
- **[Evaluating Structured Strategy Backtests: Peer Benchmarks, Regime Timing, and Live Performance](https://arxiv.org/abs/2604.18821)** (2026) · `A` 79.1 — *backtest, regime timing, peer benchmark* · structured strategy, pro forma performance, live performance, institutional allocator
- **[Implementation Risk in Portfolio Backtesting: A Previously Unquantified Source of Error](https://arxiv.org/abs/2603.20319)** (2026) · `A` 78.7 — *backtesting, metrology* · implementation risk, portfolio backtesting, engine sensitivity, implementation uncertainty interval
- **[An Explicit Solution to Black-Scholes Implied Volatility](https://arxiv.org/abs/2604.24480)** (2026) · `A` 76.8 — *black-scholes model, inverse gaussian distribution, quantile function* · implied volatility, option pricing, variance scale, explicit formula
- **[When Forecast Accuracy Fails: Rank Correlation and Decision Quality in Multi-Market Battery Storage Optimization](https://arxiv.org/abs/2604.12082)** (2026) · `A` 75.1 — *hierarchical optimization, forecasting, rank correlation* · battery energy storage, forecast accuracy, decision quality, multi-market trading
- **[DatedGPT: Preventing Lookahead Bias in Large Language Models with Time-Aware Pretraining](https://arxiv.org/abs/2603.11838)** (2026) · `A` 75.0 — *large language model, pretraining* · lookahead bias, backtesting, time-aware pretraining, forecasting validity
- **A Deterministic Limit Order Book Simulator with Hawkes-Driven Order Flow** · `A` 74.8 — *limit order book simulator, hawkes process, multivariate hawkes process, marked hawkes process* · market microstructure, order flow, stability, ergodicity
- **[Orthogonal reparametrization of the Nelson-Siegel-Svensson interest rate curve model: conditioning, diagnostics, and identifiability](https://arxiv.org/abs/2604.19290)** (2026) · `A` 74.8 — *nelson-siegel-svensson model, orthogonal reparametrization, thin qr decomposition, nonlinear least squares* · yield curve, conditioning, identifiability, collinearity
- **[PumpSense: Real-Time Detection and Target Extraction of Crypto Pump-and-Dumps on Telegram](https://arxiv.org/abs/2605.09431)** (2026) · `A` 74.7 — *natural language processing, text classification, named entity recognition* · pump and dump, telegram, real-time detection, target extraction

→ Full lists by domain in **[papers.md](papers.md)**.

## Research Themes

Auto-detected from the paper co-occurrence graph:

- **large language model · multi agent system · portfolio optimization**
- **reinforcement learning · risk management · dynamic programming**
- **neural network · option pricing · implied volatility**
- **transformer · deep learning · time series forecasting**
- **portfolio optimization · regime shift · mean variance optimization**
- **stochastic control · market making · inventory risk**
- **machine learning · asset pricing · autoencoder**
- **transaction cost · reproducibility · agentic system**

→ See **[research-map.md](research-map.md)** for the full landscape (per-domain tables, methods, concepts, asset classes, all themes).

## Full Curation

- 📄 **[papers.md](papers.md)** — all S/A papers by sub-domain, with method/concept tags
- 🗺️ **[research-map.md](research-map.md)** — domain landscape, trends, themes

## License

The curated list and structure are licensed under [CC BY 4.0](LICENSE). Each paper's copyright belongs to its original authors. Links point to arXiv.

---
*Maintained by [OHSE AI Lab](https://ohselab.com).*
