# 문서화 스킬셋 관리 인덱스

이 인덱스는 문서화 스킬셋의 관리 목록이며, 본문은 각 `SKILL.md`가 정본이다. "사본"은 원출처와 파일 단위로 바이트가 같은 복사본, "기존 관리"는 이 디렉터리에서 이미 관리하던 항목이다.

- 위치: `skills/paperthin/DEVCOMFORT-DOCS-INDEX.md` (관리 목록을 세트 단위로 두었다).
- 2026-10-20 추가: 전역 `~/.omp/agent/skills/`에서 paperthin 세트(31개 스킬)를 내용 수정 없이 복사.
- 검증: `paperthin/<스킬>/` 31개 디렉터리의 모든 파일 278개가 원본과 sha256 일치, 하위 폴더 6개 구조도 동일.
- 기존 관리 항목의 추가일은 이 디렉터리에 기록이 없어 확인하지 못했다("확인 안 됨").

## 스킬 세트

| 스킬 이름 | 원출처 | 용도(한 줄) | 사본/정본 여부 | 추가일 |
|---|---|---|---|---|
| paperthin (31개 스킬) | 전역 `~/.omp/agent/skills/` | 문서 정돈·검증·의사결정 보조 스킬 묶음(구성은 아래 표). | 사본(원본과 바이트 동일) | 2026-10-20 |
| matt-skills | 이 디렉터리 기존 항목 | matt 스킬 패키지. | 기존 관리 | 확인 안 됨 |
| ecc | 이 디렉터리 기존 항목 | ecc 스킬 패키지. | 기존 관리 | 확인 안 됨 |
| emil-skills | 이 디렉터리 기존 항목 | emil 스킬 패키지. | 기존 관리 | 확인 안 됨 |
| vercel-agent-skills | 이 디렉터리 기존 항목 | vercel agent 스킬 패키지. | 기존 관리 | 확인 안 됨 |
| impeccable | 이 디렉터리 기존 항목 | 프런트엔드 UI 디자인·리디자인·비평·모션·접근성 스킬 패키지. | 기존 관리 | 확인 안 됨 |

## 개별 관리 문서 스킬

| 스킬 이름 | 원출처 | 용도(한 줄) | 사본/정본 여부 | 추가일 |
|---|---|---|---|---|
| maintaining-living-documents | 이 디렉터리 기존 항목 | 문서·명세·ADR·README·런북·프롬프트·스킬 등 살아있는 문서의 생성·수정·보존 규칙. | 기존 관리 | 확인 안 됨 |
| using-excalidraw-mcp | 이 디렉터리 기존 항목 | Excalidraw MCP로 다이어그램과 `.excalidraw` JSON을 만들고 다듬는다. | 기존 관리 | 확인 안 됨 |
| how-to-ask | 이 디렉터리 기존 항목 | 사용자에게 물을 질문을 정리하고 보내는 규칙. | 기존 관리 | 확인 안 됨 |
| notion-note-schema | 이 디렉터리 기존 항목 | Notion 학습 노트의 페이지 종류·섹션 카탈로그·포함/제외 판정 기준. | 기존 관리 | 확인 안 됨 |
| notion-note-writing | 이 디렉터리 기존 항목 | Notion 노트 작성 규칙(서식·문단 밀도·자료 배치·마무리 편집 패스). | 기존 관리 | 확인 안 됨 |
| note-quality-criteria | 이 디렉터리 기존 항목 | 노트 초안을 대조하는 일곱 항목 평가 기준과 검토 보고 형식. | 기존 관리 | 확인 안 됨 |
| learning-document-layout | 이 디렉터리 기존 항목 | 학습·정보 문서의 층과 이름, 페이지 배치 규칙. | 기존 관리 | 확인 안 됨 |
| record-observation | 이 디렉터리 기존 항목 | 관찰 기록을 명세에 맞게 일관되게 쓰는 절차. | 기존 관리 | 확인 안 됨 |
| subagent-handoff-discipline | 이 디렉터리 기존 항목 | 서브에이전트 브리프·핸드오프에 반드시 담을 내용과 작성 순서. | 기존 관리 | 확인 안 됨 |
| managing-external-sources | 이 디렉터리 기존 항목 | `.sourcerc` 기반으로 외부 스킬의 출처·상류 갱신·반영 여부를 관리한다. | 기존 관리 | 확인 안 됨 |

## paperthin 세트 구성

