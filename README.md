# 멀티에이전트 기반 AI worldcup 축구 에이전트 설계
---
## Random walk
> 로봇의 양측 바퀴 속도를 random으로 결정하는 알고리즘으로, 간단히 말하면 ‘무작위 움직임’ agent  

### 1. [`random-walk`](https://github.com/I-hate-Soccer/AI_Soccer/tree/main/Random%20Walk/random-walk)

---
## Dynamic planning
> Rule-Based 알고리즘을 기반으로 하며, 확고한 규칙을 가진 전략을 세우고 그에 따라 행동하는 agent

### 1. [`Standard role-based players`](https://github.com/I-hate-Soccer/AI_Soccer/tree/main/Dynamic%20Planning/Standard_role-based_players)
### 2. [`Gegenangriff`](https://github.com/I-hate-Soccer/AI_Soccer/tree/main/Dynamic%20Planning/Gegenangriff) - becoming extremely offensive players
### 3. [`Gegenpressing`](https://github.com/I-hate-Soccer/AI_Soccer/tree/main/Dynamic%20Planning/Gegenpressing) – becoming extremely defensive players
### 4. [`Becoming sprinters`](https://github.com/I-hate-Soccer/AI_Soccer/tree/main/Dynamic%20Planning/Becoming_sprinters)
### 5. [`Becoming defenders in the penalty area`](https://github.com/I-hate-Soccer/AI_Soccer/tree/main/Dynamic%20Planning/Becoming%20defenders%20in%20the%20penalty%20area)
### 6. [`Becoming man-to-man defenders`](https://github.com/I-hate-Soccer/AI_Soccer/tree/main/Dynamic%20Planning/Becoming%20man-to-man%20defenders)
### 7. [`Becoming ball-hunters`](https://github.com/I-hate-Soccer/AI_Soccer/tree/main/Dynamic%20Planning/Becoming_ball-hunters)
### 8. [`All Becoming goalies #1`](https://github.com/I-hate-Soccer/AI_Soccer/tree/main/Dynamic%20Planning/All%20Becoming%20goalies_1)
### 9. [`All Becoming goalies #2`](https://github.com/I-hate-Soccer/AI_Soccer/tree/main/Dynamic%20Planning/All%20Becoming%20goalies_2)  

---
## Multi-agent Reinforence Learning
> IQL과 QMIX 두 가지 알고리즘을 사용하며, random walk와 여러 규칙 기반 agent들을 상대로 학습시켜 모델을 얻는 agent
