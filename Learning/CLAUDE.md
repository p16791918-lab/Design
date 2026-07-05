# 증례 발표 PPT 표준 흐름 (CLAUDE.md)

이 프로젝트의 모든 증례 발표 덱은 **아래 흐름**으로 만든다. (호흡기 CAP 증례 덱의 구조를 표준으로 채택함.)
디자인은 **Med Case Presentation System**(Pretendard·인디고·표 중심·이상치 빨강볼드·챕터/페이지 크롬)을 그대로 따른다.

## PART 1 — Case Presentation (증례)

1. **Title** — 풀-인디고 타이틀 슬라이드 (진단명 + 과 + 학번/조/날짜)
2. **Chief Complaint & Present Illness (CC/PI)** — 나이/성별, CC, 시간순 PI
3. **History** — PMH · Operation Hx · Medication Hx · Family Hx · Social History
4. **ROS & Physical Examination** — 계통문진 + V/S + 신체검진 (양성/음성 대비)
5. **Initial studies** — ECG, CXR 등 초기 검사. **이전 영상과 나란히 비교**
6. **Initial Impression** — 감별진단 여러 개를 R/O 형태로 나열 (흐름의 중심축)
7. **Diagnostic Plan** — 위 감별 각각을 겨냥한 검사 배치
8. **Laboratory findings** — 표 중심. 이상치는 빨강+볼드
9. **Advanced imaging (CT 등)** — 영상으로 감별을 하나씩 좁히고 배제
10. **Assessment** — 최종 임상 판단 (most likely / less likely 정리)
11. **Therapeutic Plan** — 문제별 치료 (약제 표 포함)
12. **Progress Note (입원 경과)** — 치료 반응 → 실패 시 항생제/치료 상향 → 호전 → 퇴원. (CRP 등 추이, 날짜 비교)
13. **Discharge medications** — 퇴원 약제

## PART 2 — Disease Review (질환 리뷰)

주제 질환을 교과서 순서로 정리:
- Definition & Classification
- Pathophysiology
- Pathology
- Etiology
- Clinical Manifestations (증상 + 신체검진)
- Diagnosis (clinical / differential / etiologic)
- **Severity Assessment** (해당 질환의 중증도 도구 — 예: CURB-65, PSI)
- Treatment (상황별: 외래/입원/중환자)
- Reevaluation / Failure to improve
- Complications & Follow-up

- **Reference** — Harrison 등 교과서 + UpToDate 등

## 원칙

- **감별 축을 살릴 것**: "여러 감별 나열(6) → 검사로 각각 배제(8·9) → 확진(10)"이 덱의 골격.
- **경과(Progress Note)를 반드시 포함**: 실제 병원 경과(치료 실패→상향→호전→퇴원)를 날짜·수치 추이로.
- **비교 영상** 적극 사용 (이전 vs 이번).
- 질환 리뷰 분량은 사용자와 합의 (전체 유지 vs 핵심 압축).
- 이상치·red flag는 `#C00000` 빨강+볼드만 사용. 챕터번호·페이지번호·푸터 브랜드는 콘텐츠 슬라이드에 항상 유지.
