# 언어·실행기

프로그래밍 언어의 특성과 코드를 실행하는 런타임의 동작을 정리합니다.

## 중분류·소분류

굵은 경로는 중분류이며, 그 아래 경로는 해당 주제를 나눈 소분류입니다.

| 경로 | 정리할 내용 |
| --- | --- |
| **[language-theory/](language-theory/)** | 언어에 공통으로 적용되는 개념 |
| [language-theory/semantics/](language-theory/semantics/) | 값, 평가 전략, 스코프와 언어의 의미 |
| [language-theory/type-systems/](language-theory/type-systems/) | 타입, 추론, 제네릭과 타입 안전성 |
| [language-theory/programming-paradigms/](language-theory/programming-paradigms/) | 객체지향, 함수형, 선언형 프로그래밍 |
| **[languages/](languages/)** | 개별 언어의 문법·기능·사용법 |
| [languages/java/](languages/java/) | Java의 언어 기능과 표준 라이브러리 |
| [languages/kotlin/](languages/kotlin/) | Kotlin의 타입, null 안전성, 코루틴과 언어 기능 |
| [languages/javascript/](languages/javascript/) | JavaScript의 스코프, 클로저, 프로토타입과 비동기 표현 |
| [languages/typescript/](languages/typescript/) | TypeScript의 타입 모델링, 추론과 제네릭 |
| [languages/python/](languages/python/) | Python의 문법, 객체 모델과 표준 라이브러리 |
| **[runtimes/](runtimes/)** | 개별 실행 환경의 구조와 동작 |
| [runtimes/jvm/](runtimes/jvm/) | 클래스 로딩, 바이트코드, JIT, JVM 메모리와 GC |
| [runtimes/nodejs/](runtimes/nodejs/) | Node.js의 이벤트 루프, 모듈과 I/O 실행 환경 |
| [runtimes/cpython/](runtimes/cpython/) | CPython의 인터프리터, 바이트코드와 객체 관리 |
| **[compilers-and-interpreters/](compilers-and-interpreters/)** | 언어를 분석하고 실행하는 구현 기법 |
| [compilers-and-interpreters/parsing/](compilers-and-interpreters/parsing/) | 어휘·구문 분석과 구문 트리 |
| [compilers-and-interpreters/intermediate-representations/](compilers-and-interpreters/intermediate-representations/) | 중간 표현과 코드 변환 |
| [compilers-and-interpreters/optimization-and-code-generation/](compilers-and-interpreters/optimization-and-code-generation/) | 최적화와 기계어·바이트코드 생성 |
| [compilers-and-interpreters/interpreter-design/](compilers-and-interpreters/interpreter-design/) | 인터프리터와 가상 머신의 실행 방식 |

## 배치 기준

언어는 개별 언어별로, 런타임은 개별 실행기별로 나눕니다. Java·Kotlin이 공유하는 JVM 원리는 runtimes/jvm에 모읍니다.

문서는 개념, 문제, 해결 기법과 선택 근거를 중심으로 작성합니다. 구현·실험은 해당 문서 가까이에 두며, 기술별 탐색은 [기술별 목차](../indexes/technologies/)에서 연결합니다.
