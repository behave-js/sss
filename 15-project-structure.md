# 프로젝트 구조와 명명법

이 문서는 Scenario-Semantic Synthesis(SSS) 프로젝트의 정본·작업 뷰(Working View)·근거(Evidence)를 찾고 유지하기 위한 권장 구조를 설명한다. 디렉터리 구조 자체는 방법론의 온톨로지(ontology)가 아니다.

## 권장 디렉터리

```text
project-sss/
├─ README.md
├─ notions/
│  ├─ 00-notion-overview.md
│  ├─ <notion-stream-id>.md
│  └─ alignment-map.md
├─ tensions/
│  ├─ 00-tension-ledger.md
│  ├─ tension-journal.md
│  ├─ tension-closed.md
│  └─ <tension-record-id>.md
├─ actors/
│  ├─ 00-actors.md
│  └─ <actor-id>.md
├─ props/
│  ├─ 00-props.md
│  └─ <prop-id>.md
├─ settings/
├─ locations/
├─ subjects/
│  ├─ 00-subjects.md
│  └─ <subject-id>.md
├─ scenes/
│  ├─ 00-scene-catalog.md
│  ├─ <scene-id>.md
│  └─ 99-evidence-coverage.md
├─ causalities/
│  ├─ 00-causality-overview.md
│  └─ <edge-id>.md
├─ closure-units/
│  ├─ 00-closure-unit-overview.md
│  └─ <closure-id>.md
├─ staging/
│  ├─ 00-staging-index.md
│  └─ <staging-id>.md
├─ backstage/
│  ├─ 00-backstage-index.md
│  └─ <backstage-id>.md
├─ probes/
│  ├─ 00-probe-index.md
│  └─ <probe-id>.md
├─ productions/
│  ├─ 00-production-index.md
│  └─ <production-id>.md
├─ reflections/
│  ├─ 00-reflection-index.md
│  └─ <reflection-id>.md
├─ orchestrations/
│  ├─ 00-orchestration-index.md
│  └─ <orchestration-id>.md
├─ profiles/
│  └─ quality-concerns/
│     ├─ 00-inquiry-library.md
│     ├─ lenses/
│     │  ├─ software-quality.md
│     │  └─ dramatic-narrative-quality.md
│     └─ <quality-orchestration-id>.md
├─ evidence/
│  ├─ 00-evidence-ledger.md
│  ├─ unknowns.md
│  └─ conflicts.md
└─ diagrams/
```

Scenario-Semantic Synthesis(SSS)의 `Scenario`는 기본 디렉터리나 정본 종류가 아니다. 특정 프로젝트가 실제 각본·사용 사례·운영 시나리오를 자료로 다룬다면 `scenarios/`를 둘 수 있지만, 모든 액터(Actor)·씬(Scene)·시퀀스(Sequence)·완결(Closure)을 다시 감싸는 필수 상위 폴더로 만들지 않는다.

작은 프로젝트는 파일을 합칠 수 있다. 그러나 개념적 구분은 유지한다. 액터(Actor) 목록과 씬(Scene) 목록을 한 표에 넣더라도 둘이 같은 종류라고 취급하지 않는다.

## 안정 ID

표시 이름은 바뀔 수 있으므로 안정 ID를 둔다.

- 액터(Actor): `ACT-<slug>`
- 소품(Prop): `PRP-<slug>`
- 세팅(Setting): `SET-<slug>`
- 장소(Location): `LOC-<slug>`
- 주제(Subject): `SUB-<slug>`
- 씬(Scene): `SCN-###`
- 인과성(Causality) 엣지(edge): `EDG-###`
- 완결 단위(Closure Unit): `CLU-###`
- 근거(Evidence) claim: `EVD-###`
- 관념 스트림(Notion stream): `NTN-<perspective>-<slug>`
- 텐션(Tension) 기록(record): `TEN-<observer>-###`
- 스테이징(Staging) view: `STG-<perspective>-###`
- 백스테이지(Backstage) inquiry: `BKS-<perspective>-###`
- 시맨틱 프로브(Semantic Probe): `PRB-<question>-###`
- 프로덕션(Production): `PRD-<scope>-###`
- 리플렉션(Reflection): `RFL-<scope>-###`
- 오케스트레이션(Orchestration): `ORC-<scope>-###`
- 품질 관심사 오케스트레이션(Quality Concern Orchestration): `QCO-<scope>-###`

