# 8StructuralThinkingInAIEra

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-blue?style=flat-square&logo=github)](https://inha20.github.io/8StructuralThinkingInAIEra/)
[![Field](https://img.shields.io/badge/Field-Cognitive%20Science%20%7C%20AI%20Education-orange?style=flat-square)](https://inha20.github.io/8StructuralThinkingInAIEra/)
**논문 제목:** 생성형 AI 시대의 구조적 사고와 인간-AI 연구 협력  
**Title:** Structural Thinking and Human-AI Research Collaboration in the Generative AI Era: A Framework Proposal, a Case Study, and Educational Implications  
**저자:** 최종훈 (Jonghun Choi) — 인하공업전문대학 졸업 · 독립 연구자  
**GitHub Pages:** [웹 논문 및 대화형 포털 보기](https://inha20.github.io/8StructuralThinkingInAIEra/)  

> 이 저장소의 논문은 같은 저자의 다른 저장소를 읽지 않아도 정의, 가설, 사례를 따라갈 수 있게 썼습니다. 사례에 쓰이는 수학 용어는 본문에서 풀어 쓰며, 증명은 자매 논문(7번)에 있습니다.

---

## 📌 Keywords
Structural thinking, Generative AI, Human-AI collaboration, Structure Recognition Theory (SRT), Human-AI Research Continuity Theory (HARCT), Metacognition, Distributed research memory, AI education, Karnaugh maps.

---

## 📖 Abstract (초록)

생성형 AI는 정형화된 문제의 답을 빠르게 산출한다. 이 환경에서 인간 연구자와 학습자에게 남는 역할이 무엇인지, 그리고 AI와 장기 연구를 어떻게 수행할지를 다룬다. 본 논문은 **이론 제안 논문**이며 가설의 검증 결과를 보고하지 않는다.

1. **SRT (Structure Recognition Theory):** 6단계 인지 흐름, 9단계 질문 계층, 10개 가설(H1~H10), 일부 가설의 검증 가능한 예측.
2. **HARCT (Human-AI Research Continuity Theory):** 분산 연구 기억, 핸드오버 프로토콜, 인지적 분업.
3. **단일 사례 연구 (n=1):** 한 연구자의 수학 연구 프로젝트에서 세 에피소드. 공유 기억이 오류도 전파한다는 점을 드러내어 독립 검증 단계를 이론에 추가한다.
4. **교육적 함의:** 과정 중심 교육 제안과 파일럿 연구 설계.

---

## 🧠 핵심 구성

### SRT 10개 가설 (요약)
| 번호 | 가설 | 핵심 명제 |
|:---:|:---|:---|
| H1 | Structure Discoverer | 인간은 구조 발견(구조를 찾고, 질문을 만들고, 의미를 부여하고, 연구 방향을 고르는 일)에서 비교우위를 가질 수 있다. 전체 능력의 차이가 아니라 **역할의 차이**를 뜻한다 |
| H2 | Representation Transformation | 어떤 어려운 문제는 계산량을 줄여서가 아니라 표상을 바꿈으로써(예: 논리식에서 카르노맵으로) 다루기 쉬워진다 |
| H3 | Attention Filter | 인간은 모든 패턴을 조사하지 않으며, 조사 이전에 선택 과정이 작동한다. 어떤 패턴이 통과하는지는 열린 문제이다 |
| H4 | Significance Filter | 주의 이후에 구조가 조사할 가치가 있는지를 평가하는 암묵적 필터가 작동한다. 통과 조건의 후보는 압축성, 예측력, 일반화력, 설명 견인력이다 |
| H5 | Explanation Anticipation | 인간은 설명을 찾기 전에 설명이 존재하리라고 예상한다. 패턴이 "무작위로 보이지 않는다"는 감각이 탐색에 선행한다 |
| H6 | Explanatory Significance | 연구는 구조 발견 자체가 아니라 구조가 지닌 설명적 잠재력의 감지에서 시작된다 |
| H7 | Mature Structure Discoverer (H1의 성숙판) | 인간의 핵심 우위는 패턴 인식 자체가 아니라, 어떤 구조가 설명적 유의성을 지니는지 평가하는 능력일 수 있다 |
| H8 | Concept-as-Lens | 개념은 관찰의 렌즈로 작동한다. 개념을 얻으면 구조로 인식할 수 있는 대상이 달라질 수 있다 |
| H9 | Concept Evolution | 연구는 개념을 낳고, 개념은 확장된 지각을 통해 새로운 연구를 낳는다 |
| H10 | Generative Concept | 개념마다 생성력이 다르다. 어떤 개념은 지각을 더 넓고 오래 확장한다 |

이 가설들은 **아직 실증되지 않았습니다.** 논문 3.4절에 검증 가능한 예측을 제시합니다. H3~H9는 SRT의 형식 정의 3.1~3.3의 조건과 연결됩니다(H3은 정의 3.2의 조건 4, H4·H5·H6·H7은 정의 3.3, H8·H9는 정의 3.1의 조건 1). 연결 표는 논문 3.4절에 있습니다.

### 공생적 연구 순환 (5단계)

1. 인간 직관 → AI 형식화
2. AI 연역·계산 → 인간 검토
3. **독립 검증** (사례 연구에서 도출되어 추가된 단계)
4. 인간 가치 부여 → 연구 확장
5. 공동 체계화 → 분산 기억 저장

---

## 📂 저장소 구조 (Repository Structure)

```
8StructuralThinkingInAIEra/
├─ README.md                               ← 저장소 안내 (본 문서)
├─ LICENSE                                 ← 이용 조건 (All rights reserved)
├─ index.html                              ← 대화형 웹 논문 포털
├─ images/                                 ← 논문 그림 6장 (7번 저장소 그림의 복사본, 출처는 images/README.md)
└─ paper/
   ├─ StructuralThinkingInAIEra.md         ← 논문 전문
   └─ 01_StructuralThinkingInAIEra.pdf     ← 논문 PDF (원고에서 생성)
```

---

## 🌐 관련 저장소 (선택 사항, 읽지 않아도 됨)

이 논문은 독립적으로 읽을 수 있습니다. 아래는 본 논문의 사례로 쓰인 수학 연구와 연구 프로그램 포털입니다. 사례의 근거 기록이 있는 저장소의 이름과 커밋은 논문 4.7절에 적었습니다.

| 저장소 | 내용 |
|:---|:---|
| [7GroupTheoryBooleanUnification](https://github.com/inha20/7GroupTheoryBooleanUnification) | 사례에 쓰인 수학 논문 (카르노맵 대칭 분류) |
| [Research-Portfolio](https://github.com/inha20/Research-Portfolio) | 전체 연구 프로그램 포털 |

---

## 📜 인용 정보 (Citation)

```bibtex
@misc{choi2026structuralthinking,
  author       = {Choi, Jonghun},
  title        = {Structural Thinking and Human-AI Research Collaboration in the Generative AI Era},
  howpublished = {Independent Interdisciplinary Research Program Preprint},
  year      = {2026},
  url       = {https://github.com/inha20/8StructuralThinkingInAIEra}
}
```

---
© 2026 Jonghun Choi (최종훈). All rights reserved. 이용 조건은 [LICENSE](LICENSE)를 참조하세요.
