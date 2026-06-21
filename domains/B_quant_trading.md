# B 영역: 정량 트레이딩 (Quantitative Trading) 시드 논문 분석

> 수집일: 2026-06-20
> 분야: Quantitative Trading / Factor Investing / Statistical Arbitrage / Financial Econometrics

---

## 1. Fama & French (1992) - The Cross-Section of Expected Stock Returns

| 항목 | 내용 |
|------|------|
| **저자** | Eugene F. Fama, Kenneth R. French |
| **연도** | 1992 |
| **게재지** | The Journal of Finance, Vol. 47, No. 2, pp. 427–465 |
| **DOI** | `10.1111/j.1540-6261.1992.tb04398.x` |
| **인용 수** | ~16,000+ (Google Scholar 기준) |

### 초록 (요약)
NYSE, AMEX, NASDAQ에 상장된 주식의 단면 평균수익률에서 시장 베타(β), 기업 규모(Size), 주가수익비(E/P), 레버리지(Leverage), 장부가/시가비(Book-to-Market Equity)의 공동 역할을 실증 분석. 시장 베타만으로는 수익률 변동을 설명할 수 없으며, **기업 규모와 장부가/시가비(B/M)가 결합**하여 주식 수익률의 단면 변동을 포착함을 보임.

### 핵심 기여
- **CAPM의 시장 베타 단독으로는 주식 수익률을 설명하지 못함**을 실증적으로 입증
- **Size(규모)와 B/M(가치) 팩터**가 주식 수익률의 단면 변동을 설명하는 핵심 변수임을 발견
- 이후 Fama-French 3-factor 모델의 기반이 되는 핵심 실증 근거를 제시

### 정량 트레이딩에 대한 중요도
- **팩터 투자(Factor Investing)의 출발점**: 가치(Value) 팩터와 규모(Size) 팩터의 존재를 최초로 체계적으로 입증
- 모든 후속 팩터 모델(3-factor, 5-factor, 6-factor 등)의 출발점
- 정량적 포트폴리오 구축 시 팩터 노출(Style Exposure) 관리의 이론적 근거

---

## 2. Fama & French (2015) - A Five-Factor Asset Pricing Model

| 항목 | 내용 |
|------|------|
| **저자** | Eugene F. Fama, Kenneth R. French |
| **연도** | 2015 |
| **게재지** | Journal of Financial Economics, Vol. 116, No. 1, pp. 1–22 |
| **DOI** | `10.1016/j.jfineco.2014.10.010` |
| **SSRN** | `2287202` |
| **인용 수** | ~12,800 (Google Scholar 기준) |

### 초록 (요약)
기존 3-factor 모델(Market, Size, Value)에 **수익성(Profitability, RMW)**과 **투자(Investment, CMA)** 팩터를 추가한 5-factor 자산가격결정 모델을 제안. 이 모델은 3-factor 모델보다 평균 수익률 변동을 더 잘 설명하며, 수익성과 투자 팩터가 포함되면 가치(HML) 팩터는 설명력이 중복(redundant)해질 수 있음을 보임.

### 핵심 기여
- **5-factor 모델 제안**: Market(Mkt-RF), Size(SMB), Value(HML), Profitability(RMW), Investment(CMA)
- 수익성이 높고 투자가 보수적인 기업이 초과수익을 올리는 패턴을 체계적으로 포착
- 가치 팩터(HML)가 수익성·투자 팩터와 함께 사용 시 중복될 수 있음을 발견

### 정량 트레이딩에 대한 중요도
- **현대 팩터 투자의 표준 모델**: 수익성(RMW)과 투자(CMA) 팩터를 활용한 전략 설계의 기초
- 정량 전략의 알파 소스를 확장: 기존 Value + Size에서 Profitability + Investment로 확장
- 포트폴리오 리스크 모델링 시 다차원 팩터 익스포처 계산의 기준선

---

## 3. Jegadeesh & Titman (1993) - Returns to Buying Winners and Selling Losers

| 항목 | 내용 |
|------|------|
| **저자** | Narasimhan Jegadeesh, Sheridan Titman |
| **연도** | 1993 |
| **게재지** | The Journal of Finance, Vol. 48, No. 1, pp. 65–91 |
| **DOI** | `10.1111/j.1540-6261.1993.tb04702.x` |
| **인용 수** | ~18,200 (Google Scholar 기준) |

### 초록 (요약)
과거 3~12개월간 상대적으로 높은 수익률을 기록한 주식(승자)을 매수하고, 낮은 수익률을 기록한 주식(패자)을 매도하는 전략이 **3~12개월 투자 기간에서 유의미한 양(+)의 초과수익**을 생성함을 실증. 이 현상은 거래비용을 고려한 후에도 지속되며, 주식시장의 효율성에 대한 도전적 증거를 제공.

### 핵심 기여
- **모멘텀(Momentum) 효과의 최초 체계적 실증 문서화**: 3-12개월 단기 모멘텀의 존재를 입증
- 과거 수익률 기반 순위 전략(Ranking Strategy)의 수익성 검증
- 시장 효율성 가설에 대한 강력한 반례(Anomaly) 제시

