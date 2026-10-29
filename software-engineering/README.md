# 설계·개발·검증

요구사항을 코드와 구조로 옮기고 검증·개선하는 방법을 정리합니다.

## 중분류·소분류

굵은 경로는 중분류이며, 그 아래 경로는 해당 주제를 나눈 소분류입니다.

| 경로 | 정리할 내용 |
| --- | --- |
| **[requirements-and-modeling/](requirements-and-modeling/)** | 구현할 동작과 제약의 정의 |
| [requirements-and-modeling/functional-requirements/](requirements-and-modeling/functional-requirements/) | 기능 요구사항, 유스케이스와 동작 모델 |
| [requirements-and-modeling/quality-attributes-and-constraints/](requirements-and-modeling/quality-attributes-and-constraints/) | 품질 속성, 운영 조건과 설계 제약 |
| **[architecture/](architecture/)** | 시스템의 구조와 설계 선택 |
| [architecture/architectural-styles/](architecture/architectural-styles/) | 계층형, 헥사고날, 모놀리스, 마이크로서비스 등 구조 |
| [architecture/modularity-and-boundaries/](architecture/modularity-and-boundaries/) | 모듈, 의존성과 시스템 경계 |
| [architecture/architectural-decisions/](architecture/architectural-decisions/) | 대안, 트레이드오프와 아키텍처 의사결정 |
| **[domain-design/](domain-design/)** | 업무 개념과 경계의 모델링 |
| [domain-design/strategic-design/](domain-design/strategic-design/) | 하위 도메인, 경계와 컨텍스트 간 관계 |
| [domain-design/tactical-design/](domain-design/tactical-design/) | 엔티티, 값 객체, 애그리거트와 도메인 이벤트 |
| **[design-principles-and-patterns/](design-principles-and-patterns/)** | 코드 구조를 설계하는 원리와 반복되는 해법 |
| [design-principles-and-patterns/design-principles/](design-principles-and-patterns/design-principles/) | 응집도, 결합도, 책임과 의존성 |
| [design-principles-and-patterns/design-patterns/](design-principles-and-patterns/design-patterns/) | 설계 패턴의 의도, 구조와 적용 조건 |
| **[api-design/](api-design/)** | 사용자·시스템에 제공하는 인터페이스 설계 |
| [api-design/contracts-and-modeling/](api-design/contracts-and-modeling/) | 계약, 리소스, 요청·응답과 오류 모델 |
| [api-design/interaction-patterns/](api-design/interaction-patterns/) | 호출 방식, 페이지네이션과 비동기 작업 인터페이스 |
| [api-design/compatibility-and-evolution/](api-design/compatibility-and-evolution/) | 버전, 호환성과 API 변경 |
| **[application-mechanisms/](application-mechanisms/)** | 애플리케이션과 프레임워크의 공통 동작 |
| [application-mechanisms/dependency-injection/](application-mechanisms/dependency-injection/) | 의존성 주입, 객체 구성과 생명주기 |
| [application-mechanisms/request-processing/](application-mechanisms/request-processing/) | 요청 파이프라인, 라우팅과 공통 처리 |
| [application-mechanisms/persistence-integration/](application-mechanisms/persistence-integration/) | ORM, 매핑, 로딩과 영속성 컨텍스트 |
| [application-mechanisms/transaction-management/](application-mechanisms/transaction-management/) | 트랜잭션 경계, 전파와 애플리케이션 연동 |
| **[testing/](testing/)** | 소프트웨어 검증 전략과 테스트 작성 |
| [testing/testing-strategy/](testing/testing-strategy/) | 테스트 수준, 범위와 검증 전략 |
| [testing/test-design/](testing/test-design/) | 테스트 케이스, 속성 기반 테스트와 검증 기법 |
| [testing/test-doubles-and-fixtures/](testing/test-doubles-and-fixtures/) | 테스트 더블, 데이터와 실행 환경 준비 |
| **[refactoring-and-code-quality/](refactoring-and-code-quality/)** | 코드 품질 분석과 개선 |
| [refactoring-and-code-quality/refactoring/](refactoring-and-code-quality/refactoring/) | 코드 냄새와 동작을 보존하는 구조 개선 |
| [refactoring-and-code-quality/static-analysis/](refactoring-and-code-quality/static-analysis/) | 정적 분석과 코드 품질 검사 |
| [refactoring-and-code-quality/legacy-modernization/](refactoring-and-code-quality/legacy-modernization/) | 레거시 이해, 단계적 교체와 현대화 |
| **[development-practices/](development-practices/)** | 개발 과정에서 변경과 지식을 관리하는 방법 |
| [development-practices/version-control/](development-practices/version-control/) | Git, 브랜치, 변경 이력과 병합 |
| [development-practices/code-review/](development-practices/code-review/) | 리뷰 기준, 변경 단위와 피드백 |
| [development-practices/technical-documentation/](development-practices/technical-documentation/) | 설계 문서, ADR, 사용법과 기술 설명 |

## 배치 기준

Spring·Hibernate 같은 기술의 동작도 DI·요청 처리·영속성 등 해당 주제에 정리합니다. 언어 자체는 언어·런타임에, 빌드·배포 환경은 인프라에 둡니다.

문서는 개념, 문제, 해결 기법과 선택 근거를 중심으로 작성합니다. 구현·실험은 해당 문서 가까이에 두며, 기술별 탐색은 [기술별 목차](../indexes/technologies/)에서 연결합니다.
