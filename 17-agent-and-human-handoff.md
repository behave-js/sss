# 후속 작업자 실행 규약

이 문서는 다른 사람이나 에이전트가 기존 Scenario-Semantic Synthesis(SSS) 프로젝트를 이어받거나 새 프로젝트를 시작할 때 지켜야 할 실무 순서다.

## 시작할 때

1. 루트 README와 전체 오버뷰를 먼저 읽는다.
   공식 명칭의 Scenario가 새 상위 객체가 아니고 Synthesis가 비환원적 종합(Non-reductive Synthesis)이라는 경계를 먼저 확인한다.
2. [관념(Notion)](00-notion.md)의 짧은 정의와 비지배·비고정 원칙을 읽는다. 큰 관념(Notion)은 확정할 대상이 아니며, 구체 요소를 본 뒤 현재 이름을 붙일 뿐이다.
3. [텐션(Tension)](01-tension.md)의 가치중립·비지시 원칙을 읽고 기존 ledger가 있으면 감지와 해석을 구분해 확인한다.
   저널(Journal)과 종결 상태(Closed)가 있다면 [텐션 가이드북(Tension Guidebook)](13-tension-guidebook.md)에 따라 전체 궤적·종결 이유(Closing Reason)·잔여(Residual)·재개방 신호(Reopen Signal)를 함께 읽는다.
4. 대상 식별자·판본, 범위, 근거 종류를 확인한다.
5. 액터(Actor)/소품(Prop)/세팅(Setting)/장소 바이블(Location Bible)의 명칭을 확인한다.
6. 씬(Scene) catalog, 인과성(Causality) overview, 완결(Closure) overview를 읽는다.
7. 중앙의 미확인·모순·근거 커버리지 문서를 확인한다.
8. 관념(Notion) 본문으로 돌아와 기존 스트림(stream)과 정렬 지도를 읽는다.
9. 이번 질문이 어느 씬(Scene), 주제(Subject), 엣지(edge), 완결(Closure), 관념 스트림(Notion stream), 텐션(Tension) 기록(record)에 걸리는지 적는다.
10. 기존 스테이징(Staging) 노트(note)가 있다면 정본이 아니라 관점별 작업 뷰(Working View)로 읽고, 환류되지 않은 발견과 미확인(Unknown)을 확인한다.
11. 기존 백스테이지(Backstage) 노트(note)가 있다면 숨은 조건·판단·상태 중 정본에 환류되지 않은 것과 프로덕션(Production)/리플렉션(Reflection) 인계(Handoff)를 확인한다.
12. 관련 시맨틱 프로브(Semantic Probe)가 있다면 산출물 자체와 정본에 환류된 발견을 구분하고, 입력 근거 상태와 blind spot을 확인한다.
13. 관련 프로덕션(Production) 기록이 있다면 후보(Candidate), 결정 출처, 결과 판본, EIFS 평가 기준·입력과 평가(assessment) 당시 범위(Scope)를 확인한다.
14. 관련 리플렉션(Reflection) 기록이 있다면 계기(Trigger)·범위(Scope)·관찰 구간(Observation Window)과 당시 판본, 환류되지 않은 발견을 확인한다.
15. 관련 오케스트레이션(Orchestration) 기록이 있다면 질문·작업 패킷(Work Packet)·권한(Authority)·의존·인계(Handoff)·통합 상태와 재개방 조건을 확인한다.
16. 품질 관심사 프로필(Quality Concern Profile)을 사용했다면 분야 비종속 질문(Domain-uncommitted Question), 참조 렌즈(Reference Lens)의 가시성과 사각지대, 위치(Position)별 관점(Perspective)·관념(Notion) 방향·기능 배정(Function Assignment)·권한(Authority)·근거(Evidence)·트레이드오프(Trade-off)와 환류 상태를 확인한다.

기존 이름을 확인하기 전에 새 문서를 만들지 않는다. 같은 대상을 다른 이름으로 중복 생성하는 것이 가장 흔한 손상이다.

