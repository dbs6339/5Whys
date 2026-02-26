# 5 Whys Analysis / 5 Whys 분석

## KOR

> 장애를 면밀히 살펴보기 위하여 5 Whys 기법이 사용되며, 문제의 정의로부터 왜 장애가 발생했는지를 질문하고 근본 원인을 찾을 때까지 깊이를 들여다 볼 수 있습니다.
> 한가지 장애에도 여러 개의 원인이 존재할 수 있듯이 5 Whys 기법으로 근본원인 뿐만 아니라 대책방안을 도출할 수 있습니다.

### 작성 가이드

- **이전 답변(A)을 기반으로 다음 질문(Q)을 도출**합니다 (연쇄 구조)
- 각 단계에서 **분석 관점**을 표기하면 다양한 각도에서 원인을 파악할 수 있습니다
- 근본 원인에 도달하면 → [Poka Yoke 대책](Poka-yoke.md)으로 연결합니다

#### 분석 관점 태그

| 태그 | 설명 |
|------|------|
| `[감지]` | 왜 더 빨리 발견하지 못했는가? |
| `[대응]` | 왜 복구가 지연되었는가? |
| `[예방]` | 왜 사전에 방지하지 못했는가? |
| `[프로세스]` | 운영/배포/변경 관리 절차 문제 |
| `[시스템]` | 아키텍처/인프라/코드 결함 |

---

### 1Why

- **관점**: `[감지]` / `[대응]` / `[예방]` / `[프로세스]` / `[시스템]`
- Q: 장애의 복구가 10분 이내에 완료되지 않은 이유는 무엇입니까? *(10분 내 복구된 경우 질문 제거)*
- A:

### 2Why

- **관점**: `[ ]`
- Q: *(1Why의 답변을 기반으로 질문 작성)*
- A:

### 3Why

- **관점**: `[ ]`
- Q: *(2Why의 답변을 기반으로 질문 작성)*
- A:

### 4Why

- **관점**: `[ ]`
- Q: *(3Why의 답변을 기반으로 질문 작성)*
- A:

### 5Why

- **관점**: `[ ]`
- Q: *(4Why의 답변을 기반으로 질문 작성)*
- A:

### 근본 원인 요약

> 5 Whys 분석을 통해 도출된 근본 원인을 정리합니다.

| # | 근본 원인 | 분석 관점 | Poka Yoke 연결 |
|---|-----------|-----------|----------------|
| 1 | | | 단기 / 중기 / 장기 |
| 2 | | | 단기 / 중기 / 장기 |

### 자동 감지 방안

> 향후 동일 증상 발생 시 자동으로 감지할 수 있는 방안을 기술합니다.

| 감지 대상 | 모니터링 방법 | 알림 채널 | 담당자 | 상태 |
|-----------|--------------|-----------|--------|------|
| | | | | 미구축 / 구축완료 |

---

## ENG

> This section uses the 5 Whys technique to drill down from the problem definition to the root cause. Even a single incident can have multiple causes, and 5 Whys helps derive both root causes and countermeasures.

### Writing Guide

- **Derive each question (Q) from the previous answer (A)** (chain structure)
- Tag each step with an **analysis perspective** to explore causes from multiple angles
- Once root cause is reached → connect to [Poka Yoke countermeasures](Poka-yoke.md)

#### Analysis Perspective Tags

| Tag | Description |
|-----|-------------|
| `[Detection]` | Why wasn't it detected sooner? |
| `[Response]` | Why was recovery delayed? |
| `[Prevention]` | Why wasn't it prevented beforehand? |
| `[Process]` | Operations/deployment/change management issues |
| `[System]` | Architecture/infrastructure/code defects |

---

### 1Why

- **Perspective**: `[Detection]` / `[Response]` / `[Prevention]` / `[Process]` / `[System]`
- Q: Why the recovery from Incident was not done within 10 minutes? *(Remove this question if recovered within 10 minutes)*
- A:

### 2Why

- **Perspective**: `[ ]`
- Q: *(Derive from 1Why answer)*
- A:

### 3Why

- **Perspective**: `[ ]`
- Q: *(Derive from 2Why answer)*
- A:

### 4Why

- **Perspective**: `[ ]`
- Q: *(Derive from 3Why answer)*
- A:

### 5Why

- **Perspective**: `[ ]`
- Q: *(Derive from 4Why answer)*
- A:

### Root Cause Summary

> Summarize root causes derived from the 5 Whys analysis.

| # | Root Cause | Perspective | Poka Yoke Link |
|---|------------|-------------|----------------|
| 1 | | | Short / Medium / Long Term |
| 2 | | | Short / Medium / Long Term |

### Automated Detection Plan

> Describe how similar symptoms can be automatically detected in the future.

| Target | Monitoring Method | Alert Channel | Owner | Status |
|--------|------------------|---------------|-------|--------|
| | | | | Not built / Completed |

---

**이전 단계 / Previous Step**: ← [인시던트 정의서](Incident-Summary.md)
**다음 단계 / Next Step**: → [Poka Yoke 대책](Poka-yoke.md)
