# Scenario-Semantic Synthesis(SSS) 문서 템플릿

템플릿도 본문 문서와 같은 개념 구조로 찾는다. 아래 순서는 작성 의무나 고정 워크플로(Workflow)가 아니다.

Scenario 전용 템플릿은 기본 제공하지 않는다. Scenario는 모든 기록을 감싸는 새 코어 문서가 아니라, 아래 요소들이 구체적 맥락(Context)에서 형성하고 변화시키는 전개를 읽는 방법적 성질이다. 프로젝트에 실제 각본·사용 사례·운영 시나리오가 존재할 때에는 그것을 자료나 소품(Prop), 주제(Subject), 별도 프로젝트 문서로 명시한다.

## 관념(Notion)과 텐션(Tension)

- [관념 스트림(Notion stream)](notion-stream-template.md)
- [관념(Notion) 오버뷰(Overview)](notion-overview-template.md)
- [관념(Notion) 정렬 오버뷰(Alignment Overview)](notion-alignment-overview-template.md)
- [텐션(Tension) 기록(Record)](tension-record-template.md)
- [텐션(Tension) 원장(Ledger)](tension-ledger-template.md)
- [텐션 저널(Tension Journal)](tension-journal-template.md)
- [텐션 종결 기록(Tension Closed)](tension-closed-template.md)

## 구체 요소와 연결

- [액터(Actor)](actor-template.md)
- [소품(Prop)](prop-template.md)
- [세팅(Setting)](setting-template.md)
- [장소(Location)](location-template.md)
- [주제(Subject)](subject-template.md)
- [씬(Scene)](scene-template.md)
- [인과성(Causality) 엣지(edge)](causality-template.md)
- [완결 단위(Closure Unit)](closure-unit-template.md)

액터(Actor)·소품(Prop)·세팅(Setting)·장소(Location)은 배타적 분류가 아니다. 복합 실체나 외부·재사용 구성이 여러 읽기를 가질 때에는 새 유형의 템플릿을 만들기보다, 현재 질문에서 실제로 성립하는 책임을 각 정본에 기록하고 서로 링크한다. 성립 조건(Constitutive Condition)·환경 전제(Environmental Premise)·관념적 선택(Notional Choice)은 필요할 때만 편입 경계를 검토하는 렌즈로 사용한다.

## 오버뷰와 근거(Evidence)

- [씬 카탈로그(Scene Catalog)](scene-catalog-template.md)
- [인과성 오버뷰(Causality Overview)](causality-overview-template.md)
- [완결 오버뷰(Closure Overview)](closure-overview-template.md)
- [근거·커버리지(Evidence Coverage)](evidence-coverage-template.md)

## 탐색·실현·환류·조율

- [스테이징(Staging)](staging-template.md)
- [백스테이지(Backstage)](backstage-template.md)
- [시맨틱 프로브(Semantic Probe)](semantic-probe-template.md)
- [프로덕션(Production)](production-template.md)
- [리플렉션(Reflection)](reflection-template.md)
- [오케스트레이션(Orchestration)](orchestration-template.md)

## 선택적 프로필(Profile)

- [품질 관심사 오케스트레이션(Quality Concern Orchestration)](quality-concern-orchestration-template.md)

템플릿의 모든 절을 기계적으로 채울 필요는 없다. 다만 생략한 절이 해당 대상에 정말 필요 없는지 판단한다. `관찰`, `추론`, `설계 의도`, `미확인` 표기는 프로젝트 전체에서 같은 의미로 사용한다.

관념(Notion) 템플릿은 작업 시작 시 완성하는 양식이 아니다. 초기에는 씨앗과 질문만 기록하고, 구체적인 씬(Scene)·비트(Beat)·인과성(Causality)·완결(Closure)을 충분히 만든 뒤 스트림(stream)과 정렬 관계를 다시 작성한다. 다른 템플릿의 `관련 관념(Notion)`도 승인 도장이나 소유권이 아니라, 실제로 어떤 의미 방향과 만나고 변형되는지를 기록하는 칸이다.