## 조사하거나 분석할 때

- 질문을 답하는 데 필요한 증거를 먼저 정의한다.
- 넓은 인벤토리에서 관련 진입점을 찾고, 상태 변화와 결과까지 추적한다.
- 구조·선언의 근거, 행동·경험 관찰, 문서 설명을 구분한다.
- 제목·명칭·분류·표면 문구만으로 행동을 확정하지 않는다.
- 기존 씬(Scene) 경계가 틀렸다고 보이면 즉시 덮어쓰지 말고 새 근거와 영향 범위를 기록한다.
- “찾지 못함”에는 검색 범위를 붙인다.
- 관찰과 SSS 해석을 별도 문장으로 쓴다.
- 무언가 걸리면 원인·평가를 몰라도 텐션(Tension)으로 기록할 수 있지만, 이슈(Issue)나 수정 요청으로 자동 승격하지 않는다.

## 문서를 수정할 때

수정 순서는 다음과 같다.

1. 직접 근거 또는 설계 의도
2. 해당 씬(Scene)과 비트(Beat)
3. 관련 액터(Actor)/소품(Prop)/세팅(Setting)/장소(Location)
4. 인입·유출 인과성(Causality) 엣지(edge)
5. 영향받는 완결 단위(Closure Unit)
6. 주제(Subject)와 오버뷰/교차표
7. 주체별 관념 스트림(Notion stream), 정렬·긴장·단절과 비지배 범위
8. 관련 텐션(Tension)의 감지·재해석·잔류 상태. 조치가 없을 수도 있음
9. 스테이징(Staging)에 영향을 주는 변경이면 관련 작업 뷰(Working View)와 환류 상태
10. 백스테이지(Backstage)에서 드러난 숨은 조건·액터(Actor)·소품(Prop)·엣지(edge)·완결(Closure)과 인계(Handoff)
11. 관련 시맨틱 프로브(Semantic Probe)의 발견·한계·보존 여부와 정본 환류
12. 관련 프로덕션(Production)의 작업 결정(Working Decision)·결과·EIFS 평가(assessment)와 리플렉션(Reflection) 인계(Handoff)
13. 관련 리플렉션(Reflection)의 관찰(Observation)·관념 스트림(Notion stream) 비교·텐션(Tension)·미확인(Unknown)과 정본/프로브(Probe)/프로덕션(Production) 환류
14. 관련 오케스트레이션(Orchestration)의 Packet·인계(Handoff)·통합·동반 변경(Co-change)과 종료/재개방 상태
15. 관련 품질 관심사(Quality Concern)의 관점(Perspective)·권한(Authority)·근거(Evidence)·트레이드오프(Trade-off)·텐션(Tension)과 인계(Handoff)
16. 링크와 구조 검증

새 파일 하나만 추가하고 끝내지 않는다. SSS의 단위는 파일이 아니라 관계다.

## 문체 규칙

