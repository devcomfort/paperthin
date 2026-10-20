# paperthin 스킬 세트

- 출처: 전역 `~/.omp/agent/skills/` (여러 항목은 `~/.agents/skills/`를 가리키는 심볼릭 링크이며, 링크를 따라 실제 디렉터리 내용을 복사했다).
- 추가일: 2026-10-20
- 구성: 31개 스킬 디렉터리. 각 디렉터리의 `SKILL.md`(필요하면 `references/`, `agents/` 등 하위 폴더)를 내용 수정 없이 그대로 두었다.
- 검증: 복사한 31개 디렉터리의 모든 파일 278개에 대해 원본과 sha256이 일치하고, 하위 폴더 구조(6개)도 동일함을 확인했다.
- 관리 목록: 같은 폴더의 `DEVCOMFORT-DOCS-INDEX.md`.

## 구성 스킬

| 스킬 | 한 줄 |
|---|---|
| debloat | 군더더기를 걷어내 밀도를 높인다 |
| dedash | 대시 표기를 문맥에 맞게 바꾼다 |
| detool | 우연한 도구·경로 이름을 메커니즘으로 바꾼다 |
| reorder | 순서만 다시 세운다 |
| shower | 맥락 없는 새 세션으로 콜드 리드 검증 |
| factchk | 사실 주장을 외부 출처로 검증 |
| ssotize | 흩어진 사실을 정본 하나로 모은다 |
| sip | 만든 직후 스킬로 맛보기 검증 |
| re0 | 산출물을 현재 최선 v0으로 정돈 |
| re0-git | 커밋 메시지 재작성 |
| re0-loop | 빌드→QA→메모→재작업 반복 |
| re0-memo | 작업 주기에서 교훈 추출 |
| re0-merge | 외부 기여 검토·반영 |
| re0-plan | 새 주기 사례집 열기 |
| re0-release | 출시 점검·태그 |
| re0-upgrade | 설치 스킬을 현행 카탈로그로 정렬 |
| re0-work | 검증된 교훈만 남기고 v0부터 재구축 |
| readchk | 지시 이해 확인 |
| aim | 얇은 요청에서 의도 추정·제안 |
| catchup | 떠난 사용자에게 맥락 복구 브리핑 |
| nba | 다음 최선 행동 하나 |
| modelchk | 모델 등급·추론 분량 산정 |
| feynman | 결정을 설명해 이해 공백 확인 |
| macrothink | 방향이 터널 시야인지 점검 |
| prism | 여러 실패 유형 렌즈로 분해 |
| hate | 계획을 실패시키려 공격 |
| mandela | 평가·지표 정답 누출 감사 |
| autobahn | 안전 경계 항목 분리 후 나머지 실행 |
| diagram-design | 다이어그램을 HTML/SVG/PNG로 생성 |
| visual-plan | 글 계획을 시각 계획으로 전환 |
| change-impact | 변경 영향 분석·사후 diff 대조 |
