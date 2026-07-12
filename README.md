<div align="center">

# Jang1J

**AI Systems Builder**

신뢰할 수 있는 AI 시스템, 멀티에이전트 파이프라인, 재현 가능한 ML 실험을 만듭니다.

[![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-ML-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![LightGBM](https://img.shields.io/badge/LightGBM-Ranking-2C8C3C)](https://lightgbm.readthedocs.io/)
[![gRPC](https://img.shields.io/badge/gRPC-Services-244C5A?logo=google&logoColor=white)](https://grpc.io/)
[![Kafka](https://img.shields.io/badge/Apache_Kafka-Events-231F20?logo=apachekafka&logoColor=white)](https://kafka.apache.org/)

</div>

## About

모델의 정확도만큼 **운영 안전성, 데이터 시점 정합성, 실패 시 복구 가능성**을 중요하게 생각합니다. 연구 아이디어를 코드로 옮기는 데서 멈추지 않고, 계약·검증·관측 가능성을 갖춘 시스템으로 완성하는 작업에 관심이 있습니다.

- Multi-agent AI orchestration and decision systems
- Financial ML, ranking, reinforcement learning, and risk controls
- Reproducible evaluation, contract testing, and paper-safe operations
- Python 중심의 AI와 Java/TypeScript 기반 서비스 경계 통합

## Toolbox

| Layer | Stack |
|---|---|
| **AI / ML** | Python, PyTorch, LightGBM, scikit-learn, reinforcement learning |
| **Agent Systems** | Multi-agent orchestration, RAG, LLM routing, typed contracts |
| **Services** | gRPC, Kafka, REST, STOMP, Spring Boot |
| **Frontend** | TypeScript, React, Vite |
| **Reliability** | pytest, replay validation, PIT-safety, audit logging, circuit breaker |

## Featured Project

### [Flephant](https://github.com/Jang1J/Flephant)

KOSPI 30종목을 1분 주기로 분석하는 멀티에이전트 Decision OS입니다. 장중의 저지연 정량 경로와 이벤트 기반 LLM 경로, 장마감 후 모델 검증 경로를 하나의 paper-safe 시스템으로 연결했습니다.

| Area | Implementation |
|---|---|
| Decision pipeline | LightGBM ranking → PPO allocation → portfolio manager → FDA approve/veto |
| Agent system | Quant, News, Risk, Debate, FDA, Backtest agents |
| Reliability | 18 API contracts, PIT-safety, replay gates, audit trail |
| Integration | gRPC, Kafka, REST, STOMP |
| Result | Capstone project **A+**, 2,221 tests collected |

[프로젝트 자세히 보기 →](https://github.com/Jang1J/Flephant#readme)

## More Work

| Project | Focus |
|---|---|
| [GPT-2 Sonnet Generation](https://github.com/Jang1J/gpt2-sonnet-generation) | 구조 제약 디코딩과 재현 가능한 생성 품질 평가 |
| [Food Regulation Chatbot](https://github.com/Jang1J/food-regulation-chatbot) | 식품 법규 문서를 위한 RAG 기반 질의응답 |
| [Food Safety Mailer](https://github.com/Jang1J/food-safety-mailer) | 글로벌 식품 안전정보 자동 수집 및 이메일 전달 |
| [Nuclear AI NAS](https://github.com/Jang1J/26_nuclear_ai_NAS) | 원전 사고 진단을 위한 AI 모델 탐색 |

## GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Jang1J&theme=github_dark">
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Jang1J&theme=github">
  <img alt="Jang1J GitHub profile summary" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Jang1J&theme=github">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Jang1J&bg_color=0d1117&color=c9d1d9&line=2f81f7&point=58a6ff&area=true&hide_border=true">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Jang1J&bg_color=ffffff&color=24292f&line=0969da&point=0550ae&area=true&hide_border=true">
  <img alt="Jang1J contribution activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=Jang1J&bg_color=ffffff&color=24292f&line=0969da&point=0550ae&area=true&hide_border=true">
</picture>

</div>

## Engineering Principles

```text
correctness before cleverness
evidence before confidence
fail closed on unsafe transitions
make experiments reproducible
```
