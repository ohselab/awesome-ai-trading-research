# Research Landscape Map

> **Last Updated**: 2026-06-21
> **Seed Papers**: 17 (A: 4, B: 7, C: 6)
> **Total Citations**: ~300,000+
> **Follow-up Papers**: 40+ (2024-2026)

---

## Summary

| Domain | Papers | Total Citations | Most Influential Paper | Key Keywords |
|--------|--------|----------------|----------------------|--------------|
| **A. System Trading** | 4 | ~8,232 | O'Hara 1995 (3,622) | Market microstructure, execution optimization, adaptive markets |
| **B. Quant Trading** | 7 | ~111,700 | Engle 1982 (37,600) | Factor models, stat arb, cointegration, ARCH |
| **C. AI/ML Trading** | 6 | ~183,055 | Vaswani 2017 (175,000) | Transformer, DRL, sentiment, financial LLM |

---

## Citation Tree

```
                          [Mathematical Foundations]
                              │
            ┌─────────────────┼─────────────────┐
            │                 │                 │
     [B4] Time Series    [B1] Factor        [A4] Market
     Econometrics        Investing          Microstructure
     ├─ Engle 1982       ├─ Fama 1992       └─ O'Hara 1995
     │  (ARCH)            │  (3-factor)
     └─ Engle 1987        └─ Fama 2015
        (Cointegration)      (5-factor)
            │                 │                 │
            └────────┬────────┘                 │
                     │                          │
              [B2] Statistical                  │
              Arbitrage                         │
              ├─ Gatev 2006                     │
              └─ Avellaneda 2010                │
                     │                          │
                     └──────────┬───────────────┘
                                │
                         [A2] Algorithmic
                         Trading
                         └─ Almgren 2001
                                │
                    ┌───────────┼───────────┐
                    │           │           │
             [A1] Tech.    [A3] HFT    [B3] Portfolio
             Analysis                   Optimization
             └─ Lo 2000                   └─ Merton 1972
             └─ Lo 2004
                    │
                    │         [Deep Learning Revolution 2017~]
                    │              │
                    │    ┌─────────┼─────────┐
                    │    │         │         │
                    │  [C1] DL  [C2] DRL  [C3] NLP
                    │  Price    Portfolio  Sentiment
                    │  ├Vaswani ├Jiang    ├Xu 2018
                    │  │ 2017   │ 2017    └Bollen 2011
                    │              │
                    └──────┬───────┘
                           │
                    [C4] LLM Trading
                    ├─ BloombergGPT 2023
                    ├─ FinGPT 2023
                    ├─ FinAgent 2024 (wow: 88)
                    └─ TradingAgents 2024 (wow: 85)
```

---

## Cross-Domain Links

| From | To | Connection |
|------|-----|-----------|
| B4 → B2 | Cointegration theory → Pairs trading statistical foundation |
| B1 → C2 | Factor models → DRL portfolio reward function design |
| C1 → C4 | Transformer → Financial LLM architecture |
| A4 → A2 | Market microstructure → Execution algorithm design |
| C4 ↔ C2 | LLM-RL hybrid: LLM for learning, RL for execution |

---

## Top 5 Most Cited Papers

1. **Vaswani 2017** — ~175,000 (Transformer)
2. **Engle 1982** — ~37,600 (ARCH, Nobel Prize)
3. **Engle 1987** — ~30,000 (Cointegration, Nobel Prize)
4. **Jegadeesh 1993** — ~18,200 (Momentum)
5. **Fama 1992** — ~16,000 (3-factor)

---

## Priority Follow-ups (2024-2026)

### Priority 1 (Active Research)
| Domain | Topic | Reason |
|--------|-------|--------|
| C4 | LLM Trading Agents | Fastest growing, most practical |
| C2 | RL Portfolio (2024-2026) | DRL + LLM convergence |
| B1 | Factor Investing (ML) | ML-based factor discovery |

### Priority 2 (1-2 weeks)
| Domain | Topic | Reason |
|--------|-------|--------|
| C3 | Financial Sentiment (LLM-based) | Paradigm shift from rule-based |
| A2 | Execution Algorithms (ML) | ML-based execution optimization |

---

*This map is based on 17 seed papers and 40+ follow-up papers. Continuously updated.*
