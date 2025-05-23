# 03. eXtreme Programming 기법 (XP)

## 3.1. eXtreme Programming 개요

**익스트림 프로그래밍(eXtreme Programming, XP)**은 수시로 발생하는 고객의 요구사항 변경에 유연하게 대응하기 위해 고객의 참여와 개발 과정의 반복을 극대화하여 개발 생산성을 향상시키는 방법론입니다.

- 짧고 반복적인 개발 주기, 단순한 설계, 고객의 적극적인 참여를 통해 빠르게 개발하는 것이 목표입니다.
- 릴리즈의 규모를 작게 하고 릴리즈 주기를 짧게 반복하면서 고객의 요구사항을 적극적으로 수용합니다.
- **신속한 피드백**, **단순성**, **점진적 변화**, **품질 작업** 등을 기본 가치로 합니다.
- 개발자의 부담을 최소화하고 변화에 유연하게 대응하기 위한 **소통**, **단순함**, **용기**, **존중**, **피드백**의 다섯 가지 가치를 기반으로 합니다.

## 3.2. eXtreme Programming의 주요 실천 방법

### 3.2.1. 기본 실천 방법

1. **계획 세우기 (Planning Game)**

   - 개발할 기능에 대한 사용자 스토리(User Story) 작성
   - 릴리즈와 이터레이션 계획을 수립

2. **작은 릴리즈 (Small Release)**

   - 작은 시스템을 먼저 만들고, 짧은 주기로 업데이트

3. **메타포어 (Metaphor)**

   - 공통된 이름체계와 시스템 서술서를 통해 고객과 개발자 간의 의사소통 원활화

4. **간단한 디자인 (Simple Design)**

   - 현재의 요구사항을 해결하는 가장 단순한 설계를 채택
   - 불필요한 복잡성과 코드를 제거

5. **테스트 기반 개발 (Test-Driven Development)**

   - 테스트 케이스를 먼저 작성한 후 실제 코드를 개발
   - 지속적인 테스트로 품질 보증

6. **리팩토링 (Refactoring)**
   - 프로그램의 기능 변경 없이 내부 구조를 개선하는 작업
   - 중복 코드 제거, 객체 간의 의존성 줄이기 등을 통해 코드 품질 개선

### 3.2.2. 개발자 실천 방법

1. **짝 프로그래밍 (Pair Programming)**

   - 두 명의 개발자가 하나의 컴퓨터로 함께 작업
   - 한 명은 코드를 작성하고, 다른 한 명은 코드를 검토

2. **공동 코드 소유권 (Collective Ownership)**

   - 누구든지 언제라도 시스템의 어떤 부분이든 수정 가능
   - 전체 코드에 대한 책임을 공유

3. **지속적인 통합 (Continuous Integration)**

   - 작업한 코드는 하루에 여러 번 빌드하고 테스트하여 통합
   - 문제를 조기에 발견하고 해결

4. **40시간 근무 (40-hour Week)**

   - 지속적인 초과근무를 지양하여 생산성과 품질 유지
   - 개발자의 번아웃 방지

5. **현장 고객 (On-site Customer)**

   - 개발 기간 동안 고객을 팀의 일원으로 참여시켜 즉각적인 피드백 수집
   - 의사결정 지연 방지

6. **코딩 표준 (Coding Standards)**
   - 코드 작성에 대한 규칙을 정하여 모든 코드가 일관성을 유지하도록 함
   - 공동 작업과 유지보수 용이성 증가

## 3.3. eXtreme Programming의 개발 프로세스

### 3.3.1. 릴리즈 계획 수립

1. **사용자 스토리 작성**

   - 고객이 시스템을 통해 얻고자 하는 것을 간단한 시나리오로 작성
   - 각 스토리는 구현하는 데 필요한 시간을 예측

2. **릴리즈 계획 수립**
   - 어떤 스토리를 어떤 순서로 개발할지 우선순위 결정
   - 첫 번째 릴리즈의 범위와 일정 계획

### 3.3.2. 이터레이션

1. **이터레이션 계획**

   - 각 이터레이션(보통 1~3주)에서 구현할 스토리 선택
   - 스토리를 작업(Task)으로 분할하고 개발자에게 할당

2. **테스트 작성**

   - 구현할 기능에 대한 테스트 케이스 먼저 작성
   - 테스트가 성공하면 해당 기능 구현 완료로 간주

3. **쌍 프로그래밍**

   - 두 명의 개발자가 한 컴퓨터에서 함께 개발
   - 코드 품질 향상 및 지식 공유

4. **지속적 통합**
   - 코드 변경사항을 자주 통합하고 테스트
   - 모든 테스트가 통과해야 다음 단계로 진행

### 3.3.3. 인수 테스트

1. **고객 테스트**

   - 고객이 정의한 요구사항을 충족하는지 확인
   - 고객의 피드백 수집 및 반영

2. **소규모 릴리즈**
   - 완성된 기능을 작은 단위로 자주 릴리즈
   - 사용자에게 빠른 가치 전달

### 3.3.4. 회고와 조정

1. **회고 미팅**

   - 이터레이션이나 릴리즈 후 프로세스 개선점 도출
   - 잘된 점과 개선할 점을 논의

2. **프로세스 조정**
   - 회고에서 나온 개선점을 다음 이터레이션에 적용
   - 지속적인 프로세스 개선
