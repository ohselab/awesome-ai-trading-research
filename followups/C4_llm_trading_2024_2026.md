# C4 영역 후속 조사: LLM 기반 트레이딩 에이전트 (2024-2026)

> **수집일:** 2026-06-20
---

## 📋 논문 요약 테이블

| # | 논문 | 저자 | 연도 | Venue | arXiv/DOI | 코드 | wow_score |
|---|------|------|------|-------|-----------|------|-----------|
| 1 | FinAgent: A Multimodal Foundation Agent for Financial Trading | Zhang et al. | 2024 | KDD 2024 | [2402.18485](https://arxiv.org/abs/2402.18485) | ✅ | **88** |
| 2 | TradingAgents: Multi-Agents LLM Financial Trading Framework | Xiao et al. | 2024 | Oral @ Multi-Agent AI | [2412.20138](https://arxiv.org/abs/2412.20138) | ✅ | **85** |
| 3 | FinCon: Synthesized LLM Multi-Agent System with Conceptual Verbal Reinforcement | Yu et al. | 2024 | NeurIPS 2024 | [2407.06567](https://arxiv.org/abs/2407.06567) | ✅ | **82** |
| 4 | AlphaAgent: LLM-Driven Alpha Mining with Regularized Exploration | Tang et al. | 2025 | KDD 2025 | [2502.16789](https://arxiv.org/abs/2502.16789) | ✅ | **82** |
| 5 | SHARP: Self-Evolving Human-Auditable Rubric Policy | Chen et al. | 2026 | arXiv | [2605.06822](https://arxiv.org/abs/2605.06822) | ❌ | **80** |
| 6 | ATLAS: Adaptive Trading with LLM AgentS | Papadakis et al. | 2025 | arXiv | [2510.15949](https://arxiv.org/abs/2510.15949) | ❌ | **78** |
| 7 | TradExpert: Revolutionizing Trading with MoE LLMs | Ding et al. | 2024 | arXiv | [2411.00782](https://arxiv.org/abs/2411.00782) | ❌ | **77** |
| 8 | FinMem: Performance-Enhanced LLM Trading Agent with Layered Memory | Yu et al. | 2024 | IEEE TBD | [2311.13743](https://arxiv.org/abs/2311.13743) | ✅ | **76** |
| 9 | QuantAgent: Self-Improving LLM for Trading Signal Mining | Wang et al. | 2024 | arXiv | [2402.03755](https://arxiv.org/abs/2402.03755) | ❌ | **75** |
| 10 | WebCryptoAgent: Agentic Crypto Trading with Web Informatics | Kurban et al. | 2026 | arXiv | [2601.04687](https://arxiv.org/abs/2601.04687) | 🔜 | **74** |
| 11 | FinPos: Position-Aware Trading Agent System | Liu & Dang | 2025 | arXiv | [2510.27251](https://arxiv.org/abs/2510.27251) | ❌ | **73** |
| 12 | DeepFund: Live Real-Time Fund Investment Benchmarking | Li et al. | 2025 | NeurIPS 2025 D&B | [2505.11065](https://arxiv.org/abs/2505.11065) | ✅ | **72** |
| 13 | StockAgent: LLM-based Stock Trading in Simulated Environments | Zhang et al. | 2024 | arXiv | [2407.18957](https://arxiv.org/abs/2407.18957) | ✅ | **70** |
| 14 | When Agents Trade: Live Multi-Market Trading Benchmark | Qian et al. | 2025 | arXiv | [2510.11695](https://arxiv.org/abs/2510.11695) | ❌ | **70** |
| 15 | StockBench: Can LLM Agents Trade Stocks Profitably? | Chen et al. | 2025 | arXiv | [2510.02209](https://arxiv.org/abs/2510.02209) | ✅ | **68** |
| 16 | Adversarial News: Manipulating Headlines in LLM-Driven Trading | Rizvani et al. | 2026 | IEEE SaTML | [2601.13082](https://arxiv.org/abs/2601.13082) | ❌ | **67** |
| 17 | AI Agents in Financial Markets: Architecture & Systemic Implications | Gong | 2026 | FinTech 2026 | [2603.13942](https://arxiv.org/abs/2603.13942) | ❌ | **65** |
| 18 | The Alpha Illusion: Reported Alpha Should Not Be Treated as Evidence | Ye et al. | 2026 | arXiv | [2605.16895](https://arxiv.org/abs/2605.16895) | ✅ | **65** |
| 19 | Agentic Trading: When LLM Agents Meet Financial Markets | Xia et al. | 2026 | arXiv | [2605.19337](https://arxiv.org/abs/2605.19337) | ❌ | **63** |
| 20 | Beyond Agent Architecture: Execution Assumptions & Reproducibility | Yao & Zheng | 2026 | arXiv | [2606.08285](https://arxiv.org/abs/2606.08285) | ❌ | **60** |

> **wow_score 기준:** the research community (open-source LLMs 보유, 금융 AI 제품) 적용 가능성 + 기술적 참신성 + 재현성 종합 평가

---

## 🏆 상위 논문 상세 분석

### 1. FinAgent: A Multimodal Foundation Agent for Financial Trading (wow: 88)

| 항목 | 내용 |
|------|------|
| **저자** | Wentao Zhang, Yixin Yao, Xuyang Zhang, Jiahe Chen, Qiang Liu, Zhiqiang Zhang, Yao Hu, Zhiyuan Liu, Maosong Sun |
| **연도** | 2024 |
| **Venue** | **KDD 2024** (ACM SIGKDD) |
| **arXiv** | [2402.18485](https://arxiv.org/abs/2402.18485) |
| **DOI** | 10.1145/3637528.3671801 |

#### 핵심 기여
- **최초의 멀티모달 금융 트레이딩 파운데이션 에이전트:** 텍스트(뉴스, 공시), 시계열(가격), 테이블(재무제표) 등 다양한 모달리티를 통합 처리
- **Tool Augmentation:** 외부 도구(API, 계산기)를 활용한 보강추론 아키텍처
- **Market Intelligence Module:** 멀티모달 데이터를 통합적으로 이해하는 지능 모듈
- 12개 SOTA 방법론을 **크게 상회하는 성능** (398 거래일 테스트)

---

### 2. TradingAgents: Multi-Agents LLM Financial Trading Framework (wow: 85)

| 항목 | 내용 |
|------|------|
| **저자** | Yijia Xiao, Edward Sun, Di Luo, Wei Wang |
| **연도** | 2024 |
| **Venue** | Tauric Research Technical Report / Oral @ Multi-Agent AI in the Real World |
| **arXiv** | [2412.20138](https://arxiv.org/abs/2412.20138) |
| **코드** | [github.com/tauricresearch/tradingagents](https://github.com/tauricresearch/tradingagents) ✅ |

#### 핵심 기여
- **트레이딩 펌 조직 모방 멀티에이전트 프레임워크:** 실전 트레이딩 회사의 역할 분담을 모방
- **전문 에이전트 역할:**
  - 애널리스트 (Fundamental, Sentiment, Technical)
  - 리서치 (Bull/Bear Researcher)
  - 리스크 관리팀
  - 트레이더 (다양한 리스크 프로파일)
- **토론 기반 의사결정:** 에이전트 간 debate를 통한 합의 도출
- 누적 수익률, 샤프 비율, 최대 낙폭에서 베이스라인 대비 **우월한 성능**

---

### 3. FinCon: Synthesized LLM Multi-Agent System with Conceptual Verbal Reinforcement (wow: 82)

| 항목 | 내용 |
|------|------|
| **저자** | Yangyang Yu, Zhihan Yao, Haohang Li, Zhi Chen, Yuechen Jiang, Yang Li, Denghui Zhang, Rong Liu, Jordan W. Suchow, Khaldoun Khashanah |
| **연도** | 2024 |
| **Venue** | **NeurIPS 2024** |
| **arXiv** | [2407.06567](https://arxiv.org/abs/2407.06567) |

#### 핵심 기여
- **Conceptual Verbal Reinforcement:** 자연어 기반 투자 신념(belief)을 강화학습 메커니즘으로 업데이트
- **Manager-SubAgent 구조:** 매니저 에이전트가 최종 트레이딩 결정, 서브에이전트가 정보 수집
- **PnL 기반 신념 업데이트:** 손익 결과를 바탕으로 투자 전략의 개념적 표현을 자동 개선
- 다중 금융 태스크(주식, 암호화폐)에서 검증

---

### 4. AlphaAgent: LLM-Driven Alpha Mining with Regularized Exploration (wow: 82)

| 항목 | 내용 |
|------|------|
| **저자** | Ziyi Tang, Zechuan Chen, Jiarui Yang, Jiayao Mai, Yongsen Zheng, Keze Wang, Jinrui Chen, Liang Lin |
| **연도** | 2025 |
| **Venue** | **KDD 2025** |
| **arXiv** | [2502.16789](https://arxiv.org/abs/2502.16789) |
| **코드** | [github.com/RndmVariableQ/AlphaAgent](https://github.com/RndmVariableQ/AlphaAgent) ✅ |

#### 핵심 기여
- **Alpha Decay 저항:** 알파 팩터의 시간 감쇠(decay) 문제를 LLM 기반으로 해결
- **3가지 핵심 메커니즘:**
  1. AST 기반 유사도 측정으로 **독창성 강제** (Originality Enforcement)
  2. LLM 기반 가설-팩터 **의미 정렬** (Hypothesis-Factor Alignment)
  3. AST 구조 제약으로 **복잡도 제어** (Complexity Control)
- CSI 500 (중국) 및 S&P 500 (미국)에서 **4년간 일관된 알파 생성**
- 전통적 GP 및 기존 LLM 방법론 대비 **우월한 성능**

---

### 5. SHARP: Self-Evolving Human-Auditable Rubric Policy (wow: 80)

| 항목 | 내용 |
|------|------|
| **저자** | Xiwen Chen, Wenhui Zhu, Songzhu Zheng, Kashif Rasul, Yueyue Deng, Huayu Li |
| **연도** | 2026 |
| **arXiv** | [2605.06822](https://arxiv.org/abs/2605.06822) |

#### 핵심 기여
- **신경-심볼릭 프레임워크:** 비구조적 프롬프트 최적화 → 구조적 심볼릭 정책 최적화로 전환
- **Human-Readable Rubric:** `IF 조건 THEN 행동` 형태의 사람이 읽을 수 있는 규칙 기반 정책
- **Attribution Agent:** 불량 거래의 원인을 교차 샘플추론으로 특정 규칙 실패에 귀속
- **Walk-forward Validation:** 정책 수정 후 엄격한 워크포워드 검증으로 규제
- GPT-4o-mini 등 소형 모델에서 **10-20%p 성능 향상**
- 3개 주식 섹터, 4개 LLM backbone에서 검증

---

### 6. ATLAS: Adaptive Trading with LLM AgentS (wow: 78)

| 항목 | 내용 |
|------|------|
| **저자** | Charidimos Papadakis, Angeliki Dimitriou, Giorgos Filandrianos, Maria Lymperaiou, Konstantinos Thomas, Giorgos Stamou |
| **연도** | 2025 |
| **arXiv** | [2510.15949](https://arxiv.org/abs/2510.15949) |

#### 핵심 기여
- **Adaptive-OPRO:** 실시간 확률적 피드백을 프롬프트에 동적으로 반영하는 프롬프트 최적화 기법
- **Order-Aware Action Space:** 추상적 신호가 아닌 실행 가능한 주문으로 직접 출력
- 멀티에이전트 통합 (시장, 뉴스, 펀더멘털)
- **Reflection 기반 피드백은 체계적 성능 향상을 제공하지 못함** 발견

---

### 7. TradExpert: Revolutionizing Trading with Mixture of Expert LLMs (wow: 77)

| 항목 | 내용 |
|------|------|
| **저자** | Qianggang Ding, Haochen Shi, Jiadong Guo, Bang Liu |
| **연도** | 2024 |
| **arXiv** | [2411.00782](https://arxiv.org/abs/2411.00782) |

#### 핵심 기여
- **Mixture of Experts (MoE) 아키텍처:** 4개 전문 LLM (뉴스, 시장 데이터, 알파 팩터, 펀더멘털) + 1개 General Expert
- **이중 모드:** 예측 모드 (주가 방향 예측) ↔ 랭킹 모드 (퀀트 트레이딩)
- 대규모 금융 데이터셋 공개

---

### 8. FinMem: Performance-Enhanced LLM Trading Agent with Layered Memory (wow: 76)

| 항목 | 내용 |
|------|------|
| **저자** | Yangyang Yu, Haohang Li, Zhi Chen et al. |
| **연도** | 2024 (IEEE Transactions on Big Data) |
| **arXiv** | [2311.13743](https://arxiv.org/abs/2311.13743) |
| **코드** | [github.com/pipiku915/finmem-llm-stocktrading](https://github.com/pipiku915/finmem-llm-stocktrading) ✅ |

#### 핵심 기여
- **레이어드 메모리:** Working Memory + Long-term Memory의 계층적 구조
- **인식 범위 조절 (Cognitive Span):** 인간 트레이더의 인지 한계를 넘어선 정보 보존
- **캐릭터 설계 (Character Design):** 에이전트 성격 커스터마이징
- 실시간 튜닝 가능, 높은 해석 가능성

---

### 9-20. 나머지 논문 요약

#### 9. QuantAgent (arXiv:2402.03755, 2024)
- **핵심:** 2-Layer 자기개선 루프 (내부: 지식 기반 응답 개선, 외부: 실전 테스트 → 지식 자동 강화)
- **적용성:** 트레이딩 신호 자동 발굴 시스템에 참조 가능

#### 10. WebCryptoAgent (arXiv:2601.04687, 2026)
- **핵심:** 모달리티별 전문 에이전트 분해 + 통합 증거 문서 + 전략/리스크 분리 아키텍처
- **적용성:** 암호화폐 트레이딩 특화, 실시간 리스크 관리 모듈 참조

#### 11. FinPos (arXiv:2510.27251, 2025)
- **핵심:** 포지션 인식 트레이딩 에이전트. 듀얼 에이전트 (방향성추론 + 포지션 조정)
- **적용성:** 실전 포지션 관리 시스템 설계에 참조

#### 12. DeepFund (arXiv:2505.11065, 2025, NeurIPS 2025 D&B)
- **핵심:** 실시간 펀드 투자 벤치마크. "Time Travel" 문제 해결 (학습 데이터 누출 방지)
- **주요 발견:** DeepSeek-V3, Claude-3.7-Sonnet도 실시간 거래에서 손실 발생
- **적용성:** 한국 시장 특화 실시간 벤치마크 구축 참조

#### 13. StockAgent (arXiv:2407.18957, 2024)
- **핵심:** 외부 요인(매크로, 정책, 기업 실적)이 LLM 트레이딩에 미치는 영향 분석
- **적용성:** 한국 시장 외부 요인 분석 프레임워크 참조

#### 14. When Agents Trade / AMA (arXiv:2510.11695, 2025)
- **핵심:** 실시간 멀티마켓 벤치마크 (암호화폐 + 주식). **에이전트 아키텍처 > LLM backbone** 발견
- **적용성:** 에이전트 설계의 중요성 확인

#### 15. StockBench (arXiv:2510.02209, 2025)
- **핵심:** LLM 트레이딩 벤치마크. **대부분의 SOTA LLM이 Buy-and-Hold를 상회하지 못함** 발견
- **적용성:** 한국 시장 특화 벤치마크 설계 참조

#### 16. Adversarial News (arXiv:2601.13082, 2026, IEEE SaTML)
- **핵심:** 적대적 뉴스 헤드라인으로 LLM 트레이딩 시스템 공격 가능. 연간 수익률 **최대 17.7%p 감소**
- **적용성:** 금융 AI 제품의 보안 아키텍처 설계에 필수 참조

#### 17. AI Agents in Financial Markets (arXiv:2603.13942, 2026, FinTech Journal)
- **핵심:** 4-Layer 에이전트 아키텍처 (데이터 인식 →추론 → 전략 생성 → 실행). "Bounded Autonomy" 제안
- **적용성:** 금융 AI 제품의 전체 아키텍처 설계 가이드

#### 18. The Alpha Illusion (arXiv:2605.16895, 2026)
- **핵심:** LLM 트레이딩 에이전트의 보고된 알파는 배포 증거로 사용 불가. 6가지 구조적 타당성 검사 필요
- **적용성:** 자체 평가 프로토콜 설계에 필수 참조

#### 19. Agentic Trading Survey (arXiv:2605.19337, 2026)
- **핵심:** 77개 연구 메타분석. 재현성 위기: 19개 주요 연구 중 **R3(완전 재현 가능) 0개**
- **적용성:** 연구 재현성 표준 수립에 참조

#### 20. Beyond Agent Architecture (arXiv:2606.08285, 2026)
- **핵심:** 실행 가정(Execution Assumptions)의 투명성이 아키텍처 못지않게 중요. 30개 연구 재현성 감사
- **적용성:** 평가 프로토콜 표준화에 참조

---

## 🔍 교차 분석: C4 영역 기술 트렌드

### 연구 계보 (Research Lineage)

```
FinGPT (2023) + BloombergGPT (2023) ─────────────────────────┐
  "금융 특화 LLM 기반"                                         │
                                                              ▼
FinMem (2023-24) ───────────────────────────────────────────┐│
  "레이어드 메모리 에이전트"                                    ││
  ▼                                                          ││
FinCon (2024) ──────────────────────────────────────────────┐││
  "개념적 언어 강화 멀티에이전트"                                │││
  ▼                                                          │││
FinAgent (2024) ───────────────────────────────────────────┐│││
  "멀티모달 파운데이션 에이전트"                                ││││
  ▼                                                          ▼▼▼▼
TradingAgents (2024) ────────────────────────────────────────────
  "트레이딩 펌 모방 멀티에이전트"
  ▼
AlphaAgent (2025) ──────────────────────────────────────────────
  "알파 자동 생성 + 디케이 저항"
  ▼
SHARP (2026) ───────────────────────────────────────────────────
  "신경-심볼릭 자기개선 정책"
  ▼
Agentic Trading Survey (2026) + Beyond Architecture (2026)
  "재현성 위기 진단"
```

### 기술적 발전 흐름

| 시기 | 트렌드 | 대표 논문 |
|------|--------|-----------|
| 2023-24 | 레이어드 메모리 에이전트 | FinMem |
| 2024 | 멀티모달 파운데이션 에이전트 | FinAgent |
| 2024 | 멀티에이전트 토론/강화 프레임워크 | TradingAgents, FinCon |
| 2024 | MoE 기반 전문 에이전트 앙상블 | TradExpert |
| 2025 | 알파 자동 생성 및 디케이 저항 | AlphaAgent |
| 2025 | 실시간 벤치마크 및 평가 프로토콜 | DeepFund, StockBench, AMA |
| 2025-26 | 적응적 프롬프트 최적화 | ATLAS, SHARP |
| 2026 | 재현성 위기 진단 및 보안 분석 | Alpha Illusion, Adversarial News |
| 2026 | 구조적 평가 표준화 제안 | Agentic Trading, Beyond Architecture |

### 핵심 발견 (Key Findings)

#### 1. 멀티에이전트 > 단일 에이전트
- TradingAgents, FinCon 등이 일관되게 단일 에이전트 대비 우월한 성능
- **에이전트 아키텍처의 영향 > LLM backbone의 영향** (AMA 벤치마크 확인)

#### 2. 재현성 위기
- 2026년 3개 논문(Agentic Trading, Beyond Architecture, Alpha Illusion)이 독립적으로 동일 문제 지적
- **77개 연구 중 R3(완전 재현 가능) 0개**
- 거래 비용, 타이밍, 데이터 분할의 불투명성이 핵심 문제

#### 3. "Time Travel" 문제
- LLM 학습 데이터에 미래 정보가 포함되어 백테스팅 결과가 과대평가
- DeepFund: 실시간 테스트에서 **DeepSeek-V3, Claude-3.7도 손실**
- StockBench: **대부분 SOTA LLM이 Buy-and-Hold를 상회하지 못함**

#### 4. 신경-심볼릭 융합 추세
- SHARP: 사람이 읽을 수 있는 규칙 기반 정책 + LLM추론
- 금융 규제 준수와 해석 가능성에 유리한 방향

#### 5. 보안 취약성
- Adversarial News: 헤드라인 조작만으로 연간 수익률 **17.7%p 감소**
- 금융 AI 제품의 보안 아키텍처 설계가 시급

---

## 🏢 the research community 전략적 시사점

### 즉시 적용 가능 (Immediate)
1. **TradingAgents 프레임워크 → 한국어 특화:** KULLM을 backbone으로 한국 주식시장 특화 멀티에이전트 시스템 구축
2. **AlphaAgent → 한국 시장 알파 생성:** KURE 기반 한국어 금융 가설 생성 + AST 정규화

### 중기 연구 (Mid-term)
3. **FinAgent 멀티모달 아키텍처:** KULLM에 한국어 공시/뉴스/재무제표 멀티모달 모듈 추가
4. **SHARP 심볼릭 정책:** KURE의추론능력을 구조적 트레이딩 정칙으로 전환
5. **한국 시장 실시간 벤치마크:** DeepFund 참조하여 KRX 특화 평가 시스템 구축

### 장기 과제 (Long-term)
6. **보안 강화:** Adversarial News 연구 참조한 방어 메커니즘 설계
7. **재현성 표준:** Beyond Architecture의 7차원 평가 기준 자체 연구에 적용

### ⚠️ 주의사항
- **대부분 논문의 백테스팅 결과는 과대평가 가능성** (Time Travel 문제)
- **거래 비용/슬리피지 미고려 연구 다수** → 실전 성능은 보고된 것보다 낮을 가능성
- **한국 시장 특화 검증 없음** → 모든 프레임워크의 한국 시장 적용 시 재검증 필요

---

## 📊 분야 성숙도 평가

| 차원 | 점수 (1-5) | 설명 |
|------|-----------|------|
| 아키텍처 다양성 | ⭐⭐⭐⭐⭐ | 단일/멀티에이전트, MoE, 심볼릭 등 다양한 접근 |
| 재현성 | ⭐⭐ | 77개 연구 중 완전 재현 가능 0개 |
| 실전 검증 | ⭐⭐ | 대부분 백테스팅, 실시간 검증은 소수 |
| 한국 시장 적용 | ⭐ | 한국 특화 연구 거의 없음 |
| 보안 고려 | ⭐⭐ | Adversarial News 외 대부분 미고려 |
| 학술적 관심도 | ⭐⭐⭐⭐⭐ | NeurIPS, KDD, IEEE 등 최상위 venue 다수 |

---

*최종 업데이트: 2026-06-20*
*수집 소스: arXiv, Google Scholar, Semantic Scholar, ACM DL*
*논문 수: 20편 (2024-2026)*
*상위 논문(wow ≥80): 5편 → 블로그 초안 대상*
