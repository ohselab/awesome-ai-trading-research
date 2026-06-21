# Wow Papers (Score ≥ 80)

> **Wow Score** evaluates papers on: Practical Applicability (30%), Novelty (25%), Performance (25%), Reproducibility (15%), Timeliness (5%)
> **Last Updated**: 2026-06-21

---

## All Wow Papers (sorted by score)

| Rank | Paper | Domain | Year | Wow | Venue | arXiv | Code | Key Contribution |
|------|-------|--------|------|-----|-------|-------|------|------------------|
| 1 | FinAgent: Multimodal Foundation Agent | C4 | 2024 | **88** | KDD 2024 | [2402.18485](https://arxiv.org/abs/2402.18485) | ✅ | Multimodal LLM for financial trading decisions |
| 2 | GIFT: LLM-Guided State-Reward Interface | C4 | 2026 | **88** | arXiv | [2606.08450](https://arxiv.org/abs/2606.08450) | ✅ | LLM for RL state-reward design, not direct trading |
| 3 | TradingAgents: Multi-Agent LLM Framework | C4 | 2024 | **85** | Multi-Agent AI | [2412.20138](https://arxiv.org/abs/2412.20138) | ✅ | Multi-agent collaboration for trading decisions |
| 4 | Beyond Agent Architecture: Reproducibility | C4 | 2026 | **85** | arXiv | [2606.08285](https://arxiv.org/abs/2606.08285) | ❌ | Reproducibility audit of 30 LLM trading studies |
| 5 | FPILOT: Plan Before You Trade | C2 | 2026 | **85** | arXiv | [2605.12653](https://arxiv.org/abs/2605.12653) | 🔜 | Inference-time optimization for RL agents |
| 6 | FPQC-SAC: Quantum-Inspired RL | C2 | 2026 | **84** | arXiv | [2606.10448](https://arxiv.org/abs/2606.10448) | ❌ | Quantum circuits stabilize SAC in low-SNR markets |
| 7 | Deep RL for Diversified Portfolio | C2 | 2026 | **82** | arXiv | [2605.17307](https://arxiv.org/abs/2605.17307) | ❌ | SAC + Dirichlet policy, global market testing |
| 8 | BAVAR-BLED: Regime-Aware Portfolio | C2 | 2026 | **82** | arXiv | [2606.09104](https://arxiv.org/abs/2606.09104) | ❌ | Bayesian VAR + Black-Litterman for regime changes |
| 9 | FinCon: Conceptual Verbal Reinforcement | C4 | 2024 | **82** | NeurIPS 2024 | [2407.06567](https://arxiv.org/abs/2407.06567) | ✅ | LLM multi-agent with verbal reinforcement |
| 10 | AlphaAgent: LLM-Driven Alpha Mining | C4 | 2025 | **82** | KDD 2025 | [2502.16789](https://arxiv.org/abs/2502.16789) | ✅ | LLM-based alpha factor discovery |
| 11 | Deep Hedging with RL | C2 | 2025 | **80** | arXiv | [2512.12420](https://arxiv.org/abs/2512.12420) | ✅ | Cost-aware RL for options hedging |
| 12 | SHARP: Self-Evolving Rubric Policy | C4 | 2026 | **80** | arXiv | [2605.06822](https://arxiv.org/abs/2605.06822) | ❌ | Self-evolving human-auditable trading policy |

---

## By Domain

### C2: RL Portfolio Management (5 papers)
- FPILOT (85), FPQC-SAC (84), Diversified Portfolio (82), BAVAR-BLED (82), Deep Hedging (80)

### C4: LLM Trading Agents (7 papers)
- FinAgent (88), GIFT (88), TradingAgents (85), Beyond Architecture (85), FinCon (82), AlphaAgent (82), SHARP (80)

---

## Key Insights from Wow Papers

### 1. LLM ↔ RL Hybrid Architecture Rising
LLMs are being used not as direct decision engines but for specific RL pipeline stages:
- **GIFT**: LLM → state/reward design (learning phase)
- **FPILOT**: LLM → price prediction (inference phase)
- **SHARP**: LLM → rubric policy evolution

### 2. Execution Realism Becomes Mandatory
- **Beyond Agent Architecture**: Audited 30 studies for reproducibility
- Trend: performance claims → reproducibility verification

### 3. Self-Improving Agent Paradigm
- Single agent → Multi-agent systems
- Fixed policy → Self-evolving policy
- **SHARP**, **FinCon**, **TradingAgents** lead this trend

---

*Updated automatically from the internal research pipeline.*
