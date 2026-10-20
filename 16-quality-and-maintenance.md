# 품질과 유지보수

Scenario-Semantic Synthesis(SSS) 문서는 그래프형 지식베이스이므로 내용의 정확성뿐 아니라 링크·ID·역참조의 일관성이 중요하다.

## 품질의 네 축

### 커버리지

- 대상의 주요 화면, 상태, 판단, 자동화, 실패 경로가 배정됐는가?
- UI가 없는 AI와 규칙 책임이 빠지지 않았는가?
- 보조 요소를 독립 씬(Scene)으로 만들지 않은 이유가 설명되는가?
- 제작 참여자·작품 구성·소비자의 주요 관념 스트림(Notion stream)과 정렬·긴장·단절이 검토됐는가?
- 설명되지 않은 감각을 기록할 텐션(Tension) 통로가 있으며, 관찰한 관점과 관찰하지 않은 범위가 구분되는가?

### 추적성

- 씬(Scene)의 비트(Beat)에서 액터(Actor), 소품(Prop), 엣지(edge), 완결(Closure)로 이동할 수 있는가?
- 중요한 해석이 근거 위치로 돌아가는가?
- 오버뷰와 상세 문서가 서로 링크되는가?
- 텐션(Tension)의 감지 지점, 선택적 원인 후보, 상류·하류 관련 요소가 원본 기록(record)과 연결되는가?

### 인식론적 정직성

- 관찰, 추론, 설계 의도, 미확인, 모순이 구분되는가?
- 구조와 선언의 조사를 실제 행동·경험 관찰처럼 쓰지 않았는가?
- 부정적 결론에 조사 범위가 있는가?
- 선언된 관념(Notion), 구성·작동한 관념(Notion), 분석자가 추론한 관념(Notion), 조사된 소비자 수용이 구분되는가?
- 텐션(Tension) 감지 사실과 원인·가치·중요도·조치 판단이 분리되는가?

### 사용성

- 새 독자가 전체 구조를 한 문서에서 조망할 수 있는가?
- 질문별 읽기 경로가 있는가?
- 전형적 경로가 필수 순서로 오해되지 않는가?
- 문서가 분류를 위해 존재하지 않고 실제 판단을 돕는가?
- 관념(Notion)이 가장 중요한 설명으로 보이면서도 다른 모든 문서를 읽기 전에 정답으로 오해되지 않는가?
- 텐션(Tension)이 필수 관찰 장치로 보이면서도 이슈(Issue) 목록이나 품질 점수로 오해되지 않는가?
- Scenario가 각본·사용 사례·선형 정상 경로 또는 모든 요소의 상위 객체로 오해되지 않는가?
- 종합(Synthesis)이 차이를 제거한 단일 해석·합의·평균·완성 선언으로 오해되지 않는가?

## 필수 교차 검사