텐션(Tension) 템플릿도 모든 대상에 채우는 의무 항목이 아니다. 필수인 것은 기록 통로이며 실제 기록(record) 수는 0일 수 있다. 텐션(Tension)을 기록할 때에는 감지와 해석·평가·활용을 분리하고, 미해석·보류·무조치를 허용한다.

스테이징(Staging) 템플릿은 현재 SSS의 정본을 대체하지 않는 관점별 작업 뷰(Working View)다. 모든 작업에서 만들 필요는 없으며, 재구성 중 발견한 새 의미는 관련 액터(Actor)·씬(Scene)·엣지(edge)·완결(Closure)·관념(Notion) 등의 정본으로 환류한다.

백스테이지(Backstage) 템플릿도 모든 씬(Scene)에 적용하는 체크리스트가 아니다. 현재 의미와 완결(Closure)을 실제로 바꾸는 숨은 조건을 탐색할 때만 사용하고, 발견된 내용은 관련 SSS 정본과 프로덕션(Production)/리플렉션(Reflection) 인계(Handoff)로 연결한다.

시맨틱 프로브(Semantic Probe) 템플릿은 반복 참조하거나 근거·반례로 보존할 가치가 있을 때 사용한다. 임시 스케치는 문서화하지 않거나 폐기해도 되지만, 프로브(Probe)가 만든 표현·추론과 실제 관찰(Observation), blind spot, 새 결정은 혼동하지 않는다.

프로덕션(Production) 템플릿은 실제 결정과 결과를 만드는 범위(Scope)에서 사용한다. EIFS는 후보(Candidate) 비교가 필요할 때만 작성하되 평가 기준·적용 조건·입력과 근거(Evidence)를 기록하고, 작업 결정(Working Decision)과 산출물(artifact)이 SSS 정본을 대체하지 않도록 한다.

리플렉션(Reflection) 템플릿은 실제 결과·경험·운영을 반복 참조하거나 환류 상태를 보존할 가치가 있을 때 사용한다. 관찰 구간(Observation Window)과 당시 판본을 적고, 관념 스트림(Notion stream) 사이의 차이를 자동으로 텐션(Tension)·결함·변경 명령으로 바꾸지 않는다.

텐션 저널(Tension Journal)은 여러 구성·작업·판본을 가로질러 궤적과 관계를 볼 필요가 있을 때만 사용한다. 현재 적극 관찰을 내려놓을 때에는 텐션 종결 기록(Tension Closed)으로 옮겨 종결 이유(Closing Reason)·잔여(Residual)·재개방 신호(Reopen Signal)를 보존하며, 종결 상태(Closed)를 Completed나 해결 실적으로 취급하지 않는다.

오케스트레이션(Orchestration) 템플릿은 여러 기능(Function)·배정(Assignment)·질문·근거(Evidence) 경로·산출물을 나누고 다시 통합할 필요가 있을 때만 사용한다. Packet 수나 병렬성을 목표로 삼지 않고, 질문·권한(Authority)·인계(Handoff)·통합·동반 변경(Co-change)·중지 조건(Stop Condition)과 재개방 조건을 보존한다.

품질 관심사 오케스트레이션(Quality Concern Orchestration) 템플릿은 이름 붙기 전의 품질 질문을 여러 위치(Position)·관념 스트림(Notion stream)·분야별 참조 렌즈(Reference Lens)에서 함께 판단할 때만 사용한다. 범용 질문이나 분야 분류를 체크리스트·종합 점수표로 만들지 않고, 각 렌즈가 드러내는 것과 가리는 것, 관점(Perspective)·기능 배정(Function Assignment)·책임(Responsibility)·권한(Authority)·근거(Evidence)·트레이드오프(Trade-off)·텐션(Tension)·인계(Handoff)를 분리한다.
