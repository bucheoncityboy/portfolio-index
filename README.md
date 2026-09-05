# 김재원 (Jaewon Kim) — 이력서 & 포트폴리오 인덱스

> **Quant Researcher · AI Agent System Engineer**
> 한양대학교 경영학부 졸업 · 투자자산운용사 합격 · 주식 운용/리서치 인턴 지원

| 연락처 | |
|---|---|
| Email | kjw582390@gmail.com |
| H.P | 010-2570-5823 |
| GitHub | [github.com/bucheoncityboy](https://github.com/bucheoncityboy) |

---

## 1. 학력

| 학교 | 전공 | 기간 | 비고 |
|---|---|---|---|
| 한양대학교(서울) | 경영학부 (주전공) · 정보시스템학과 (제2전공) | 2019.03 – 2026.08 | 졸업 · **3.65 / 4.5** |
| 수주고등학교 | 인문계 | 2015.03 – 2018.02 | 졸업 |

## 2. 교내 활동

| 활동 | 주요 내용 | 기간 |
|---|---|---|
| **HY-FIN 재무금융학회** | Fama-French 모형 기반 한국 시장 실증 분석 / 환위험 관리 및 환헤지 연구 논문 / WorldQuant Brain 산학협력 | 2025.09 – 2026.07 |
| **Quantitative Analytics Lab (학부연구생)** | 금융 머신러닝(Meta-Labeling) 연구 / 금융 시계열 꼬리위험 정량화 및 리스크 관리 | 2025.09 – 2025.12 |

## 3. 자격증 · 어학

| 구분 | 내용 | 취득일 / 점수 |
|---|---|---|
| 자격증 | 투자자산운용사 (금융투자협회) | 2025.10.30 |
| 자격증 | ADsP 데이터분석 준전문가 (한국데이터산업진흥원) | 2024.05.31 |
| 자격증 | SQL 개발자 (한국데이터산업진흥원) | 2024.04.05 |
| 어학 | TOEIC Speaking | 130 / 200 (중) |
| 컴퓨터 활용 | Excel / 한글 / PowerPoint / MS Word | 상 |

## 4. 경력 (인턴)

| 회사 | 부서 | 담당 업무 | 기간 |
|---|---|---|---|
| 진저티프로젝트 | 조직문화 | 보고서 작성 · 인터뷰 전사 · 기업 행사 보조 | 2023.06 – 2023.08 |
| 링커리어 | 마케팅 | 보고서 작성 · 콘텐츠 제작 · CS 응대 · 커뮤니티 관리 | 2024.09 – 2024.12 |

---

## 5. 프로젝트 포트폴리오

교내 활동과 연구에서 직접 구축한 저장소들입니다. 면접 시 아래 링크의 README와 코드를 참고해 주세요.

### 리서치 · 논문 (교내 활동 연계)

| 저장소 | 한 줄 설명 | 핵심 성과 |
|---|---|---|
| [**fama-french-korea-factor**](https://github.com/bucheoncityboy/fama-french-korea-factor) | 한국 시장 Fama-French 3-Factor 실증 (HY-FIN) | FnGuide **1,054종목 · 311개월** 패널 ETL → 25개 Size×BM 포트폴리오 GRS 검정. HML 유의(t=3.89) · **SMB 부호 반전**(-0.67%/월) 발견 |
| [**deep-quant-risk-haqr**](https://github.com/bucheoncityboy/deep-quant-risk-haqr) | 계층적 어텐션 분위수 회귀로 꼬리위험 정량화 (QA Lab) | Non-Crossing Quantile Head · **Sharpe 1.05** (LGBM 0.82 대비) · Pinball 0.00584 · 손실구간 91% 적중 |
| [**Dynamic-Shield-K-ICS-AI**](https://github.com/bucheoncityboy/Dynamic-Shield-K-ICS-AI) | K-ICS 자본 효율 극대화 AI 동적 환헤지 시스템 (환헤지 논문, 팀 저녁은 뉴욕에서) | "Risk Paradox" 증명 · HMM 국면인식 + PPO 강화학습 · 실데이터 5,292일 검증 · **자본비용 최대 10.38% 절감** |
| [**quant-alpha-agent-harness**](https://github.com/bucheoncityboy/quant-alpha-agent-harness) | WorldQuant BRAIN 알파 마이닝 LLM 에이전트 하네스 (산학협력) | 통계 가드레일 + 5-Gate 제출 파이프라인 · **유효 알파 70개 발굴** · 리서치 컨설턴트 계약 체결 |

### AI 에이전트 · 엔지니어링

| 저장소 | 한 줄 설명 | 핵심 성과 |
|---|---|---|
| [**agentic-research-pipeline**](https://github.com/bucheoncityboy/agentic-research-pipeline) | AI Agent 기반 기업분석 리포트 자동화 | DART/FnGuide/KRX 등 **7개 소스 연동** · 4단계 Fail-Closed 검증 게이트 · 592개 단위 테스트 · 19종목 커버리지 · 샘플 결과물 6건 |
| [**harness-engineering**](https://github.com/bucheoncityboy/harness-engineering) | 확률적 AI 출력을 결정적 시스템으로 통제하는 하네스 아키텍처 | 3-Layer 구조 (Deterministic Shell · Middleware Chain · Policy Layer) + oh-my-openagent 사례 분석 |

### 운용 시스템

| 저장소 | 한 줄 설명 | 핵심 성과 |
|---|---|---|
| [**quantamental-kr**](https://github.com/bucheoncityboy/quantamental-kr) | KOSPI200/KOSDAQ150 대상 주간 퀀타멘탈 운용 엔진 | OLS 시장·섹터 중립화로 순수 알파 추출 · Black-Litterman 최적화 · Human-in-the-loop 매니저 승인 |

### 기타 공개 저장소

[token-tracker](https://github.com/bucheoncityboy/token-tracker) · [kr-stock-report](https://github.com/bucheoncityboy/kr-stock-report) · [llm-alignment-coding](https://github.com/bucheoncityboy/llm-alignment-coding) · [fama-ff3-](https://github.com/bucheoncityboy/fama-ff3-) · [Fama-French-The-Cross-Section-of-Expected-Stock-Returns-](https://github.com/bucheoncityboy/Fama-French-The-Cross-Section-of-Expected-Stock-Returns-)

---

## 6. 기술 스택

- **Quant/Finance**: WorldQuant BRAIN · Fama-French 팩터 모델 · 분위수 회귀 · Black-Litterman · PSR/DSR · GRS 검정 · K-ICS
- **ML/AI**: TensorFlow · PyTorch · Hierarchical Attention · HMM · PPO (stable-baselines3) · Meta-Labeling
- **Data/Engineering**: Python · pandas · statsmodels · FastAPI · SQLite · pytest · FnGuide/KRX/DART API

---

*포트폴리오 제출용 저장소입니다. 프로젝트별 상세는 각 링크에서 확인해 주세요.*