| 검사 | 발견하려는 문제 |
|---|---|
| 씬(Scene)–액터(Actor)/역할(Role) 행렬 | 주체 없는 변화, 모든 권한을 가진 액터(Actor) |
| 씬(Scene)–소품(Prop) 행렬 | 생성자·소비자 없는 데이터, 끊긴 상태 호 |
| 복합 실체–코어 요소 지도 | 하나의 기술·사물 종류를 액터(Actor)·소품(Prop)·세팅(Setting)·장소(Location) 중 하나로 고정함, 서로 다른 읽기의 정본 링크 누락 |
| 편입 구성(Imported Configuration) 전제 검사 | 기능만 재사용한다고 가정함, 성립 조건(Constitutive Condition)·환경 전제(Environmental Premise)·관념적 선택(Notional Choice) 혼합, 원래 환경의 인과를 현재 전체 규칙으로 일반화함 |
| 씬(Scene)–주제(Subject) 행렬 | 주제(Subject)적 탐색의 공백, 주제(Subject)의 과도한 독점 |
| 씬(Scene)–완결(Closure) 행렬 | 닫히지 않는 과업, 종료만 있고 시작 없는 결과 |
| 관념(Notion)–주체 행렬 | 단일 제작자 의도로 환원, 소비자와 분업 참여자의 스트림(stream) 누락 |
| 관념(Notion)–SSS 요소 행렬 | 근거 없는 큰 주제(Subject)문, 구체 구성과 연결되지 않는 의도 |
| 관념(Notion) 정렬 지도 | 겹침과 정렬의 혼동, 생산적 긴장과 우발적 단절의 혼동 |
| 텐션(Tension)–관점 행렬 | 감지자 누락, 한 사람의 감각을 보편 반응으로 일반화 |
| 텐션(Tension)–SSS 요소 지도 | 감지 위치를 원인 위치로 오인, 상류·하류 관계 누락 |
| 텐션(Tension) 상태 감사 | 감지·해석·평가·활용 혼합, 모든 기록(record)의 강제 해소 |
| 텐션 저널(Tension Journal)–종결 상태(Closed) 감사 | 저널(Journal)의 backlog화, 국소 감지만 기록하고 전체 관계 누락, 종결 상태(Closed)를 Completed로 오인, 재열림 단서 유실 |
| 스테이징(Staging)–정본 환류 검사 | 관점별 재구성이 정본을 조용히 대체함, 새 발견이 작업 뷰(Working View)에만 남음 |
| 백스테이지(Backstage)–정본 환류 검사 | 숨은 액터(Actor)·상태·판단이 기술 노트(note)에만 남음, 질문 군(Family)이 체크리스트로 굳음 |
| 프로브(Probe)–정본·근거 검사 | 도구 산출물이 정본이나 관찰(Observation)로 오인됨, blind spot과 새 가정이 누락됨 |
| 프로덕션(Production)–정본·결정 검사 | 작업 결정(Working Decision)이 원래 의도로 소급됨, 산출물(artifact)이 정본을 대체함, EIFS 평가 기준·입력·근거 누락 |
| 리플렉션(Reflection)–근거·환류 검사 | 좁은 관찰 구간(Observation Window)의 일반화, 차이의 자동 결함화, 작업 뷰(Working View)가 정본을 대체함 |
| 오케스트레이션(Orchestration)–통합 검사 | 질문 없는 기계적 분할, 병렬 결과 나열, 인계(Handoff)에서 근거·미확인(Unknown) 유실, 조율 기능(Coordination Function) 담당자의 의미 권위화 |
| 품질 관심사 프로필(Quality Concern Profile) 감사 | 범용 질문의 온톨로지(ontology)화, 한 분야 참조 렌즈(Reference Lens)의 지배, 분야 어휘의 정밀도 소실, 직책별 고정 관념(Notion)·소유권, 측정값(Measure)의 품질 전체 환원, 트레이드오프(Trade-off)와 텐션(Tension) 혼동 |
| Scenario 경계 감사 | 씬(Scene)·시퀀스(Sequence)·완결(Closure)과의 혼동, 대표 정상 경로의 전체화, 필수 상위 컨테이너 생성 |
| 비환원적 종합(Non-reductive Synthesis) 감사 | 관점·근거·반례·텐션(Tension)·미확인(Unknown)의 삭제, 종합 담당자의 의미 권위화, 단일 최종 해석 강제 |
| 인입/유출 엣지(edge) 검사 | 고립 씬(Scene), 막힌 전이 |
| 근거 커버리지 표 | 근거 없는 확정, 조사됐지만 문서화되지 않은 영역 |

## 자동 검증 권장 항목