### 정량 트레이딩에 대한 중요도
- **모멘텀 전략의 바이블**: 거의 모든 정량 펀드가 모멘텀 팩터를 포트폴리오에 포함
- Cross-sectional momentum과 time-series momentum의 이론적 근거
- 팩터 모델에 모멘텀 팩터(UMD, Up Minus Down)를 추가하는 계기

---

## 4. Gatev, Goetzmann & Rouwenhorst (2006) - Pairs Trading: Performance of a Relative-Value Arbitrage Rule

| 항목 | 내용 |
|------|------|
| **저자** | Evan Gatev, William N. Goetzmann, K. Geert Rouwenhorst |
| **연도** | 2006 |
| **게재지** | The Review of Financial Studies, Vol. 19, No. 3, pp. 797–827 |
| **DOI** | `10.1093/rfs/hhj017` |
| **NBER** | Working Paper No. 7032 |
| **인용 수** | ~3,500+ (Google Scholar 기준) |

### 초록 (요약)
월스트리트의 투자 전략인 **페어스 트레이딩(Pairs Trading)**을 1962–2002년 일간 데이터로 실증 검증. 주식을 **거리(Distance) 기반**으로 페어로 매칭하고, 형성 기간(Formation Period) 중 가격 차이가 커진 페어에 대해 거래 기간(Trading Period)에 평균회귀를 이용한 차익거래를 수행. **월 평균 1.4%의 초과수익**을 보고하며, 이는 일시적 가격 비효율성에서 발생함을 시사.

### 핵심 기여
- **페어스 트레이딩 전략의 최초 학술적 실증 검증**: Distance 방법론을 통한 체계적 접근법 제시
- 시장 중립(Market Neutral) 전략의 실증 성과 입증
- 통계적 차익거래(Statistical Arbitrage) 분야의 학문적 토대를 구축

### 정량 트레이딩에 대한 중요도
- **페어스 트레이딩/시장중립 전략의 표준 참조 논문**
- Distance 기반 매칭 → 이후 공적분(Cointegration) 기반, ML 기반 페어 선별로 진화
- 정량적 차익거래 전략의 실현 가능성과 수익성을 학술적으로 검증한 첫 논문

---

## 5. Avellaneda & Lee (2010) - Statistical Arbitrage in the US Equities Market

| 항목 | 내용 |
|------|------|
| **저자** | Marco Avellaneda, Jeong-Hyun Lee |
| **연도** | 2010 |
| **게재지** | Quantitative Finance, Vol. 10, No. 7, pp. 761–782 |
| **DOI** | `10.1080/14697680903124632` |
| **SSRN** | `1153505` |
| **인용 수** | ~600+ (Google Scholar 기준) |

### 초록 (요약)
미국 주식시장에서 모델 기반 **통계적 차익거래(Statistical Arbitrage)** 전략을 백테스팅 및 비교. 거래 신호를 두 가지 방식으로 생성: **(1) 주성분 분석(PCA)**을 이용한 공통 팩터 추출, **(2) 섹터 ETF**를 체계적 팩터 대리변수로 활용. 잔차(고유 수익률)를 평균회귀 과정으로 모델링하여 역방향(Contrarian) 거래 신호를 생성. 일간 거래량 정보를 **거래 시간(Trading Time)**으로 반영하는 새로운 방법론을 도입하여 성과를 크게 개선. PCA 기반 전략은 1997–2007 평균 연 **Sharpe ratio 1.44**를 달성.

### 핵심 기여
- **PCA 및 섹터 ETF 기반 통계적 차익거래 모델**의 체계적 구현 및 비교
- **Trading Time**(거래량 기반 시간 척도)이라는 혁신적 방법론 도입
- 2007년 유동성 위기(Quant Crisis) 동안 전략 성과를 분석하고 위기 원인을 해석

### 정량 트레이딩에 대한 중요도
- **현대 통계적 차익거래의 실무 표준**: PCA 기반 잔차 거래의 학술적 레퍼런스
- 퀀트 크라이시스(2007년 8월) 분석 — 전략 붕괴 메커니즘 이해의 핵심 자료
- 대규모 포트폴리오에서 개별 주식의 고유 위험을 추출·거래하는 방법론의 원형

---

## 6. Engle (1982) - Autoregressive Conditional Heteroscedasticity with Estimates of the Variance of United Kingdom Inflation

| 항목 | 내용 |
|------|------|
| **저자** | Robert F. Engle |
| **연도** | 1982 |
| **게재지** | Econometrica, Vol. 50, No. 4, pp. 987–1007 |
| **DOI** | `10.2307/1912773` |
| **인용 수** | ~37,600+ (Google Scholar 기준) |