번호는 순서를 암시할 수 있으므로 씬(Scene)의 실제 시간 순서가 자주 바뀌는 프로젝트에서는 UUID 또는 의미 slug를 사용해도 된다. 한 번 외부에서 참조한 ID는 가능한 재사용하지 않는다.

## 권장 메타데이터

Markdown 전면부를 사용할 경우 다음 정도면 충분하다.

```yaml
---
id: SCN-011
title: 설계 검토
status: draft
evidence_status: mixed
target_edition: "1.2.0"
actors: [ACT-participant, ACT-validator]
props: [PRP-design]
subjects: [SUB-design, SUB-risk]
notions: [NTN-planner-control, NTN-user-agency]
tensions: [TEN-tester-004]
closures: [CLU-design-session]
incoming_edge: [EDG-021]
outgoing_edge: [EDG-022, EDG-023]
---
```

메타데이터는 본문을 대신하지 않는다. 자동 검사와 색인을 위한 최소 관계만 둔다.

## 정본 원칙

비환원적 종합(Non-reductive Synthesis)은 하나의 종합 문서를 새 정본으로 만드는 원칙이 아니다. 아래 정본의 서로 다른 책임과 기록 맥락을 보존한 채 관계를 추적하는 원칙이다.

- 액터(Actor)의 전역 정체성은 액터(Actor) 문서가 정본이다.
- 소품(Prop)의 전체 상태 호는 소품(Prop) 문서가 정본이다.
- 씬(Scene)의 목적·권한·비트(Beat)는 씬(Scene) 문서가 정본이다.
- 구체적인 씬(Scene) 간 전달 평가는 인과성(Causality) 문서가 정본이다.
- 시작과 종료의 생애는 완결(Closure) 문서가 정본이다.
- 반복 주제(Subject)와 지식의 탐색 경로는 주제(Subject) 문서가 정본이다.
- 대상에서 확인한 사실과 미확인은 근거(Evidence) ledger가 정본이다.
- 주체별 의미 방향과 변형은 관념 스트림(Notion stream) 문서가 정본이다.
- 스트림(stream) 사이의 정렬·긴장·단절은 관념(Notion) alignment map이 정본이다.
- 텐션(Tension)의 최초 감지·궤적·선택적 해석은 텐션(Tension) 기록(record)이 정본이다.
- 텐션(Tension) ledger는 기록(record)의 상태와 관련 요소를 찾는 색인이며 이슈(Issue) backlog를 대신하지 않는다.
- 텐션 저널(Tension Journal)은 여러 구성·작업·판본을 가로질러 적극 관찰할 텐션(Tension)의 궤적과 관계를 보존하는 작업 뷰(Working View)다.
- 텐션 종결 기록(Tension Closed)은 현재 적극 관찰에서 내려놓은 기록(record)의 종결 이유(Closing Reason)·잔여(Residual)·재개방 신호(Reopen Signal)를 보존하는 작업 뷰(Working View)다. Completed나 Archive가 아니다.
- 스테이징(Staging) 문서는 관점별 재구성과 리허설의 작업 뷰(Working View)다. 새 의미는 해당 액터(Actor)·씬(Scene)·엣지(edge)·완결(Closure)·관념(Notion) 등의 정본으로 환류하며 스테이징(Staging) 자체를 새 정본으로 만들지 않는다.
- 백스테이지(Backstage) 문서는 보이지 않는 조건과 작동을 탐색하는 작업 뷰(Working View)다. 발견된 액터(Actor)·소품(Prop)·세팅(Setting)·장소(Location)·비트(Beat)·엣지(edge)·완결(Closure)·관념(Notion)은 각 정본으로 환류하며 질문 목록 자체를 정본으로 만들지 않는다.
- 시맨틱 프로브(Semantic Probe) 문서는 질문을 다른 표현·관찰·실험에 통과시킨 작업 뷰(Working View)다. 프로브(Probe) 결과 자체가 정본은 아니며 새 발견과 근거만 관련 정본으로 환류한다.
- 프로덕션(Production) 문서는 현재 범위(Scope)의 결정·실현·결과·EIFS 평가(assessment)를 보존하는 작업 뷰(Working View)다. 자주 참조되더라도 관련 SSS 정본을 대체하지 않는다.
- 리플렉션(Reflection) 문서는 특정 범위(Scope)·관찰 구간(Observation Window)에서 실제 결과를 다시 읽고 환류하는 작업 뷰(Working View)다. 의미 차이(Semantic Delta)와 해석은 관련 정본·근거(Evidence)·텐션(Tension)·프로덕션(Production) 기록을 대체하지 않는다.
- 오케스트레이션(Orchestration) 문서는 현재 질문의 기능(Function)·배정(Assignment)·작업 패킷(Work Packet)·권한(Authority)·의존·인계(Handoff)·통합·동반 변경(Co-change)을 조율하는 작업 뷰(Working View)다. 조직도, 워크플로(Workflow) 정본 또는 의미 결정 권위를 대신하지 않는다.
- 품질 관심사 프로필(Quality Concern Profile)은 선택적 어휘(Vocabulary)와 작업 뷰(Working View)다. 분야 비종속 질문(Domain-uncommitted Question)이나 소프트웨어·극작 등 참조 렌즈(Reference Lens)의 관심사(Concern)를 SSS 코어(Core)·관념(Notion)·요구사항(Requirement)·측정값(Measure)으로 자동 승격하거나 직책별 독점 책임으로 만들지 않는다.