- 모든 로컬 Markdown 링크의 대상 존재
- 중복 ID와 파일명 충돌
- 오버뷰에 등록되지 않은 상세 문서
- 상세 문서에서 참조되지 않는 그래프 엣지(edge)
- 씬(Scene) 문서의 필수 절: 목적, 진입/전이, 비트(Beat), 근거, 인과 연결
- 인과성(Causality) 문서의 세 평가 존재
- 완결(Closure) 문서의 시작, 열린 상태, 정상/대안 완결, 잔여물 존재
- 관념(Notion) 문서의 관점 주체, 출발 맥락, 방향, 변형, 정렬/긴장, 비지배 범위 존재
- 선언·구성·작동·추론·수용·환류 상태의 근거 연결
- 텐션(Tension) 기록(record)의 감지자·관점·대상·맥락·원문 감각 존재
- 해석·원인·평가·활용 필드가 선택 사항이며 상태별 근거가 분리됨
- 텐션(Tension) 수·강도가 자동 품질 점수나 수정 우선순위로 사용되지 않음
- 장기 텐션(Tension)은 필요할 때 관점·구조·시간·완결(Closure)·관념(Notion)을 가로지르는 궤적이 저널(Journal)에 보이고, 종결 상태(Closed)에는 이유(Reason)·잔여(Residual)·재개방 신호(Reopen Signal)가 보존됨
- 스테이징 관점(Staging Perspective)과 세계 안의 역할(Role)이 구분되고, 재구성의 출처와 정본 환류 위치가 필요한 만큼 연결됨
- 백스테이지(Backstage) 질문이 필요한 군(Family)만 사용되고, 발견된 의미가 기존 SSS 요소와 근거로 환류됨
- 시맨틱 프로브(Semantic Probe) 입력·출력의 근거 상태, 새 결정, blind spot, 정본 환류와 보존 여부가 필요한 만큼 구분됨
- 프로덕션(Production)의 결정 출처·범위(Scope)·결과 판본·완결(Closure)·EIFS 평가 기준·입력·이유(Reason)·근거(Evidence)가 필요한 만큼 구분됨
- 리플렉션(Reflection)의 계기(Trigger)·범위(Scope)·관찰 구간(Observation Window), 관념 스트림(Notion stream) 비교, 관찰(Observation)/추론(Inference), 텐션(Tension)과 환류가 필요한 만큼 구분됨
- 오케스트레이션(Orchestration)의 작업 패킷(Work Packet)이 질문·범위(Scope)·권한(Authority)·중지 조건(Stop Condition)을 가지며, 의존·통합·인계(Handoff)·동반 변경(Co-change)과 재개방 조건이 필요한 만큼 보임
- 품질 관심사 프로필(Quality Concern Profile)을 사용했다면 분야 비종속 질문(Domain-uncommitted Question), 참조 렌즈(Reference Lens), 작업 어휘(Working Vocabulary), 위치(Position)·오케스트레이션 기능(Orchestration Function)·기능 배정(Function Assignment)·관념(Notion)·근거(Evidence)·측정값(Measure)이 분리되고, 렌즈별 가시성·사각지대·비동일성 경계와 영향 위치(Impact Position)·결정 권한(Decision Authority)이 혼동되지 않음
- `TODO`, `미확인`, `모순`의 중앙 목록과 역링크

도구가 없더라도 작업을 완료하기 전에 체크리스트로 수행한다. 자동 검증은 의미 품질을 대신하지 않지만 구조적 부패를 빠르게 찾는다.

## 변경 절차

새 근거 또는 설계 변경이 들어오면 다음 순서로 갱신한다.

1. 근거 레코드의 대상 식별자·판본을 갱신한다.
2. 직접 영향을 받는 씬(Scene)/비트(Beat)를 수정한다.
3. 관련 액터(Actor)/소품(Prop)/세팅(Setting)/장소(Location) 연속성을 확인한다.
4. 인입·유출 인과성(Causality) 엣지(edge)의 세 평가를 재검토한다.
5. 완결(Closure)의 시작·종료·잔여가 달라졌는지 확인한다.
6. 주제(Subject)의 탐색 경로와 교차표를 갱신한다.
7. 관련 관념 스트림(Notion stream)이 강화·약화·반전·분기됐는지, 다른 관점과의 정렬이 달라졌는지 확인한다.
8. 관련 텐션(Tension)이 새로 감지·재해석·해소·잔류했는지 확인하되 모든 기록(record)의 처리를 강제하지 않는다.
   장기 추적 기록(record)이라면 저널(Journal)/종결 상태(Closed) 이동과 재열림 이력도 확인한다.
