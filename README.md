# 5Whys — 인시던트 근본 원인 분석 프레임워크

인시던트(장애) 발생 시 근본 원인을 체계적으로 분석하고 재발을 방지하기 위한 템플릿 저장소입니다.

## 분석 프로세스

```
① 인시던트 정의  →  ② 5 Whys 분석  →  ③ Poka Yoke 대책
```

| 단계 | 문서 | 목적 |
|------|------|------|
| ① 인시던트 정의 | [Incident-Summary.md](Incident-Summary.md) | 장애 맥락 정리 (심각도, 타임라인, 영향 범위) |
| ② 5 Whys 분석 | [5Ways.md](5Ways.md) | 반복적 "왜?" 질문으로 근본 원인 도출 |
| ③ Poka Yoke 대책 | [Poka-yoke.md](Poka-yoke.md) | 단기/중기/장기 재발 방지 대책 수립 및 추적 |

## 사용법

1. **인시던트 발생 시** → `Incident-Summary.md`를 복사하여 기본 정보와 타임라인을 작성합니다.
2. **원인 분석** → `5Ways.md`에서 이전 답변을 기반으로 연쇄적으로 "왜?"를 질문합니다.
3. **대책 수립** → `Poka-yoke.md`에서 근본 원인별 대책을 매핑하고 담당자/기한/상태를 관리합니다.

## How to Use (English)

1. **When an incident occurs** → Copy `Incident-Summary.md` and fill in basic info and timeline.
2. **Root cause analysis** → In `5Ways.md`, chain "Why?" questions based on each previous answer.
3. **Countermeasures** → In `Poka-yoke.md`, map countermeasures to root causes and track owner/due date/status.
