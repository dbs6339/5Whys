# Incident Summary / 인시던트 정의서

## KOR

> 5 Whys 분석에 앞서, 인시던트의 전체 맥락을 정리합니다.
> 이 문서가 근본 원인 분석의 출발점이 됩니다.

### 기본 정보

| 항목 | 내용 |
|------|------|
| **인시던트 제목** | |
| **심각도** | P1 / P2 / P3 / P4 |
| **발생 일시** | YYYY-MM-DD HH:MM |
| **감지 일시** | YYYY-MM-DD HH:MM |
| **복구 일시** | YYYY-MM-DD HH:MM |
| **총 장애 시간** | |
| **작성자** | |
| **관련 팀** | |

### 영향 범위

| 항목 | 내용 |
|------|------|
| **영향받은 서비스** | |
| **영향받은 사용자 수** | |
| **비즈니스 영향** | (매출 손실, SLA 위반 등) |
| **영향받은 리전/환경** | |

### 타임라인

> 시간순으로 사건 경과를 기록합니다.

| 시각 | 이벤트 | 조치자 |
|------|--------|--------|
| HH:MM | (장애 발생) | |
| HH:MM | (장애 감지 - 수동/자동) | |
| HH:MM | (초기 대응) | |
| HH:MM | (원인 파악) | |
| HH:MM | (복구 완료) | |

### 인시던트 요약

> 장애가 무엇이었는지 2~3문장으로 요약합니다. 이 요약이 5 Whys의 출발점이 됩니다.

(여기에 작성)

### 감지 방법

- [ ] 자동 모니터링/알림에 의해 감지
- [ ] 수동으로 감지 (고객 리포트, 내부 발견 등)

> 자동 감지가 아닌 경우, 5 Whys 분석 시 감지 자동화를 반드시 다루어야 합니다.

---

## ENG

> Before starting 5 Whys analysis, summarize the full context of the incident.
> This document serves as the starting point for root cause analysis.

### Basic Information

| Field | Details |
|-------|---------|
| **Incident Title** | |
| **Severity** | P1 / P2 / P3 / P4 |
| **Occurred At** | YYYY-MM-DD HH:MM |
| **Detected At** | YYYY-MM-DD HH:MM |
| **Recovered At** | YYYY-MM-DD HH:MM |
| **Total Downtime** | |
| **Author** | |
| **Related Teams** | |

### Impact Scope

| Field | Details |
|-------|---------|
| **Affected Services** | |
| **Affected Users** | |
| **Business Impact** | (revenue loss, SLA violations, etc.) |
| **Affected Regions/Environments** | |

### Timeline

> Record the sequence of events in chronological order.

| Time | Event | Responder |
|------|-------|-----------|
| HH:MM | (Incident occurred) | |
| HH:MM | (Incident detected - manual/automated) | |
| HH:MM | (Initial response) | |
| HH:MM | (Root cause identified) | |
| HH:MM | (Recovery completed) | |

### Incident Summary

> Summarize the incident in 2-3 sentences. This summary becomes the starting point for 5 Whys.

(Write here)

### Detection Method

- [ ] Detected by automated monitoring/alerting
- [ ] Detected manually (customer report, internal discovery, etc.)

> If not detected automatically, the 5 Whys analysis MUST address detection automation.

---

**다음 단계 / Next Step**: → [5 Whys 분석](5Ways.md) 진행