9. 관련 스테이징(Staging) 작업 뷰(Working View)가 낡았는지, 환류되지 않은 발견이 있는지 확인한다.
10. 관련 백스테이지(Backstage) 작업 뷰(Working View)와 프로덕션(Production)/리플렉션(Reflection) 인계(Handoff)가 낡았는지 확인한다.
11. 관련 시맨틱 프로브(Semantic Probe)가 현재 질문에 여전히 유효한지, 산출물과 환류된 발견이 구분되는지 확인한다.
12. 관련 프로덕션(Production)의 작업 결정(Working Decision)·산출물(artifact)·EIFS 평가(assessment)가 정본과 분리되고 결과가 환류됐는지 확인한다.
13. 관련 리플렉션(Reflection)이 당시 판본과 관찰 범위를 명시하고 발견을 적절한 정본·프로브(Probe)·프로덕션(Production)으로 환류했는지 확인한다.
14. 관련 오케스트레이션(Orchestration)의 병렬·순차 결과가 명칭·판본·근거(Evidence) 상태를 보존한 채 통합되고 환류됐는지 확인한다.
15. 관련 품질 관심사(Quality Concern) 기록이 있다면 직책별 고정 관념(Notion)이나 독점 책임을 만들지 않고 트레이드오프(Trade-off)·텐션(Tension)·권한(Authority)·인계(Handoff)를 보존했는지 확인한다.
16. 오버뷰, 링크, 미확인 목록을 검증한다.

문서 하나만 고치는 습관은 그래프를 빠르게 낡게 만든다. 변경 영향 범위를 관계별로 따라간다.

## 기록 안정성과 변경 관리

- 표시 이름과 안정 ID를 분리한다.
- ID는 생성 후 의미가 조금 달라져도 가능한 유지한다.
- 대규모 분할/병합 시 이전 ID의 리다이렉트 또는 변경 기록을 남긴다.
- 근거에는 대상 식별자·판본을 붙인다.
- 분석 결과와 일반 방법론을 같은 디렉터리에 섞지 않는다.
- 그래프가 커지면 한 거대 Mermaid 도식 대신 상위 지도와 부분 그래프를 함께 둔다.

## 완료 전 체크리스트

