# Skill Trends Changelog

Daily Skill Trends 보고서와 소개 인덱스의 변경 기록입니다. 보고서의 날짜는 Asia/Seoul 기준입니다.

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
