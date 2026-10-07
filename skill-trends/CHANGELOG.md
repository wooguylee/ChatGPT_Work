# Skill Trends Changelog

Daily Skill Trends 보고서와 소개 인덱스의 변경 기록입니다. 보고서의 날짜는 Asia/Seoul 기준입니다.

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
