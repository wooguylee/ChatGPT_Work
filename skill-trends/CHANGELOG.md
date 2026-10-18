# Skill Trends Changelog

Daily Skill Trends 보고서와 소개 인덱스의 변경 기록입니다. 보고서의 날짜는 Asia/Seoul 기준입니다.

## 2026-10-18

- [오늘의 보고서](2026/10/2026-10-18.md)에 신규 소개 Skill 5개를 기록: wiki-qa, wiki-onboarding, pydantic-models-py, gws-workflow-standup-report, recipe-find-free-time.
- Top Pick: wiki-qa의 코드 근거 기반 질문 답변. Codex 즉시 활용 후보: pydantic-models-py의 기존 API 계약 검토.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치함을 확인했다. 그 이후 introduced-skills.md에 5개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 260개에서 265개가 되었다.
- 기존 날짜별 보고서 44개의 소개 260개를 전체 인덱스와 대조했으며 누락·최초 소개일 불일치·보고서에 없는 항목은 없었다. 기존 항목·날짜·재등장 규칙을 보존했다.
- 보고서의 GitHub·공식 API 출처 URL 27개를 재조회해 접근을 확인했고 Pydantic·FastAPI·Google Calendar/Tasks·GitHub Copilot CLI·Git 공식 문서 12개도 확인했다. 저장소 전체 지표와 개별 Skill 인기도·출시일·성능을 구분했다.
- wiki-qa의 실제 소스·인용 범위와 wiki-onboarding의 네 독자별 가이드를 설명했다. 온보딩 기본 분량 2,600~5,300줄·최소 다이어그램 합계 16개와 코드에서 확인할 수 없는 비용·담당자·SLA·로드맵의 추정 위험을 명시했다.
- 두 wiki 스킬의 현재 checkout과 기본 브랜치 확인 차이, 개별 Skill 1.0.0·plugin manifest 2.0.0·marketplace 1.0.0의 표기 차이를 확인했다.
- pydantic-models-py의 생략과 null, exclude_unset과 exclude_none, 입력·출력 alias, v2.11+ populate_by_name 권고 변경을 공식 문서와 대조했다. Cosmos DB 전용 doc_type과 일반 모델 계약을 구분했다.
- standup의 primary/@default 고정, 일정 25개·작업 20개 단일 페이지, 오늘 작업 필터 부재·할당 작업 기본 제외, 조회 실패의 빈 배열 대체, 시간대 캐시·fallback, Model Armor 미적용을 확인했다.
- free-time 레시피의 busy 구간 조회와 실제 이벤트 생성 단계를 구분했다. 캘린더별 오류·시간대·건수 한도와 원문의 과거 날짜·오프셋 없는 생성 예시를 현행 구현 및 Calendar API 요건과 대조했다.
- fastapi-router-py는 템플릿의 소유권 검사 주석·누락과 문서 표현의 차이 때문에 신규 소개에서 제외했다. 특정 운영 서비스의 취약점을 발견·재현했다고 표현하지 않았다.
- 설치·코드 생성/실행·테스트·문서 렌더링·인증·실제 Workspace 조회·회의 예약·배포는 수행하지 않았다. 과거 날짜 보고서는 새로 작성하지 않았고 skill-trends 밖의 파일은 수정하지 않았다.
- 검증된 게시 커밋: [보고서 dabf9f3](https://github.com/wooguylee/ChatGPT_Work/commit/dabf9f33d90172bdd37e8c4f531d49168436852b), [인덱스 62c1f49](https://github.com/wooguylee/ChatGPT_Work/commit/62c1f496361ca260aaa32d5d7d6ebdceb353f8b0).

## 2026-10-17

- [오늘의 보고서](2026/10/2026-10-17.md)에 신규 소개 Skill 6개를 기록: gha-security-review, gws-workflow-meeting-prep, gws-gmail-read, entry-point-analyzer, spec-to-code-compliance, constant-time-analysis.
- Top Pick: spec-to-code-compliance의 작은 명세부터 근거를 연결하는 검토. Codex 즉시 활용 후보: gha-security-review의 소스 검토 초안.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치함을 확인했다. 그 이후 introduced-skills.md에 6개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 254개에서 260개가 되었다.
- 기존 날짜별 보고서 43개의 소개 254개를 전체 인덱스와 대조했으며 누락·최초 소개일 불일치·보고서에 없는 항목은 없었다. 기존 항목·날짜·재등장 규칙을 보존했다.
- 보고서의 GitHub·공식 API 출처 URL 33개를 재조회해 접근을 확인했다. Google Calendar·Gmail, GitHub workflow·gh api 및 BearSSL의 1차 문서도 확인했다. 저장소 지표·개별 인기도·출시일·분석 성능을 구분했다.
- gha-security-review의 외부 공격자 범위와 Safe Patterns의 한계를 설명했다. with/env 전달 이후의 consumer, workflow_run·artifact 경계, 자체 action 태그의 불변성 한계와 현행 public-preview dependency lockfile을 공식 문서와 대조했다.
- meeting-prep의 실제 캘린더 ID 사용, 종료 시각 기준 timeMin·maxResults=1로 진행 중·종일 일정이 나올 수 있는 점, 연결 문서 미조회와 Model Armor 미적용을 확인했다.
- gmail-read의 body_text/body_html과 원문 jq .body 예시 차이, HTML-only의 snippet 대체 가능성, 별도 첨부 본문 미조회, JSON 필드·RFC Message-ID와 Gmail ID 차이를 확인했다. dry-run 샘플을 실제 메일 검증으로 보지 않고 terminal 문자 제거와 콘텐츠 보안 검사를 구분했다.
- entry-point-analyzer의 실제 호출자 검사와 읽기 전용 함수 제외 범위를 명시했다. spec-to-code-compliance의 Workflow 의존·최대 30개 검사·미검사/미검증/읽기 실패 표시·DOCX/Notion export 제한을 확인했다.
- constant-time-analysis의 --warnings와 데이터 흐름·설정별 한계를 설명했다. SKILL의 비실행 설명과 달리 JavaScript 분석기가 Node로 대상 파일을 실행할 수 있음을 구현에서 확인했다.
- claude-settings-audit는 읽기 전용 목표와 넓은 gh api 허용 규칙의 차이 때문에 제외했다. insecure-defaults는 현행 command/workflow 플러그인으로 남아 있지만 SKILL.md가 없어 오늘 소개에서 제외했으며 폐기를 주장하지 않았다.
- 설치·인증·실제 Workspace 조회·CI·Slither·spec-compliance workflow·constant-time 분석기는 실행하지 않았다. 과거 날짜 보고서는 새로 작성하지 않았고 skill-trends 밖의 파일은 수정하지 않았다.
- 검증된 게시 커밋: [보고서 6fb54d3](https://github.com/wooguylee/ChatGPT_Work/commit/6fb54d3de7e1f8433fbdfdae4fce5280d80af122), [인덱스 b093627](https://github.com/wooguylee/ChatGPT_Work/commit/b093627c68bebfee7828a1f73536df8959cd4b24).

## 2026-10-16

- [오늘의 보고서](2026/10/2026-10-16.md)에 신규 소개 공식 Skill 6개를 기록: provider-docs, provider-test-patterns, provider-ephemeral-resources, azure-kusto, azure-resource-visualizer, azure-resource-lookup.
- Top Pick: azure-resource-lookup의 범위가 명확한 인벤토리. Codex 즉시 활용 후보: provider-docs의 코드·문서 대조 초안.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치함을 확인했다. 이후 introduced-skills.md에 6개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 248개에서 254개가 되었다.
- 기존 날짜별 보고서 42개의 소개 248개를 전체 인덱스와 대조했으며 누락·최초 소개일 불일치·보고서에 없는 항목은 없었다. 기존 항목·날짜·재등장 규칙을 보존했다.
- provider-docs 원문의 docs/*.md.tmpl 제안과 현재 tfplugindocs의 templates/ 입력·docs/ 출력 기본값 차이를 확인했다. 생성기가 Provider를 빌드하고 Terraform을 실행·다운로드할 수 있는 점과 --providers-schema 경로를 구분했다.
- provider-test-patterns의 실제 자원 생성·삭제·비용, RootModule만 순회하는 예제 helper, 접두어 필터·개별 삭제 오류를 로그로만 남기는 sweeper 예제를 확인했다. 종료 코드만으로 정리 완료를 판단하지 않도록 설명했다.
- provider-ephemeral-resources의 plan/state 비저장 범위, Renew의 새 결과값 반환 불가, write-only의 Terraform 1.11+ 조건을 제품 문서와 대조했다. echoprovider는 값을 일반 state로 복사하므로 더미·폐기 가능한 테스트 값과 산출물 관리가 필요함을 강조했다.
- Azure Kusto의 ARM·데이터 권한 차이, RestrictedViewAccess·현재 도구 인자 조건, Resource Graph의 부분 권한·인덱싱 지연·KQL 부분집합을 확인했다. --first 건수 제한과 --subscriptions 범위 선택을 구분했다.
- Resource Visualizer의 구성 기반 문서화와 실제 트래픽 관측을 구분했다. 비밀값을 출력에서 가리는 지침과 처음부터 불필요한 비밀값 조회를 피하는 권고를 구분하고 문서 생성·공유 범위를 설명했다.
- azure-rbac는 README 이름과 현행 SKILL.md 확보 결과가 달라 선정에서 제외했으며 폐기됐다고 단정하지 않았다. 플러그인 Node 22+·MCP @latest·기본 read-only 옵션 부재·telemetry 및 Foundry README와 실제 MCP 설정의 차이를 명시했다.
- GitHub 저장소 전체 지표와 개별 스킬 인기도를 구분했다. 이번에는 여섯 항목의 현재 개별 설치 수·외부 감사 결과를 확인하지 않았으며 급상승·신규 출시·안전 인증을 주장하지 않았다.
- 스킬 설치·빌드·테스트·sweeper·Terraform plan/apply·자격증명 발급·Azure 실시간 조회·Mermaid 렌더링은 수행하지 않았다. 과거 날짜 보고서는 새로 작성하지 않았고 skill-trends 밖의 저장소 파일을 수정하지 않았다.

## 2026-10-15

- [오늘의 보고서](2026/10/2026-10-15.md)에 신규 소개 Skill 6개를 기록: gws-gmail-triage, gws-calendar-agenda, gws-sheets-read, cost-optimization, azure-diagnostics, azure-compliance.
- Top Pick: cost-optimization의 보고서 전용 활용. Codex 즉시 활용 후보: azure-diagnostics의 제공 자료 전용 분석.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치함을 확인했다. 이후 introduced-skills.md에 6개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 242개에서 248개가 되었다.
- 기존 날짜별 보고서 41개의 소개 242개를 전체 인덱스와 대조했으며 누락·최초 소개일 불일치·보고서에 없는 항목은 없었다. 기존 항목·날짜·재등장 규칙을 보존했다.
- Google Workspace 조직 소유와 Google 공식 제품 지원을 구분했다. 메일의 기본 is:unread 범위·단일 페이지·메타데이터 오류 생략·labelIds 출력, Calendar의 시간대·이름 부분 일치·현재부터 7일인 --week·페이지 제한·오류 생략을 구현과 대조했다.
- Sheets values.get의 표시 값 기본값, scope 목록과 실제 최소 권한의 차이, 셀 범위가 OAuth 권한 범위를 제한하지 않는 점, helper의 sanitize=None을 명시했다. 읽기 전용 지침을 보안 격리나 외부 데이터 전송 차단으로 표현하지 않았다.
- 현행 cost-optimization의 별도 azure-cost 플러그인 구조, 약정·리사이징 절감액 이중 계산 방지, ARM MCP preview 호스트 조건을 확인했다. 과거 azure-cost 이름·지표를 현행 개별 Skill에 옮기지 않았다.
- azure-diagnostics의 기본 관찰과 privileged debug pod·외부 이미지 실행을 구분했다. Snyk 요약 Pass와 2026-05-19 Warn 상세의 불일치를 설명하고 경고가 해결됐다고 단정하지 않았다.
- azure-compliance의 시크릿 get이 실제 비밀값을 반환할 수 있음을 공식 제품 문서와 대조했다. 만료 점검에는 메타데이터 전용 조회와 별도 변경 승인을 권했다.
- Google 두 후보의 Snyk Warn 상세는 미확인이다. 페이지별 캐시·관측 시점·저장소 전체 지표를 구분했다. Node 버전 안내 불일치, MCP @latest 실행, telemetry도 설명했다.
- 스킬 설치·인증·실제 Workspace 데이터 조회·Azure 비용 조회·azqr·Key Vault·debug pod 실행 시험은 수행하지 않았다. 과거 날짜 보고서는 새로 작성하지 않았고 skill-trends 밖의 저장소 파일을 수정하지 않았다.

## 2026-10-14

- [오늘의 보고서](2026/10/2026-10-14.md)에 신규 소개 공식 Skill 5개를 기록: codeql, sarif-parsing, document-api-endpoint, gh-review-requests, pr-writer.
- Top Pick: sarif-parsing. Codex 즉시 활용 후보: pr-writer의 초안 전용 사용. gh-review-requests·pr-writer의 Snyk Warn 상세는 미확인으로 명시하고 무조건적인 실행·게시 추천으로 표현하지 않았다.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치함을 확인했다. 이후 introduced-skills.md에 5개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 237개에서 242개가 되었다.
- 기존 날짜별 보고서 40개의 소개 237개를 전체 인덱스와 대조했으며 누락·최초 소개일 불일치·보고서에 없는 항목은 없었다. 기존 항목·날짜·재등장 규칙을 보존했다.
- CodeQL DB 추출 품질·실제 쿼리 수 검증, 데이터 확장·run-all 범위와 빌드·설치·정리·덮어쓰기의 실행 경계를 설명했다.
- SARIF level과 security-severity를 구분하고, ruleConfigurationOverrides 미처리·도구 이름 없는 중복 키·경로 변화에 따른 비교 한계를 구현과 대조했다.
- Sentry API의 null·필드 부재와 경로 단위 레거시 마이그레이션, PUBLIC 승격·실제 인증 조회의 별도 권한을 설명했다.
- gh-review-requests의 unread 알림 범위, --org가 저장소 조직 필터가 아니라는 점, API 오류를 빈 결과로 처리하는 한계를 확인했다. 검증되지 않은 페이지네이션 결함은 주장하지 않았다.
- pr-writer의 PR 생성·PATCH·후속 갱신 지시와 초안 전용 요청을 구분했다. skills.sh의 재조회 수치 차이·캐시·감사 날짜·저장소 전체 지표를 구분했고 감사 대상과 현행 revision의 일치를 추정하지 않았다.
- 설치·CodeQL 빌드·스캔·SARIF helper 실행·API 문서 생성·실제 토큰 조회·리뷰 조회 스크립트 실행·PR 게시 시험은 수행하지 않았다. 과거 날짜 보고서는 새로 작성하지 않았고 skill-trends 밖의 저장소 파일을 수정하지 않았다.

## 2026-10-13

- [오늘의 보고서](2026/10/2026-10-13.md)에 신규 소개 공식 Skill 5개를 기록: django-access-review, django-perf-review, prompt-optimizer, code-simplifier, skill-scanner.
- Top Pick: prompt-optimizer. Codex 즉시 활용 후보: code-simplifier. skill-scanner는 심볼릭 링크 선검토·비밀정보 없는 OS 격리·출력 가림을 전제로 한 조건부 후보다.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치함을 확인했다. 이후 introduced-skills.md에 5개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 232개에서 237개가 되었다.
- 기존 날짜별 보고서 39개의 소개 232개를 전체 인덱스와 대조했으며 누락·최초 소개일 불일치는 없었다. 기존 항목·날짜·재등장 규칙을 보존했다.
- Django 객체 권한의 목록·생성 경계와 성능 검토의 데이터 규모·호출 빈도 근거를 설명했다. 벌크 쓰기·삭제의 save/delete 오버라이드와 시그널 차이는 공식 Django 문서로 대조했다.
- prompt-optimizer의 평가·홀드아웃과 별도 실행기 부재, code-simplifier의 Anthropic 원본 출처·개별 Skill과 모델 지정 에이전트의 차이를 확인했다.
- skill-scanner 구현이 파일을 읽은 뒤 심볼릭 링크를 검사하며 탐지 행 앞 200자를 evidence에 그대로 넣는 점을 확인했다. 패턴 검사의 파일 범위·도메인 허용목록 한계·결과 비밀값 가림을 명시했다. 자체 실행 재현 결과로 표현하지 않았다.
- gha-security-review는 신규 소개에서 제외했다. 날짜가 있는 감사 상세는 9월 30일 Gen Fail·Socket Warn, 9월 29일 Snyk Pass이며 오래된 비-www 캐시와 다르다. 교육용 공격 예제라는 맥락과 현재 revision 일치 미확인을 구분했다.
- 제외한 Skill도 포함하는 전체 Sentry plugin 설치는 오늘의 추천 경로에서 빼고 다섯 항목의 개별 설치를 우선하도록 검토·수정했다. 감사 배지를 현재 revision 안전 보증으로 확대하지 않았다.
- 설치·Django 실행·부하 측정·프롬프트 평가·코드 수정·스캐너 실행·CI 시험은 수행하지 않았다. 과거 날짜 보고서는 새로 작성하지 않았고 skill-trends 밖의 저장소 파일을 수정하지 않았다.

## 2026-10-12

- [오늘의 보고서](2026/10/2026-10-12.md)에 신규 소개 공식 Skill 5개를 기록: semgrep-rule-creator, semgrep-rule-variant-creator, algorithmic-art, brand-guidelines, slack-gif-creator.
- Top Pick: semgrep-rule-variant-creator. Codex 즉시 활용 후보: brand-guidelines(Anthropic 관련 자료 또는 자체 브랜드 규칙 작성 참고용).
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치함을 확인했다. 이후 introduced-skills.md에 5개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 227개에서 232개가 되었다.
- 기존 날짜별 보고서 38개의 소개 227개를 전체 인덱스와 대조했으며 누락·최초 소개일 불일치는 없었다. 기존 항목·날짜·재등장 규칙을 보존했다.
- Semgrep 규칙 신규 제작과 언어별 이식을 구분했다. 실제 채점 JSON·안전 사례·버전 고정·동적 workflow 호환성과 테스트 통과의 범위를 명시했다.
- constant-time-analysis는 신규 소개에서 제외했다. 정적 분석 설명과 달리 Node 바이트코드·PHP OPcache fallback 경로가 대상 파일을 subprocess로 실행하는 구현을 확인했다. 별도로 확인한 Trust Hub Fail의 상세는 접근 오류로 미확인이고 이 동작을 Fail 원인으로 추정하지 않았다.
- algorithmic-art 템플릿의 CDN·Google Fonts 의존성, brand-guidelines의 Anthropic 전용 범위·한글 글꼴 검증, GIF validator의 픽셀 크기 중심 판정과 RGB 변환·프레임 감축 시 재생시간 변화를 설명했다.
- creator의 9월 17일 Snyk Warn과 변경 가능한 원격 문서 의존성을 확인했다. skills.sh 캐시 차이·관측 시점·저장소 전체 지표를 구분했다. 감사 배지를 현재 revision 안전 보증으로 확대하지 않았다.
- 설치·규칙 실행·암호 코드 실행·시각 자료 생성·Slack 업로드 시험은 수행하지 않았다. 과거 날짜 보고서는 새로 작성하지 않았고 skill-trends 밖의 저장소 파일을 수정하지 않았다.

## 2026-10-11

- [오늘의 보고서](2026/10/2026-10-11.md)에 신규 소개 공식 Skill 6개를 기록: modern-python, supply-chain-risk-auditor, goal-prompt, mutation-testing, fp-check, post-patch-validation.
- Top Pick: post-patch-validation(격리된 환경·허가된 검사·사람 검토 조건). Codex 즉시 활용 후보: goal-prompt.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치함을 확인했다. 이후 introduced-skills.md에 6개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 221개에서 227개가 되었다.
- 기존 날짜별 보고서 37개의 소개 221개를 전체 인덱스와 대조했으며 누락·최초 소개일 불일치는 없었다. 기존 항목·날짜·재등장 규칙을 보존했다.
- 공식 여섯 SKILL.md·plugin README·marketplace 버전·관련 구현을 확인했다. modern-python의 PATH hook 영향, 동봉 참고문서와 현행 uv script lock 지원의 차이, pytest 9.0 설정 문법 조건을 명시했다.
- supply-chain-risk-auditor의 지원 lockfile·직접/전이 의존성 범위·외부 API 전송·평가 불가 상태를 설명했다. goal-prompt의 formatter 기본 길이 제한과 영어 종료 조건 정규식을 실제 호스트 보장과 구분했다.
- mutation survivor와 실제 버그, fp-check의 이진 게이트와 자료 부족, post-patch-validation의 증거 완결성과 안전 판정을 구분했다. 패치 검사는 호출자 권한으로 실행되므로 OS 격리·명시적 실행 권한·사람 검토를 강조했다.
- post-patch-validation의 Socket Warn 상세는 접근 실패로 미확인이다. skills.sh 캐시·관측 시점·저장소 전체 지표를 구분했고 급상승·출시일·실행 성능을 추정하지 않았다.
- devcontainer-setup은 bypassPermissions 자동 설정·토큰 전달·확장 network capability를 확인해 오늘의 여섯 소개에서 제외했다.
- 설치·감사·mutation test·취약점 재현·패치 검증·goal mode 실행을 했다고 주장하지 않았다. 과거 날짜 보고서는 새로 작성하지 않았고 skill-trends 밖의 저장소 파일을 수정하지 않았다.

## 2026-10-10

- [오늘의 보고서](2026/10/2026-10-10.md)에 신규 소개 공식 Skill 6개를 기록: variant-analysis, audit-context-building, semgrep, internal-comms, theme-factory, canvas-design.
- Top Pick: variant-analysis. Codex 즉시 활용 후보: audit-context-building.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치함을 확인했다. 이후 introduced-skills.md에 6개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 215개에서 221개가 되었다.
- 기존 날짜별 보고서 36개의 소개 215개를 전체 인덱스와 대조했으며 누락·최초 소개일 불일치는 없었다. 기존 항목·날짜·재등장 규칙을 보존했다.
- Trail of Bits의 세 현행 SKILL.md와 Codex plugin 경로를 확인했다. 코드 전제 정리·취약점 판정·변형 후보 검증을 구분하고, semgrep Skill의 계획 승인과 별도 workflow의 실행 동의 차이를 명시했다.
- semgrep의 실패·부분 실행·대상 없음·크기 제한 제외와 검출 0개를 구분했다. metrics=off가 오프라인 보장은 아니라는 점, Pro 확인 등 준비 단계의 네트워크 가능성, 감사 Warn 상세 접근 실패를 기록했다.
- Anthropic 세 예제의 개별 Apache 2.0 라이선스와 example-skills 묶음 구성을 확인했다. internal-comms의 3P 기간 표현·9월 15일 Snyk 경고, theme-factory의 폰트·대비 검증, canvas-design의 필수 문구 보존·실제 피드백과 원문 가정의 구분을 설명했다.
- skills.sh 관측값·감사 날짜·저장소 전체 지표를 구분했다. 설치·실행·렌더링 시험을 했다고 주장하지 않았으며 신규 소개일을 출시일로 해석하지 않았다.
- 과거 날짜 보고서는 새로 작성하지 않았고 skill-trends 밖의 저장소 파일을 수정하지 않았다.

## 2026-10-09

- [오늘의 보고서](2026/10/2026-10-09.md)에 신규 소개 공식 Skill 6개를 기록: property-based-testing, differential-review, sharp-edges, pdf, docx, pptx.
- Top Pick: property-based-testing. Codex 즉시 활용 후보: sharp-edges.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치함을 확인했다. 이후 introduced-skills.md에 6개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 209개에서 215개가 되었다.
- 기존 날짜별 보고서 35개의 소개 209개를 전체 인덱스와 대조했으며 추가 누락·최초 소개일 불일치는 없었다. 기존 항목·날짜·재등장 규칙을 보존했다.
- Trail of Bits의 현재 공식 Codex plugin 경로와 세 SKILL.md를 확인했다. 속성 테스트의 동어반복·입력 필터링·반례 해석, differential-review의 baseline checkout과 검토 범위, sharp-edges의 정적 검토와 실행 재현 경계를 명시했다.
- insecure-defaults는 폐기된 것이 아니라 commands·workflows plugin으로 바뀌었으며 예전 SKILL.md가 404여서 이번 독립 Skill 선정에서 제외했다.
- Anthropic pdf·docx·pptx의 source-available 제한적 라이선스를 확인하고 Codex 외부 설치를 권장하지 않았다. 공식 Claude document-skills 묶음 경로를 안내했다. PDF의 대소문자 경로 차이, Word 변경 이력·주석, PowerPoint 공유 객체·실제 렌더링 검증을 설명했다.
- skills.sh의 조회별 캐시 차이와 저장소 전체 지표를 구분했다. 접근하지 못한 문서 Skill 감사 Warn 상세는 미확인으로 남겼고 sharp-edges의 9월 감사 결과를 현재 revision 판정으로 확대하지 않았다.
- 신규 소개일과 출시일을 구분했다. 과거 날짜 보고서를 새로 만들지 않았고 skill-trends 밖의 저장소 파일을 수정하지 않았다.

## 2026-10-08

- [오늘의 보고서](2026/10/2026-10-08.md)에 신규 소개 공식 Skill 5개를 기록: hf-cli, terraform-style-guide, terraform-stacks, find-bugs, secret-serialization.
- Top Pick: hf-cli. Codex 즉시 활용 후보: find-bugs.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치하고 Git blob SHA도 일치함을 확인했다. 이후 introduced-skills.md에 5개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 204개에서 209개가 되었다.
- 기존 날짜별 보고서 34개의 소개 204개를 전체 인덱스와 대조했으며 추가 누락·최초 소개일 불일치는 없었다. 기존 항목·날짜·재등장 규칙을 그대로 보존했다.
- hf-cli의 v2.1.1 생성 원문·현행 설치 경로와 Jobs의 과금·취소 경계를 확인했다. huggingface-jobs는 2026-04-11 공식 삭제 커밋을 근거로 별도 신규 추천에서 제외해 5개만 선정했다.
- Terraform 스타일 검토와 자원 주소·provider 변경을 구분했다. Stacks의 일부 deployment-group/auto-approve 예제·요금제 표기가 현재 제품 문서와 다름을 설명하고 로컬 검증·speculative 업로드·실제 배포의 경계를 명시했다.
- find-bugs의 기본 diff에서 미커밋·미추적 파일이 빠질 수 있음을 설명했다. secret-serialization의 JS reference와 현재 SDK develop 구현의 toJSON 동작 차이, Node showHidden 옵션의 예외를 확인했다.
- URL별로 다른 skills.sh 캐시, 개별 Skill 지표와 저장소 전체 지표, Git 변경 이력과 출시일을 구분했다. 접근하지 못한 hf-cli 감사 상세와 secret-serialization 개별 지표는 미확인으로 남겼다.
- 과거 날짜 보고서는 새로 만들지 않았고 skill-trends 밖의 저장소 파일은 수정하지 않았다.

## 2026-10-07

- [오늘의 보고서](2026/10/2026-10-07.md)에 신규 소개 Skill 6개를 기록: react-doctor, upgrade-stripe, terraform-search-import, refactor-module, xlsx, discernment-nudge.
- Top Pick: upgrade-stripe. Codex 즉시 활용 후보: react-doctor.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치하고 Git blob SHA도 일치함을 확인했다. 이후 introduced-skills.md에 6개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 198개에서 204개가 되었다.
- 기존 날짜별 보고서 33개의 소개 198개를 전체 인덱스와 대조했으며 추가 누락은 발견하지 않았다. 기존 항목·최초 소개일·재등장 규칙을 그대로 보존했다.
- React Doctor의 단일 Skill 설치와 프로젝트 통합 설치, 기본 telemetry, 변경분 개수 기반 판정의 한계와 원격 playbook을 구분했다. 접근하지 못한 playbook·일부 감사 상세는 미확인으로 남겼다.
- Stripe의 2026-10-06 갱신 원문과 현재 API 버전 2026-09-30.endive를 대조했다. 지난달 skills.sh 캐시·5월 Snyk Fail을 현행 최신 판정으로 취급하지 않았고, SDK·API·webhook 및 분석·운영 변경의 경계를 설명했다.
- Terraform 검색 helper의 자동 init -upgrade, refactor 예제의 CIDR·AZ 변경과 Git source/version 혼용을 명시했다. xlsx의 개별 제한적 라이선스와 재계산 JSON 검증, discernment-nudge의 생략 조건을 확인했다.
- huggingface-paper-publisher는 create_pr 옵션에도 README를 직접 업로드하는 현행 구현 때문에 이번 추천에서 제외했다. 공개 저장소 지표와 개별 설치 수를 구분하고 캐시 시점·미확인 지표를 명시했다.
- 신규 소개일과 출시일을 구분했다. 과거 날짜 보고서는 새로 만들지 않았고 skill-trends 밖의 저장소 파일은 수정하지 않았다.

## 2026-10-06

- [오늘의 보고서](2026/10/2026-10-06.md)에 신규 소개 Skill 6개를 기록: huggingface-community-evals, huggingface-gradio, huggingface-trackio, nextjs-on-cloudflare, terraform-test, doc-coauthoring.
- Top Pick: huggingface-community-evals. Codex 즉시 활용 후보: huggingface-gradio.
- main에 보고서를 저장한 뒤 전체 원문을 재조회해 작성본과 정확히 일치하고 Git blob SHA도 일치함을 확인했다. 이후 introduced-skills.md에 6개를 추가하고 전체 원문 재조회·정확한 일치·기존 내용 보존을 검증했다. 누적 인덱스는 192개에서 198개가 되었다.
- 기존 날짜별 보고서 32개의 소개 192개를 전체 인덱스와 대조했으며 추가 누락은 발견하지 않았다. 기존 항목·최초 소개일·재등장 규칙을 그대로 보존했다.
- 현재 HF Skill 이름·hf-cli 중심 설치 흐름, 로컬 평가와 외부 provider 추론의 차이, Gradio 공개 공유·파일 업로드, Trackio Space의 기본 공개 및 기존 Space에 대한 private 옵션 한계를 명시했다.
- vinext의 beta 상태와 기존 OpenNext 보존 조건을 확인했다. Terraform Skill의 -filter 설명을 공식 CLI 문서의 파일 선택 의미로 교정하고 확인되지 않은 -no-cleanup 사용 예시는 제외했다. Sandbox 후보는 Skill과 현행 제품 문서의 경로·API 차이 때문에 선정하지 않았다.
- skills.sh 지표·감사 경고와 GitHub 모음 전체 지표를 구분했다. 검색 도구의 크롤링 시점은 실제 수치 갱신 시각과 같지 않음을 명시하고, 현재 이름의 gradio·trackio 개별 지표는 미확인으로 남겼다.
- 신규 소개일과 출시일을 구분했다. 과거 날짜 보고서는 새로 만들지 않았고 skill-trends 밖의 저장소 파일은 수정하지 않았다.

## 2026-10-05

- [오늘의 보고서](2026/10/2026-10-05.md)에 신규 소개 Skill 6개를 기록: huggingface-datasets, huggingface-llm-trainer, wrangler, mcp-builder, next-cache-components-optimizer, jupyter-notebooks.
- Top Pick: next-cache-components-optimizer. Codex 즉시 활용 후보: jupyter-notebooks.
- main에 보고서를 저장한 뒤 전체 원문 재조회 및 작성본의 정확한 일치를 확인했다. 이후 introduced-skills.md에 6개를 추가하고 전체 원문을 재조회해 검증했다. 누적 인덱스는 186개에서 192개가 되었다.
- 기존 날짜별 보고서 31개의 소개 186개를 전체 인덱스와 대조했으며 추가 누락은 발견하지 않았다. 기존 항목·최초 소개일·재등장 규칙을 그대로 보존했다.
- 현재 공식 Skill 원문과 설치 경로를 확인했다. next-best-practices의 독립 Skill 종료 및 Next.js 저장소 이전, openai/skills의 deprecated 안내와 현행 Data Analytics plugin 경로를 반영했다.
- huggingface-model-trainer 경로의 404와 현재 huggingface-llm-trainer 이름을 구분했다. 학습 Skill의 요금제 설명이 현행 Jobs 문서와 다름을 밝혔고 예시 비용·속도 개선 수치를 현재 검증값으로 인용하지 않았다.
- skills.sh 표시값·GitHub 저장소 전체 지표를 구분하고, Next.js optimizer의 2일 전 크롤링 수치와 mcp-builder의 Snyk Warn을 명시했다. 출시일과 신규 소개일을 구분했으며 과거 날짜 보고서는 새로 만들지 않았다.

## 2026-10-04

- [오늘의 보고서](2026/10/2026-10-04.md)에 신규 소개 Skill 6개를 기록: hf-mem, huggingface-local-models, durable-objects, workers-best-practices, triage, to-spec.
- Top Pick: hf-mem. Codex 즉시 활용 후보: to-spec.
- main에 보고서를 저장한 뒤 전체 원문 재조회 및 작성본 일치를 확인했고, 이후 introduced-skills.md에 6개를 추가하고 전체 재조회로 검증했다. 누적 인덱스는 180개에서 186개가 되었다.
- 기존 날짜별 보고서 30개를 조회해 소개 이름을 인덱스와 대조했으며 추가 누락은 발견하지 않았다. 기존 항목·최초 소개일·재등장 규칙을 보존했다.
- 공식 Skill 원문과 공개 지표를 구분했다. hf-mem 개별 설치 수는 미확인으로 남기고, huggingface-local-models의 6일 전 크롤링 수치 및 Snyk Warn, triage의 감사 Warn을 명시했다.
- 신규 소개일과 출시일을 구분했으며 과거 날짜 보고서는 새로 작성하지 않았다.

## 2026-10-03

- [오늘의 보고서](2026/10/2026-10-03.md)에 신규 소개 Skill 6개를 기록: vgpu, shadcn, prisma-orm-setup, remotion-best-practices, vercel-react-native-skills, verification-before-completion.
- Top Pick: vgpu. Codex 즉시 활용 후보: verification-before-completion.
- 보고서를 main에 저장한 뒤 원문 재조회로 확인하고, introduced-skills.md에 오늘의 6개 항목을 추가했다.
- 이미 게시된 [2026-09-25 보고서](2026/09/2026-09-25.md)의 누락 인덱스 6개를 복구: architecture-decision-records, mastra, build-an-agent-skill, xint, workiq-copilot, track-findings. 최초 소개일은 기존 보고서 날짜를 보존했다.
- 과거 날짜 보고서는 새로 작성하지 않았다.