- 목적은 한 문장으로 쓴다.
- 액터(Actor)와 역할(Role)을 함께 쓴다.
- 비트(Beat)는 `누가 무엇을 하여 무엇이 변한다`로 쓴다.
- 추상적 공간이나 의인화에는 해석임을 표시한다.
- `항상`, `절대`, `모든`은 완전한 근거가 있을 때만 쓴다.
- “전형적 과정”과 “필수 과정”을 구분한다.
- 인과성(Causality)·개연성(Plausibility)·핍진성(Verisimilitude)을 한 평가로 합치지 않는다.
- 미확인을 추측으로 메우지 않는다.
- 제작자가 선언한 관념(Notion)을 작품 전체의 실제 작동이나 소비자의 정답으로 쓰지 않는다.
- 같은 단어의 반복과 스트림(stream)의 정렬을 구분한다.
- 텐션(Tension)의 감지, 해석, 평가, 활용을 각각 구분한다.
- 저널(Journal)의 Active/종결 상태(Closed)를 중요/해결 구분으로 읽지 않고, 종결 상태(Closed)의 재열림 가능성과 잔여물을 보존한다.
- `텐션(Tension) 없음`과 `아직 관찰하지 않음`을 구분한다.
- 스테이징 관점(Staging Perspective)과 세계 안의 액터(Actor) 역할(Role)을 구분한다.
- 스테이징(Staging)에서 새 의미를 발견하면 스테이징(Staging) 문서를 정본으로 만들지 말고 해당 원래 문서로 환류한다.
- 백스테이지(Backstage)를 백엔드(Backend)나 기술 체크리스트로 축소하지 않고, 발견한 의미를 현재 SSS 요소로 환류한다.
- 시맨틱 프로브(Semantic Probe)의 산출물·온톨로지(ontology)·AI 출력을 현실이나 정본으로 승격하지 않는다.
- 프로덕션(Production) 산출물(artifact)과 EIFS 점수를 정본·객관적 가치·영구 우선순위로 승격하지 않는다.
- 리플렉션(Reflection)의 의미 차이(Semantic Delta)·Feedback·AI 해석을 결함·요구사항(Requirement)·전체 소비자의 보편적 관념(Notion)으로 승격하지 않는다.
- 오케스트레이션 기능(Orchestration Function)이나 기능 배정(Function Assignment)을 직책·계급·의미 권위(semantic authority)로 만들지 않고, 병렬 산출물을 통합 없이 정본에 반영하지 않는다.

## 새 단위를 만들기 전 질문

### 새 액터(Actor)인가?

- 기존 액터(Actor)의 새 역할(Role)은 아닌가?
- 독립된 목표·지식·권한·책임이 있는가?

### 새 소품(Prop)인가?

- 기존 소품(Prop)의 한 필드나 상태가 아닌가?
- 여러 씬(Scene)에서 같은 의미 단위로 지속되는가?

### 새 씬(Scene)인가?

- 목적, 권한, 정보, 시간, 종료 중 무엇이 바뀌는가?
- 상위 씬(Scene)의 보조 대화상자나 단순 조작은 아닌가?

### 새 주제(Subject)인가?

- 여러 씬(Scene)과 요소를 실제로 가로지르는가?
- 기존 주제(Subject)의 하위 사례가 아닌가?
- 배타적 카테고리를 만들려는 것은 아닌가?

### 새 완결 단위(Closure Unit)인가?

- 시작, 열린 상태, 하나 이상의 종료, 잔여물을 말할 수 있는가?
- 단순 씬(Scene) 묶음이나 시퀀스(Sequence)는 아닌가?

### 새 관념 스트림(Notion stream)인가?

- 누가 어떤 위치와 맥락에서 생성·구성·수용하는가?
- 고정 키워드가 아니라 출발과 방향, 변형을 말할 수 있는가?
- 기존 스트림(stream)과 어휘가 같아도 관점이나 방향이 다른가?
- 기존 스트림(stream)과 겹치지 않아도 큰 의미 방향에 정렬되는가?
- 무엇을 설명하지 않으며 무엇을 지배해서는 안 되는가?

### 새 텐션(Tension) 기록(record)인가?

- 누가 어떤 위치(Position)·관점(Perspective)·맥락(Context)에서 감지했는가?
- 어느 대상과 지점에서 무엇을 느꼈는가?
- 직접 감지인가, 여러 관점 사이의 관계적 감지인가?
- 원인이나 가치가 이미 확정됐다면 Error·Warning·이슈(Issue)가 더 정확하지 않은가?
- 다른 감지자·시점·궤적과 분리해야 하는가?
- 해석·평가·조치 없이 기록하는 것으로 충분한가?

## 작업 결과 보고 형식

후속 작업자는 최소한 다음을 보고한다.