- [ ] Scenario를 새 코어 객체·필수 상위 문서·선형 정상 경로로 만들지 않았다.
- [ ] 시나리오적 전개(Scenario-like Unfolding)에 정상·실패·취소·중단·분기·병렬·반복과 서로 다른 완결(Closure) 시간 규모가 필요한 만큼 보존됐다.
- [ ] 종합(Synthesis)이 관점·출처·근거(Evidence)·국소 논리·텐션(Tension)·미확인(Unknown)·반례를 하나의 결론으로 환원하지 않았다.
- [ ] 모든 씬(Scene)에 한 문장 목적이 있다.
- [ ] 액터(Actor)와 역할(Role)이 구분된다.
- [ ] 각 비트(Beat)는 구체적인 변화를 말한다.
- [ ] 주요 소품(Prop)의 생성·변경·소비·잔여가 이어진다.
- [ ] 세팅(Setting)과 장소(Location)가 혼동되지 않는다.
- [ ] 복합 실체를 하나의 코어 요소로 고정하지 않고, 실제로 성립하는 다중 읽기를 필요한 정본 사이에 연결했다.
- [ ] 편입 구성(Imported Configuration)을 사용했다면 성립 조건(Constitutive Condition)·환경 전제(Environmental Premise)·관념적 선택(Notional Choice)을 확정 분류가 아닌 현재 범위의 렌즈로 구분했다.
- [ ] 주제(Subject)가 배타적 소유권을 주장하지 않는다.
- [ ] 주제(Subject)와 관념(Notion)이 `무엇`과 `왜·어느 방향`으로 구분된다.
- [ ] 중요한 엣지(edge)에 인과성(Causality)·개연성(Plausibility)·핍진성(Verisimilitude) 평가가 있다.
- [ ] 핵심 완결(Closure)에 실패·취소·중단 경로가 있다.
- [ ] UI 종료와 의미 종료가 필요한 곳에서 분리된다.
- [ ] 관찰과 추론이 구분되고 미확인이 숨겨지지 않는다.
- [ ] 오버뷰와 상세 문서의 링크가 양방향이다.
- [ ] 원래 분석/설계 질문을 다시 대조했다.
- [ ] 관념(Notion)은 복수의 관점별 스트림(stream)으로 기록됐다.
- [ ] 같은 어휘의 겹침을 정렬로 오인하지 않았다.
- [ ] 대비·충돌·반전과 생산적 긴장을 불일치라는 이유만으로 제거하지 않았다.
- [ ] 큰 관념(Notion)으로 설명되지 않는 국소 논리와 반례가 보존됐다.
- [ ] 초기 관념(Notion)이 모든 액터(Actor)·씬(Scene)을 지배하는 통과 기준이 되지 않았다.
- [ ] 텐션(Tension) 기록 통로는 필수지만 모든 요소에 형식적인 텐션(Tension)을 만들지 않았다.
- [ ] 텐션(Tension) 감지와 Error·Warning·이슈(Issue) 판정이 분리됐다.
- [ ] 감지 위치를 원인 위치로 단정하지 않았다.
- [ ] 강도는 관찰자·맥락 기준이며 객관 점수처럼 사용되지 않았다.
- [ ] 미해석·보류·무조치·잔류가 유효한 상태로 허용됐다.
- [ ] 텐션(Tension) 해소를 자동으로 개선이나 완결(Closure) 종료로 취급하지 않았다.
- [ ] 텐션(Tension)을 국소 오류 목록으로 축소하지 않고 필요한 경우 관점·씬(Scene)·엣지(edge)·완결(Closure)·관념(Notion)을 가로지르는 전체 궤적을 보았다.
- [ ] 저널(Journal)을 backlog·우선순위표·정본으로 만들지 않았다.
- [ ] 종결 상태(Closed)를 Completed·Resolved·Deleted와 동일시하지 않았고 종결 이유(Closing Reason)·잔여(Residual)·재개방 신호(Reopen Signal)를 보존했다.
- [ ] 재열림을 과거 닫힘의 실패로 단정하거나 기존 이력을 덮어쓰지 않았다.
- [ ] 스테이징(Staging) 산출물을 정본이나 프로덕션(Production) 승인 게이트(Gate)로 만들지 않았다.
- [ ] 스테이징(Staging)에서 발견한 새 의미가 필요한 정본으로 환류됐거나 미환류 상태로 명시됐다.
- [ ] 백스테이지(Backstage)를 백엔드(Backend)·NFR 목록·기술 백과사전으로 축소하지 않았다.
- [ ] 백스테이지(Backstage) 질문을 전부 검사하거나 질문 수를 완전성 점수로 사용하지 않았다.
- [ ] 숨은 액터(Actor)·소품(Prop)·세팅(Setting)·장소(Location)·비트(Beat)·엣지(edge)·완결(Closure)이 필요한 정본으로 환류됐다.
- [ ] 프로브(Probe)의 형식과 온톨로지(ontology)를 SSS 코어(Core)나 현실의 구조로 승격하지 않았다.
- [ ] 프로브(Probe)가 생성한 표현·추론과 실제 관찰(Observation)을 구분했다.
- [ ] 프로브(Probe)의 blind spot과 새로 추가한 가정·결정을 필요한 만큼 기록했다.
- [ ] 프로덕션(Production) 종료와 완결(Closure) 종료, 텐션(Tension) 해소, 관념(Notion)의 이름 고정을 동일시하지 않았다.
- [ ] 작업 결정(Working Decision)과 구현 국소 선택(Implementation-local Choice)을 원래부터 있던 의미로 소급하지 않았다.
- [ ] EIFS를 사용했다면 평가 기준·적용 조건·범위(Scope), E/I/F/S의 이유(Reason)·근거(Evidence)와 Intervention/탐색(Exploration) 구분이 있다.
- [ ] EIFS 평가 기준이나 해석이 달라져도 과거 평가(assessment)를 소급 수정하지 않았다.
- [ ] 리플렉션(Reflection)을 프로덕션(Production)의 필수 게이트(Gate)나 수정 건수 평가로 만들지 않았다.
- [ ] Intended·Realized·Experienced·Operational 관념(Notion)을 구분하고 초기 관념(Notion)을 정답표로 사용하지 않았다.
- [ ] 의미 차이(Semantic Delta)를 자동으로 텐션(Tension)·결함·변경 명령으로 바꾸지 않았다.
- [ ] 관찰 구간(Observation Window) 밖의 부재와 관찰하지 않음을 존재하지 않음으로 일반화하지 않았다.
- [ ] 리플렉션(Reflection) 기록 종료와 대상 완결(Closure) 종료·텐션(Tension) 해소·관념(Notion)의 이름 고정을 동일시하지 않았다.
- [ ] 과거 EIFS 평가(assessment)는 보존하고 사후 비교나 재평가는 별도 기록으로 남겼다.
- [ ] 오케스트레이션(Orchestration)을 고정 워크플로(Workflow)·조직도·승인 사슬로 만들지 않았다.
- [ ] 작업을 자료 양으로만 분할하지 않고 질문·범위(Scope)·근거(Evidence)·통합 지점과 중지 조건(Stop Condition)을 두었다.
- [ ] 독립적이지 않은 작업을 억지로 병렬화하거나 병렬 결과를 비교 없이 나열하지 않았다.
- [ ] 인계(Handoff)에서 관찰(Observation)·추론(Inference)·의도(Intent)·미확인(Unknown)·텐션(Tension)과 권한(Authority)이 보존됐다.
- [ ] 조율(Coordination)·종합(Synthesis)·문서화 기능(Documentation Function) 또는 그 담당자에게 의미 권위(semantic authority)가 자동 부여되지 않았다.
- [ ] 오케스트레이션(Orchestration) 종료를 대상 전체의 분석·프로덕션(Production)·관념(Notion) 완결로 오해하지 않았다.
- [ ] 품질 관심사(Quality Concern)를 관념(Notion)·주제(Subject)·요구사항(Requirement)·측정값(Measure)과 자동으로 동일시하지 않았다.
- [ ] 직책만으로 관념 스트림(Notion stream)과 관심사(Concern) 소유권을 고정하지 않았다.
- [ ] 트레이드오프(Trade-off) 후보, 충돌(Conflict), 텐션(Tension)을 구분하고 측정값(Measure)을 품질 전체의 객관 점수로 사용하지 않았다.
- [ ] 영향 위치(Impact Position)의 경험과 결정 권한(Decision Authority)을 필요한 곳에서 구분했다.