다른 문서에서는 핵심 의미만 요약하고 정본으로 링크한다. 같은 상세 설명을 여러 곳에 복사하지 않는다.

## 규모별 적용

### 최소형

- README
- 통합 사전 1개
- 씬(Scene) catalog와 씬(Scene) 문서
- 주요 엣지(edge) 표
- 핵심 완결(Closure) 표
- 주요 주체별 관념 스트림(Notion stream)과 정렬/비지배 메모
- 텐션(Tension)을 기록할 통로. 실제 감지가 없으면 기록(record) 수는 0일 수 있음

### 표준형

- 요소별 Bible
- 주제 라이브러리(Subject Library)
- 엣지(edge)/완결(Closure) 상세 문서
- 근거 커버리지와 미확인 목록
- 링크 자동 검사
- 관념 라이브러리(Notion Library)와 alignment map
- 텐션(Tension) ledger와 선택적 상세 기록(record)
- 장기 추적이 필요할 때 텐션 저널(Tension Journal)과 텐션 종결 기록(Tension Closed)
- 필요할 때 관점별 스테이징(Staging) 노트(note)와 정본 환류 목록
- 필요할 때 백스테이지(Backstage) 탐색 노트(note)와 프로덕션(Production)/리플렉션(Reflection) 인계(Handoff)
- 반복 참조하거나 근거·반례로 보존할 가치가 있는 시맨틱 프로브(Semantic Probe) 기록
- 실제 결정을 내리고 결과를 만든 프로덕션(Production) 기록과 평가 시점·적용 조건별 EIFS 평가(assessment)
- 반복 참조하거나 환류 상태를 추적할 가치가 있는 리플렉션(Reflection) 기록
- 여러 기능(Function)·배정(Assignment)·Packet·근거(Evidence) 경로를 나누고 통합할 필요가 있는 오케스트레이션(Orchestration) 기록
- 품질 질문을 여러 위치(Position)·관념 스트림(Notion stream)·참조 렌즈(Reference Lens)·기능 배정(Function Assignment)에서 조율할 때 선택적인 품질 관심사 프로필(Quality Concern Profile)과 QCO 기록

### 대형/장기형

- 안정 ID와 front matter
- 근거 ledger
- 관계 데이터 자동 생성
- 부분 그래프와 관점별 뷰
- 변경 영향 검사와 CI
- 대상 판본 간 차이 문서
- 선언·구성·작동·추론·수용·환류 관념(Notion)의 판본별 비교
- 판본·관점별 텐션(Tension) 궤적과 이슈(Issue) 전환 여부. 미해석·보류 기록(record)도 유지