```text
변경한 질문/범위:
확인한 근거:
새 관찰:
새 추론 또는 설계 판단:
수정한 씬(Scene)/비트(Beat)/엣지(edge)/완결(Closure):
수행·수정한 스테이징(Staging)과 정본 환류:
수행·수정한 백스테이지(Backstage) 탐색과 프로덕션(Production)/리플렉션(Reflection) 인계(Handoff):
사용한 시맨틱 프로브(Semantic Probe)와 새 관찰·한계·정본 환류:
수행·영향받은 프로덕션(Production)과 작업 결정(Working Decision)·EIFS 평가 기준·입력·결과:
수행·영향받은 리플렉션(Reflection)의 범위(Scope)·관찰 구간(Observation Window)·환류:
수행·영향받은 오케스트레이션(Orchestration)의 Packet·인계(Handoff)·통합·동반 변경(Co-change):
수행·영향받은 품질 관심사(Quality Concern)의 분야 비종속 질문(Domain-uncommitted Question)·참조 렌즈(Reference Lens)·위치(Position)·기능 배정(Function Assignment)·관념(Notion)·트레이드오프(Trade-off):
영향받은 관념 스트림(Notion stream)과 정렬 관계:
새로 감지·재해석·잔류한 텐션(Tension)과 감지자:
저널(Journal)/종결 상태(Closed) 이동·재열림과 종결 이유(Closing Reason)·잔여(Residual):
남은 미확인과 조사 범위:
구조·링크 검증 결과:
```

## 하지 말아야 할 것

- UI 창 목록을 그대로 씬(Scene) 목록으로 만드는 것
- 자료나 구현의 한 구성 단위를 자동으로 액터(Actor) 하나로 보는 것
- 주제(Subject)를 서로 배타적인 폴더로 만드는 것
- 실행하지 않은 경로를 동적으로 관찰했다고 쓰는 것
- 성공 경로만 쓰고 취소·실패 종료를 빼는 것
- 오버뷰 그래프만 고치거나 상세 문서만 고치는 것
- 이전 미확인을 근거 없이 확정으로 바꾸는 것
- 전형적 경로를 상태기계의 필수 전이로 바꾸는 것
- 초기 관념(Notion)을 모든 요소의 승인 기준으로 만들어 발견과 창의성을 막는 것
- 담당자별 차이와 소비자 해석을 하나의 제작자 메시지로 통합하는 것
- 생산적인 충돌을 정렬 실패로 보고 자동 제거하는 것
- 텐션(Tension)을 버그·불만·극적 긴장감 중 하나로 축소하는 것
- 텐션(Tension) 수와 강도를 품질·중요도·수정 우선순위로 사용하는 것
- 모든 텐션(Tension)을 해석하거나 해소해야 작업이 끝난다고 보는 것
- 감지 위치를 원인 위치로 단정하거나 한 감지자의 반응을 보편화하는 것
- 관념(Notion)을 참·거짓을 가리거나 근거가 모이면 언젠가 확정할 명제로 다루는 것. 묻는 것은 이름이 맞는지가 아니라 이름이 흐름을 따라가는지 굳었는지다
- 프로덕션(Production)에서 미확인(Unknown)이나 [비고정 원칙](00-notion.md#비고정-원칙)을 이유로 결정 고정을 회피하는 것. 코딩 전에 범위의 작업 결정(Working Decision)을 고정하고, 구현 중 필요해진 의미 결정은 코드에서 조용히 정하지 않고 기록한다

## 권장 작업 종료 조건

- 요청한 질문에 대한 결론이 명시됐다.
- 결론마다 관찰/추론/의도 상태와 근거가 있다.
- 영향받는 모든 SSS 층이 갱신됐다.
- 새 고아 문서나 깨진 링크가 없다.
- 다음 작업자가 남은 구멍을 재조사 없이 식별할 수 있다.
- 관념(Notion)이 가장 중요한 설명으로 통합됐지만 다른 요소의 자체 논리와 반례가 보존됐다.
- 텐션(Tension) 기록 통로가 유지됐지만 형식적인 감지나 강제 해소를 만들지 않았다.