| 스킬 | 원출처 | 용도(한 줄) |
|---|---|---|
| debloat | `~/.agents/skills/debloat` | 군더더기·중복·과잉 수식을 걷어내 밀도를 높인다. |
| dedash | `~/.agents/skills/dedash` | 대시(—)와 대시 대용 표기를 문맥에 맞는 문장부호·표현으로 바꾼다. |
| detool | `~/.agents/skills/detool` | 우연한 도구·모델·CLI·경로 이름을 뜻하는 메커니즘으로 바꾼다. |
| reorder | `~/.agents/skills/reorder` | 흐트러진 순서를 하나의 원칙 아래 재배열한다(문구 수정 없음). |
| shower | `~/.agents/skills/shower` | 맥락 없는 새 세션에 산출물을 읽혀 스스로 서는지 확인한다(진단만). |
| factchk | `~/.agents/skills/factchk` | 직관으로 단정한 사실 주장을 외부 출처로 양방향 검증한다. |
| ssotize | `~/.agents/skills/ssotize` | 흩어진 사실을 하나의 정본으로 모으고 나머지를 참조로 바꾼다(승인 후). |
| sip | `~/.agents/skills/sip` | 산출물·스킬을 만든 직후 스킬로 맛보기 검증한다. |
| re0 | `~/.agents/skills/re0` | 반복 수정으로 흐트러진 산출물을 현재 최선의 v0으로 정돈·동기화한다. |
| re0-git | `~/.agents/skills/re0-git` | 끝난 커밋의 메시지를 손에 익은 로그 문체로 다시 쓴다. |
| re0-loop | `~/.agents/skills/re0-loop` | 빌드→QA→메모→재작업 주기를 반복하며 학습은 남기고 코드는 버린다. |
| re0-memo | `~/.agents/skills/re0-memo` | 작업 주기에서 다음 주기가 배울 교훈·금지 패턴·품질 기준을 뽑는다. |
| re0-merge | `~/.agents/skills/re0-merge` | 외부 기여(PR)를 이 스킬군 기준으로 검토·반영하고 공로를 남긴다. |
| re0-plan | `~/.agents/skills/re0-plan` | 새 반복 주기를 열 때 사례집을 실제 내용으로 먼저 만든다. |
| re0-release | `~/.agents/skills/re0-release` | 출시 점검 목록을 끝까지 밟고 확인 후 태그·배포한다. |
| re0-upgrade | `~/.agents/skills/re0-upgrade` | 설치된 스킬을 현행 카탈로그로 한 번에 맞춘다. |
| re0-work | `~/.agents/skills/re0-work` | 검증된 교훈·계약만 남기고 v0부터 다시 만든다. |
| readchk | `~/.agents/skills/readchk` | 길거나 되돌리기 어려운 지시를 작업 전에 제대로 이해했는지 확인한다. |
| aim | `~/.agents/skills/aim` | 얇은 요청에서 사용자가 하려는 일을 추정해 확인용 제안으로 낸다. |
| catchup | `~/.agents/skills/catchup` | 떠났다 돌아온 사용자에게 현재 상태 기준으로 맥락을 다시 세운다(읽기 전용). |
| nba | `~/.agents/skills/nba` | 지금 가장 값어치 있는 다음 행동 하나를 고른다. |
| modelchk | `~/.agents/skills/modelchk` | 작업에 필요한 모델 등급과 추론 분량을 중립 척도로 산정한다. |
| feynman | `~/.agents/skills/feynman` | 내린 결정을 반대자에게 설명해 이해의 공백을 드러낸다. |
| macrothink | `~/.agents/skills/macrothink` | 현재 방향이 터널 시야인지 새 시선 여러 개로 점검한다(읽기 전용). |
| prism | `~/.agents/skills/prism` | 하나의 주장·계획을 서로 다른 실패 유형의 렌즈 2~5개로 나눠 본다. |
| hate | `~/.agents/skills/hate` | 실제 투자 전에 계획을 실패시키려 공격해 핵심 반론 하나를 뽑는다. |
| mandela | `~/.agents/skills/mandela` | 평가·지표·실험·벤치마크에 정답 누출이 있는지 감사한다(읽기 전용). |
| autobahn | `~/.agents/skills/autobahn` | 안전 경계에 닿는 부분을 대안으로 떼어 내고 나머지를 온전히 실행한다. |
| diagram-design | `~/.local/share/agent-skills/diagram-design/skills/diagram-design` | 아키텍처·흐름·시퀀스·ER·차트 등 다이어그램을 HTML/SVG/PNG로 만든다. |
| visual-plan | `~/.omp/agent/skills/visual-plan` | 글 계획을 다이어그램·파일 맵·주석 코드가 있는 시각 계획으로 바꾼다. |
| change-impact | `~/.agents/skills/change-impact` | 변경 전 영향 범위를 근거로 분석하고 구현 후 실제 diff와 대조한다. |

## 이번에 건드리지 않은 것

- 다른 스킬 패키지(matt-skills, ecc, emil-skills, vercel-agent-skills).
- 저장소 안의 `.agents/skills` 항목은 복사하지 않았다.
