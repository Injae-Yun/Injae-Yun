# 윤인재 (Injae Yun)

**AI Engineer** · 블루시그널 AI팀 팀장 · KAIST 계산뇌과학 박사

데이터 분석 및 현상을 설명하는 모델(ML/AI) 개발에 관심이 많습니다.
LLM, 파운데이션 모델, physical AI 등에 관심이 많으며 실제 환경에 구현해보는 일을 합니다.
연구 단계의 모델을 실제로 돌아가는 시스템으로 구현합니다.

[Google Scholar](https://scholar.google.com/citations?user=Hfo5N40AAAAJ&hl=en) · desty9367@gmail.com

---

## 바이오 · 제약

신약 후보물질의 효능·독성 예측과, 그것을 자동으로 수행하는 워크플로우.

| | |
|---|---|
| **[admet-agent](https://github.com/Injae-Yun/admet-agent)** | 후보물질 우선순위 지정 멀티 에이전트. LangGraph 5-노드 워크플로우 + FastAPI. 인용 검증을 결정적 검사와 LLM 판단 두 단계로 분리해, 근거 없는 주장이 리포트로 나가지 않도록 설계 |
| **[Drug_Efficacy_Toxicity_modeling](https://github.com/Injae-Yun/Drug_Efficacy_Toxicity_modeling)** | 저분자 구조·오믹스·핵산 서열 세 modality에 걸친 효능·독성 예측 재현. ChemProp(D-MPNN) · MolFormer-XL · RNA-FM. TDC DILI AUROC 0.895 (리더보드 0.886) |

## LLM · 에이전트

| | |
|---|---|
| **[LLM_qwen](https://github.com/Injae-Yun/LLM_qwen)** | 텍스트(Qwen2.5-7B + RAG)와 비전(Qwen2.5-VL-7B) 두 전문 에이전트가 이종 데이터를 교차 평가하는 프레임워크. 단일 GPU에서 에이전트 전환 시 VRAM 관리 |
| **[agent_society](https://github.com/Injae-Yun/agent_society)** | 욕구 기반 멀티 에이전트 시뮬레이션 + LLM 내러티브 생성. LLM 백엔드(HuggingFace / Ollama / Mock)를 교체 가능한 인터페이스로 추상화 |

## 운영 중인 시스템

| | |
|---|---|
| **[academy-attendance](https://github.com/Injae-Yun/academy-attendance)** | 학원 출결 관리 웹앱. 2년치 실데이터가 든 기존 11개 시트의 구조를 전혀 바꾸지 않는다는 제약 아래, 그 위에 얹는 방식으로 설계. 발송 provider 어댑터(2종) + 큐 + 트리거, 자격증명은 ScriptProperties 분리, 테스트 722개 |

## 게임 AI · 기타

| | |
|---|---|
| **[Neurosudoku](https://github.com/Injae-Yun/Neurosudoku)** | 그래프 어텐션 + 제약 전파 기반 neuro-symbolic solver |
| **[SpireAgent](https://github.com/Injae-Yun/SpireAgent)** | Slay the Spire 플레이 에이전트 |
| **[brain_ai](https://github.com/Injae-Yun/brain_ai)** | 뇌 구조에서 착안한 효율적 AI 에이전트 실험 |

---

## 연구

- **Yun, I.** et al. *Fine-Tuning-Free Deployment of Frozen Multimodal Foundation Encoders on Small-Cohort Wearable Biosignals.* **IEEE Access** (Under Review) · 제1저자
- Huh, N.; **Yun, I.**; Lee, J.W.; Jung, M.W. *A likelihood-based method for identifying replay from spike sequences.* **Nature Communications** (2026) · 공동 제1저자 · [doi](https://doi.org/10.1038/s41467-026-74822-2)
- Jeong, Y.; Huh, N.; Lee, J.; **Yun, I.**; et al. *Role of the hippocampal CA1 region in incremental value learning.* **Scientific Reports** 8, 9870 (2018)
- 장애물 영상 데이터 합성 기반 객체 탐지 모델 학습 방법. 국내 특허 출원 10-2025-0143428 (단독 발명자)

## 기술

`Python` `PyTorch` `Lightning` `HuggingFace` `LangGraph` `FastAPI` `Docker` `RDKit` `MATLAB` `SQL`
