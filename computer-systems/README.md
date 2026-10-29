# 하드웨어·운영체제

하드웨어와 운영체제가 프로그램을 실행하고 자원을 관리하는 원리를 정리합니다.

## 중분류·소분류

굵은 경로는 중분류이며, 그 아래 경로는 해당 주제를 나눈 소분류입니다.

| 경로 | 정리할 내용 |
| --- | --- |
| **[computer-architecture/](computer-architecture/)** | 하드웨어의 구성과 명령 실행 |
| [computer-architecture/instruction-sets/](computer-architecture/instruction-sets/) | 명령어 집합과 프로그래머에게 보이는 하드웨어 모델 |
| [computer-architecture/processor-execution/](computer-architecture/processor-execution/) | 파이프라인, 명령 실행, 병렬 실행 구조 |
| [computer-architecture/memory-hierarchy/](computer-architecture/memory-hierarchy/) | 레지스터·CPU 캐시·주기억장치, 지역성과 캐시 일관성 |
| **[operating-systems/](operating-systems/)** | 운영체제의 구성과 시스템 자원 제어 |
| [operating-systems/kernel-and-system-calls/](operating-systems/kernel-and-system-calls/) | 커널 구조, 사용자·커널 모드, 시스템 콜 |
| [operating-systems/interrupts/](operating-systems/interrupts/) | 인터럽트와 예외 처리 |
| [operating-systems/resource-management/](operating-systems/resource-management/) | 자원 할당, 보호, 사용량 제어의 원리 |
| **[processes-and-threads/](processes-and-threads/)** | 프로그램 실행 단위와 상호작용 |
| [processes-and-threads/lifecycle/](processes-and-threads/lifecycle/) | 프로세스·스레드의 생성, 상태 전이, 종료 |
| [processes-and-threads/scheduling/](processes-and-threads/scheduling/) | 스케줄링과 문맥 교환 |
| [processes-and-threads/inter-process-communication/](processes-and-threads/inter-process-communication/) | 파이프, 공유 메모리 등 프로세스 간 통신 |
| **[memory/](memory/)** | 운영체제의 메모리 관리 |
| [memory/virtual-memory/](memory/virtual-memory/) | 주소 공간, 페이지 테이블, 페이징 |
| [memory/allocation/](memory/allocation/) | 메모리 할당, 회수, 단편화 |
| [memory/memory-mapping/](memory/memory-mapping/) | 메모리 매핑과 파일·주소 공간의 연결 |
| **[concurrency-and-synchronization/](concurrency-and-synchronization/)** | 공유 메모리 환경의 동시 실행과 정확성 |
| [concurrency-and-synchronization/memory-models-and-atomics/](concurrency-and-synchronization/memory-models-and-atomics/) | 가시성, 순서, 원자적 연산 |
| [concurrency-and-synchronization/synchronization-primitives/](concurrency-and-synchronization/synchronization-primitives/) | 락, 세마포어, 조건 변수와 동기화 |
| [concurrency-and-synchronization/nonblocking-algorithms/](concurrency-and-synchronization/nonblocking-algorithms/) | Lock-free·wait-free 알고리즘과 진행 보장 |
| **[io-and-filesystems/](io-and-filesystems/)** | 입출력과 파일 저장의 원리 |
| [io-and-filesystems/io-models/](io-and-filesystems/io-models/) | 블로킹·논블로킹, 동기·비동기 I/O |
| [io-and-filesystems/buffering/](io-and-filesystems/buffering/) | 버퍼, 페이지 캐시, 데이터 복사 |
| [io-and-filesystems/filesystems/](io-and-filesystems/filesystems/) | 파일, 디렉터리, 메타데이터와 파일시스템 구조 |

## 배치 기준

하드웨어·OS의 원리를 다룹니다. 서버 설정과 관리는 인프라에, JVM GC처럼 실행기 고유의 동작은 언어·런타임에 둡니다.

문서는 개념, 문제, 해결 기법과 선택 근거를 중심으로 작성합니다. 구현·실험은 해당 문서 가까이에 두며, 기술별 탐색은 [기술별 목차](../indexes/technologies/)에서 연결합니다.