### 초록 (요약)
전통적 계량경제 모델이 가정하는 **일정한 분산(constant variance)** 대신, 오차항의 분산이 과거 오차들의 함수로 변동하는 **ARCH(Autoregressive Conditional Heteroscedasticity) 모델**을 제안. 영국 인플레이션 데이터에 적용하여 ARCH 효과의 유의미함을 입증하고, 조건부 분산의 시변(time-varying) 특성을 포착.

### 핵심 기여
- **ARCH 모델 최초 제안**: 시변 변동성(Time-Varying Volatility) 모델링의 출발점
- 금융 시계열의 **변동성 군집(Volatility Clustering)** 현상을 설명하는 프레임워크 제공
- 이후 GARCH, EGARCH, GARCH-M 등 수백 가지 변형 모델의 원형 — 2003년 노벨 경제학상 수상의 핵심 업적

### 정량 트레이딩에 대한 중요도
- **리스크 관리의 수학적 기초**: VaR, 포트폴리오 최적화에서 변동성 추정의 핵심 도구
- 옵션 가격결정(Black-Scholes 확장)에서 시변 변동성 반영의 이론적 근거
- 모든 정량 전략의 리스크 모델링에서 GARCH 계열 모델은 필수적 구성요소

---

## 7. Engle & Granger (1987) - Co-integration and Error Correction: Representation, Estimation, and Testing

| 항목 | 내용 |
|------|------|
| **저자** | Robert F. Engle, Clive W. J. Granger |
| **연도** | 1987 |
| **게재지** | Econometrica, Vol. 55, No. 2, pp. 251–276 |
| **DOI** | `10.2307/1913236` |
| **인용 수** | ~30,000+ (Google Scholar 기준) |

### 초록 (요약)
**공적분(Co-integration)**과 **오차수정(Error Correction)** 모델 간의 관계를 Granger(1983)의 표현 정리에 기반하여 체계적으로 확립. 비정상(non-stationary) 시계열 간의 장기 균형 관계를 포착하는 공적분 방법론을 제시하고, 이를 오차수정 모델(ECM)과 연결하는 representation theorem을 제공. Engle-Granger 2단계 검정법(ADF 검정 기반)을 도입.

### 핵심 기여
- **공적분(Cointegration) 이론의 확립**: 비정상 시계열 간 장기 균형 관계를 포착하는 방법론
- **Engle-Granger 2단계 검정법** 제시: 실증 연구에서 널리 사용되는 공적분 검정 방법
- 오차수정 모델(ECM)과의 연결을 통한 단기·장기 동학(Dynamics)의 통합적 모델링 프레임워크

### 정량 트레이딩에 대한 중요도
- **페어스 트레이딩의 이론적 기초**: 공적분 관계를 이용한 페어 선별 및 평균회귀 전략의 핵심 도구
- Distance 기반 페어스 트레이딩을 넘어 **통계적으로 엄밀한 관계 기반 차익거래**의 기초
- Granger는 이 업적으로 2003년 노벨 경제학상 수상 (Engle과 공동)

---

## 요약 테이블

| # | 논문 | 연도 | 핵심 주제 | 인용 수 | 정량 트레이딩 기여 |
|---|------|------|-----------|---------|-------------------|
| 1 | Fama & French (1992) | 1992 | Size + Value 팩터 | ~16,000 | 팩터 투자의 출발점 |
| 2 | Fama & French (2015) | 2015 | 5-factor 모델 | ~12,800 | 현대 팩터 모델 표준 |
| 3 | Jegadeesh & Titman (1993) | 1993 | 모멘텀 효과 | ~18,200 | 모멘텀 전략의 바이블 |
| 4 | Gatev et al. (2006) | 2006 | 페어스 트레이딩 | ~3,500 | 시장중립 전략 실증 |
| 5 | Avellaneda & Lee (2010) | 2010 | 통계적 차익거래 | ~600 | PCA 기반 stat arb |
| 6 | Engle (1982) | 1982 | ARCH 모델 | ~37,600 | 변동성 모델링 기초 |
| 7 | Engle & Granger (1987) | 1987 | 공적분 + ECM | ~30,000 | 페어 트레이딩 이론 기초 |

---

## 분야별 분류

### 팩터 모델 / 자산가격결정
- Fama & French (1992): Value + Size 팩터 발견
- Fama & French (2015): 5-factor 모델 확립
- Jegadeesh & Titman (1993): Momentum 팩터 발견

### 차익거래 / 시장중립 전략
- Gatev et al. (2006): Pairs Trading 실증
- Avellaneda & Lee (2010): Statistical Arbitrage (PCA/ETF 기반)

### 금융 계량경제학 (모델링 기초)
- Engle (1982): ARCH — 변동성 모델링
- Engle & Granger (1987): Cointegration — 장기균형 관계 모델링

---

*이 7편의 논문은 정량 트레이딩의 이론적 기반을 형성하며, 팩터 투자, 모멘텀 전략, 페어스 트레이딩, 통계적 차익거래, 변동성 모델링, 공적분 분석 등 현대 퀀트 전략의 모든 핵심 분야를 포괄합니다.*
