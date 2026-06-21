# Awesome AI Trading Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> A curated list of academic papers on **System Trading**, **Quantitative Finance**, and **AI/ML-powered Trading** — maintained by [OHSE AI Lab](https://ohselab.com)

[![GitHub Stars](https://img.shields.io/github/stars/ohselab/awesome-ai-trading-research?style=social)](https://github.com/ohselab/awesome-ai-trading-research)
[![Last Updated](https://img.shields.io/badge/last--updated-2026--06--21-blue)](https://github.com/ohselab/awesome-ai-trading-research)

---

## Contents

- [Research Domains](#research-domains)
- [Research Map](#research-map)
- [Wow Papers (Score ≥ 80)](#wow-papers)
- [Domain A: System Trading (Rule-Based)](#a-system-trading-rule-based)
- [Domain B: Quantitative Trading (Statistics-Based)](#b-quantitative-trading-statistics-based)
- [Domain C: AI/ML Trading](#c-aiml-trading)
- [Key Trends (2024-2026)](#key-trends-2024-2026)
- [Follow-up Studies](#follow-up-studies)

---

## Research Domains

```
Systems Trading & Quant R&D
├── A. System Trading (Rule-Based)
│   ├── A1. Technical Analysis (chart patterns, indicators)
│   ├── A2. Algorithmic Trading (execution algorithms)
│   ├── A3. High-Frequency Trading (HFT)
│   └── A4. Market Microstructure
│
├── B. Quantitative Trading (Statistics-Based)
│   ├── B1. Factor Investing (Fama-French, momentum, value)
│   ├── B2. Statistical Arbitrage (pairs trading, mean reversion)
│   ├── B3. Portfolio Optimization (risk parity, Black-Litterman)
│   └── B4. Financial Econometrics (GARCH, cointegration)
│
└── C. AI/ML Trading
    ├── C1. Deep Learning Price Prediction (LSTM, Transformer)
    ├── C2. Reinforcement Learning Portfolio Management
    ├── C3. NLP/Sentiment Analysis Trading
    ├── C4. LLM-based Trading Agents
    └── C5. Generative Model-based Synthetic Data
```

> **13 sub-domains**, **17 seed papers** (~300,000+ total citations), **40+ follow-up papers** (2024-2026)

→ See the full [Research Map](research-map.md) for the citation tree and cross-domain links.

---

## Research Map

| Domain | Papers | Total Citations | Most Influential | Key Keywords |
|--------|--------|----------------|------------------|--------------|
| **A. System Trading** | 4 | ~8,232 | O'Hara 1995 (3,622) | Market microstructure, execution optimization, adaptive markets |
| **B. Quant Trading** | 7 | ~111,700 | Engle 1982 (37,600) | Factor models, stat arb, cointegration, ARCH |
| **C. AI/ML Trading** | 6 | ~183,055 | Vaswani 2017 (175,000) | Transformer, DRL, sentiment, financial LLM |

→ Full map: [research-map.md](research-map.md)

---

## Wow Papers

Papers rated **Wow Score ≥ 80** — high practical value, novelty, and reproducibility.

| Paper | Domain | Year | Wow | arXiv | Code |
|-------|--------|------|-----|-------|------|
| FinAgent: Multimodal Foundation Agent | C4 | 2024 | **88** | [2402.18485](https://arxiv.org/abs/2402.18485) | [✅](https://github.com/AI4Finance-Foundation/FinGPT) |
| GIFT: LLM-Guided State-Reward Interface | C4 | 2026 | **88** | [2606.08450](https://arxiv.org/abs/2606.08450) | [✅](https://github.com/KAG778/GIFT) |
| TradingAgents: Multi-Agent LLM Framework | C4 | 2024 | **85** | [2412.20138](https://arxiv.org/abs/2412.20138) | ✅ |
| Beyond Agent Architecture: Reproducibility Audit | C4 | 2026 | **85** | [2606.08285](https://arxiv.org/abs/2606.08285) | ❌ |
| FPILOT: Plan Before You Trade | C2 | 2026 | **85** | [2605.12653](https://arxiv.org/abs/2605.12653) | 🔜 |
| FPQC-SAC: Quantum-Inspired RL | C2 | 2026 | **84** | [2606.10448](https://arxiv.org/abs/2606.10448) | ❌ |
| Deep RL for Diversified Portfolio | C2 | 2026 | **82** | [2605.17307](https://arxiv.org/abs/2605.17307) | ❌ |
| BAVAR-BLED: Regime-Aware Portfolio | C2 | 2026 | **82** | [2606.09104](https://arxiv.org/abs/2606.09104) | ❌ |
| FinCon: Conceptual Verbal Reinforcement | C4 | 2024 | **82** | [2407.06567](https://arxiv.org/abs/2407.06567) | ✅ |
| AlphaAgent: LLM-Driven Alpha Mining | C4 | 2025 | **82** | [2502.16789](https://arxiv.org/abs/2502.16789) | ✅ |
| Deep Hedging with RL | C2 | 2025 | **80** | [2512.12420](https://arxiv.org/abs/2512.12420) | ✅ |
| SHARP: Self-Evolving Rubric Policy | C4 | 2026 | **80** | [2605.06822](https://arxiv.org/abs/2605.06822) | ❌ |

> **Wow Score criteria**: Practical applicability (30%), Novelty (25%), Performance (25%), Reproducibility (15%), Timeliness (5%)

→ Full list: [wow-papers/](wow-papers/)

---

## A. System Trading (Rule-Based)

### A1. Technical Analysis

| Paper | Authors | Year | Venue | Citations | Link |
|-------|---------|------|-------|-----------|------|
| The Adaptive Markets Hypothesis | Andrew W. Lo | 2004 | J. Portfolio Mgmt. | ~1,416 | [DOI](https://doi.org/10.3905/jpm.2004.442611) |
| Foundations of Technical Analysis | Lo, Mamaysky, Wang | 2000 | J. Finance | ~792 | [DOI](https://doi.org/10.1111/0022-1082.00265) |

### A2. Algorithmic Trading

| Paper | Authors | Year | Venue | Citations | Link |
|-------|---------|------|-------|-----------|------|
| Optimal Execution of Portfolio Transactions | Almgren & Chriss | 2001 | J. Risk | ~2,402 | [DOI](https://doi.org/10.21314/JOR.2001.041) |

### A4. Market Microstructure

| Paper | Authors | Year | Venue | Citations | Link |
|-------|---------|------|-------|-----------|------|
| Market Microstructure Theory (Book) | Maureen O'Hara | 1995 | Blackwell/Wiley | ~3,622 | [ISBN](https://isbnsearch.org/isbn/0631207619) |

→ Detailed analysis: [domains/A_system_trading.md](domains/A_system_trading.md)

---

## B. Quantitative Trading (Statistics-Based)

### B1. Factor Investing

| Paper | Authors | Year | Venue | Citations | Link |
|-------|---------|------|-------|-----------|------|
| The Cross-Section of Expected Stock Returns | Fama & French | 1992 | J. Finance | ~16,000 | [DOI](https://doi.org/10.1111/j.1540-6261.1992.tb04398.x) |
| A Five-Factor Asset Pricing Model | Fama & French | 2015 | J. Financial Economics | ~12,800 | [DOI](https://doi.org/10.1016/j.jfineco.2014.10.010) |
| Returns to Buying Winners and Selling Losers | Jegadeesh & Titman | 1993 | J. Finance | ~18,200 | [DOI](https://doi.org/10.1111/j.1540-6261.1993.tb04702.x) |

### B2. Statistical Arbitrage

| Paper | Authors | Year | Venue | Citations | Link |
|-------|---------|------|-------|-----------|------|
| Pairs Trading: Performance of a Relative-Value Arbitrage Rule | Gatev, Goetzmann, Rouwenhorst | 2006 | Rev. Financial Studies | ~3,500 | [DOI](https://doi.org/10.1093/rfs/hhj017) |
| Statistical Arbitrage in the US Equities Market | Avellaneda & Lee | 2010 | Quantitative Finance | ~600 | [DOI](https://doi.org/10.1080/14697680903124632) |

### B4. Financial Econometrics

| Paper | Authors | Year | Venue | Citations | Link |
|-------|---------|------|-------|-----------|------|
| Autoregressive Conditional Heteroscedasticity (ARCH) | Robert F. Engle | 1982 | Econometrica | ~37,600 | [DOI](https://doi.org/10.2307/1912773) |
| Co-integration and Error Correction | Engle & Granger | 1987 | Econometrica | ~30,000 | [DOI](https://doi.org/10.2307/1913236) |

→ Detailed analysis: [domains/B_quant_trading.md](domains/B_quant_trading.md)

---

## C. AI/ML Trading

### C1. Deep Learning / Transformers

| Paper | Authors | Year | Venue | Citations | Link |
|-------|---------|------|-------|-----------|------|
| Attention Is All You Need (Transformer) | Vaswani et al. | 2017 | NeurIPS 2017 | ~175,000 | [arXiv](https://arxiv.org/abs/1706.03762) |

### C2. Reinforcement Learning Portfolio Management

| Paper | Authors | Year | Venue | Citations | Link |
|-------|---------|------|-------|-----------|------|
| Deep RL Framework for Portfolio Management | Jiang et al. | 2017 | arXiv | ~456 | [arXiv](https://arxiv.org/abs/1706.10059) |

### C3. NLP/Sentiment Analysis

| Paper | Authors | Year | Venue | Citations | Link |
|-------|---------|------|-------|-----------|------|
| Twitter Mood Predicts the Stock Market | Bollen et al. | 2011 | J. Computational Science | ~5,401 | [DOI](https://doi.org/10.1016/j.jocs.2010.12.007) |
| Stock Movement Prediction from Tweets | Xu & Cohen | 2018 | ACL 2018 | ~446 | [ACL](https://aclanthology.org/P18-1183) |

### C4. LLM-based Trading Agents

| Paper | Authors | Year | Venue | Citations | Link |
|-------|---------|------|-------|-----------|------|
| FinGPT: Open-Source Financial LLMs | Yang et al. | 2023 | IJCAI 2023 | ~408 | [arXiv](https://arxiv.org/abs/2306.06031) |
| BloombergGPT: 50B Financial LLM | Wu et al. | 2023 | arXiv | ~1,346 | [arXiv](https://arxiv.org/abs/2303.17564) |

→ Detailed analysis: [domains/C_ai_trading.md](domains/C_ai_trading.md)

---

## Key Trends (2024-2026)

| Trend | Description | Representative Papers | Impact |
|-------|-------------|----------------------|--------|
| **LLM ↔ RL Hybrid** | LLM for state/reward design + RL for execution | GIFT, FPILOT, SHARP | ⭐⭐⭐⭐⭐ |
| **Execution Realism** | Reproducibility audits, real-world cost modeling | Beyond Agent Architecture | ⭐⭐⭐⭐⭐ |
| **Regime-Aware Portfolio** | Multi-regime models, fat-tail handling | BAVAR-BLED, FR-LUX | ⭐⭐⭐⭐ |
| **Self-Improving Agents** | Multi-agent, self-evolving policies | SHARP, FinCon, TradingAgents | ⭐⭐⭐⭐ |
| **Quantum-Inspired RL** | Quantum circuits for financial RL | FPQC-SAC | ⭐⭐⭐ |

---

## Follow-up Studies

| Domain | Topic | Papers | Period |
|--------|-------|--------|--------|
| C2 | RL Portfolio Management | 20 papers | 2024-2026 |
| C4 | LLM Trading Agents | 20 papers | 2024-2026 |

→ [C2 follow-up: RL Portfolio Management](followups/C2_rl_portfolio_2024_2026.md)
→ [C4 follow-up: LLM Trading Agents](followups/C4_llm_trading_2024_2026.md)

---

## Data Sources

| Source | Usage | Rate Limit |
|--------|-------|------------|
| Semantic Scholar | Citation data, recommendations | 100 req/sec (API key) |
| arXiv | Preprints | 1 req/3sec |
| Google Scholar | Peer-reviewed papers | Playwright scraping |

---

## Contributing

Contributions welcome! Please submit a PR with:
- Paper title, authors, year, venue
- arXiv ID or DOI
- Brief description of key contribution
- Wow score evaluation (optional)

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## License

[MIT License](LICENSE) — Paper summaries reference original authors' licenses.

---

**Maintained by**: [OHSE AI Lab](https://ohselab.com) (주식회사 오세에이아이연구소)
**Contact**: research@ohselab.com
**Last updated**: 2026-06-21
