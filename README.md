## 🔬 주요 프로젝트

| 프로젝트 | 설명 | 기술 |
|---|---|---|
| [🎯 Game AI QA Evaluator](https://github.com/haneulk1004/game-ai-qa-evaluator) | Game AI Agent 응답을 4개 지표로 자동 채점 · 한국어 혐오표현 데이터셋 연동 | HTML · JS |
| [⚔️ CombatTestGen](https://github.com/haneulk1004/CombatTestGen) | 전투 시스템 테스트 케이스 자동 생성 | Python |
| [🔍 Universal Game QA Tool](https://github.com/haneulk1004/universal-game-qa-tool) | AI 기반 게임 리뷰 분석 및 QA 자동화 시스템 | JavaScript |
| [📊 Research Game QA Tool](https://github.com/haneulk1004/Research-game-qa-tool) | 모든 게임 장르 지원 실시간 유저 리뷰 분석 & QA 인사이트 도출 | JavaScript |
| [⚾ Baseball Game QA Tool](https://github.com/haneulk1004/baseball-game-qa-tool) | AI 기반 야구 게임 QA 리서치 툴 | JavaScript |
| [🎰 Gacha Prob Insight](https://github.com/haneulk1004/Gacha-Prob-Insight) | 가챠 확률 분석 인사이트 툴 | HTML |
| [💰 PriceCheck](https://github.com/haneulk1004/pricecheck) | 사진 한 장으로 제품 식별 · 시장 가치 추론 | HTML |
| [🎙️ Voice De-Noise](https://github.com/haneulk1004/voice-de-noise) | 음성 노이즈 제거 툴 | JavaScript |

---

## 💡 관심 분야

```
Game AI QA   ── LLM 응답 품질 평가 · Safety 필터 · 프롬프트 회귀 테스트
QA 자동화    ── 테스트 케이스 생성 · 리뷰 분석 · 이슈 트래킹
게임 분석    ── 유저 리뷰 인사이트 · 확률 검증 · 밸런스 QA
```

---

## 🛠️ 기술 스택

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white)

---

## 📌 주목 프로젝트 — Game AI QA Evaluator

> LLM 기반 Game AI Agent 응답 품질을 수치로 평가하는 QA 자동화 툴

**배경**  
AI NPC는 동일한 입력에도 매번 다른 응답을 생성합니다.  
기존 Pass/Fail 체크리스트 방식으로는 이 **비결정적 출력을 검수하는 데 한계**가 있습니다.

**해결책**  
4개 품질 지표로 모든 응답을 수치화합니다.

| 지표 | 가중치 | 의미 |
|---|---|---|
| 정확성 (Groundedness) | 30% | 게임 세계관 DB와 일치하는가 |
| 자연스러움 (Fluency) | 25% | 캐릭터 말투가 어울리는가 |
| 안전성 (Safety) | 30% | 부적절한 표현이 없는가 |
| 일관성 (Consistency) | 15% | 캐릭터 설정과 모순 없는가 |

**특징**
- ✅ 설치 없음 · 인터넷 불필요 — HTML 파일 하나로 즉시 실행
- 🔴 한국어 혐오표현 데이터셋 연동 (Smilegate AI UnSmile, CC-BY-NC-ND 4.0)
- 📚 단어 학습 기능 — 미감지 표현 즉시 추가 · 일괄 등록
- 🎛️ 자동 채점 + 수동 채점 하이브리드 구조

**[▶ 라이브 데모 바로가기](https://haneulk1004.github.io/game-ai-qa-evaluator/qa-evaluator-demo.html)**

---

## 📫 연락처

[![GitHub](https://img.shields.io/badge/GitHub-haneulk1004-181717?style=flat-square&logo=github)](https://github.com/haneulk1004)