## 관념(Notion) 균형 감사

문서가 어느 한 방향으로 쏠리지 않았는지 다음 반대 질문을 함께 적용한다.

| 쏠림 | 교정 질문 |
|---|---|
| 제작자 중심주의 | 소비자와 다른 제작 참여자는 어떤 관념(Notion)을 새로 만드는가? |
| 수용 상대주의 | 실제 구성과 상태 변화가 허용하거나 제한하는 해석은 무엇인가? |
| 메시지 환원 | 액터(Actor)·소품(Prop)·씬(Scene)이 메시지와 무관하게도 자체 논리로 성립하는가? |
| 조화 강박 | 충돌과 불확정성이 의도적으로 만드는 의미는 무엇인가? |
| 창발 만능론 | 선언된 의도와 구체적으로 설계된 방향은 무엇인가? |
| 장르·주제(Subject) 환원 | 장르와 주제(Subject)를 넘어 인과·관계·맥락이 어떻게 변하는가? |
| 사후 합리화 | 반례와 설명되지 않는 요소, 판본 변화가 기록됐는가? |

감사의 목적은 중립적인 단일 해석을 만드는 것이 아니라, 특정 관점이 전체를 독점하는 것을 방지하는 것이다.

## 텐션(Tension) 균형 감사

| 쏠림 | 교정 질문 |
|---|---|
| 버그 목록화 | 원인과 위반 규칙이 실제로 확인됐는가, 아니면 감각만 기록된 상태인가? |
| 극적 긴장감 환원 | 흥미·공포가 아닌 위화감·매력·관점 차이도 허용되는가? |
| 중요도 과장 | 이 기록(record)이 재검토 표식 이상으로 중요한 근거가 있는가? |
| 해소 강박 | 유지·강화·보류·무조치가 더 적절할 가능성이 있는가? |
| 주관성 폐기 | 특정 관점에서 감지됐다는 사실 자체는 보존했는가? |
| 미스터리 낭만화 | 설명되지 않았다는 이유만으로 깊이·창의성·가치를 부여하지 않았는가? |
| 수량화 과신 | 강도 숫자의 기준·관찰자·맥락이 분명한가? |
| 부재 단정 | 기록 없음이 미관찰인지 실제 비감지인지 구분되는가? |

텐션(Tension) 감사의 목적은 더 많은 텐션(Tension)을 찾거나 없애는 것이 아니라, 감지를 판정으로 과장하지 않으면서도 설명되지 않은 감각을 잃지 않는 것이다.
