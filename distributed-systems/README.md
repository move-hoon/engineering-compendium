# 노드 간 협력·정확성

여러 노드가 통신 지연과 부분 장애 속에서 협력하는 원리와 설계 방법을 정리합니다.

## 중분류·소분류

굵은 경로는 중분류이며, 그 아래 경로는 해당 주제를 나눈 소분류입니다.

| 경로 | 정리할 내용 |
| --- | --- |
| **[system-models-and-failures/](system-models-and-failures/)** | 분산 시스템의 가정과 장애 |
| [system-models-and-failures/timing-and-failure-models/](system-models-and-failures/timing-and-failure-models/) | 동기·비동기 모델, 부분 장애와 네트워크 분할 |
| [system-models-and-failures/failure-detection/](system-models-and-failures/failure-detection/) | 장애 의심, 감지와 오탐의 한계 |
| **[time-and-ordering/](time-and-ordering/)** | 시간과 사건의 선후 관계 |
| [time-and-ordering/physical-clocks/](time-and-ordering/physical-clocks/) | 물리 시계, 시계 오차와 동기화 |
| [time-and-ordering/logical-clocks-and-causality/](time-and-ordering/logical-clocks-and-causality/) | 논리 시계, 인과관계와 이벤트 순서 |
| **[consistency/](consistency/)** | 여러 노드에서 관측하는 데이터의 의미 |
| [consistency/consistency-models/](consistency/consistency-models/) | 선형화 가능성, 순차·인과·최종 일관성 등 모델 |
| [consistency/consistency-verification/](consistency/consistency-verification/) | 실행 이력과 일관성 보장의 검증 |
| **[replication/](replication/)** | 데이터 복제와 사본 간 협력 |
| [replication/replication-topologies/](replication/replication-topologies/) | 리더 기반·다중 리더·리더리스 복제 구조 |
| [replication/quorum-mechanisms/](replication/quorum-mechanisms/) | 읽기·쓰기 쿼럼과 보장 조건 |
| [replication/conflict-resolution/](replication/conflict-resolution/) | 버전, 충돌 감지와 해결 |
| **[partitioning/](partitioning/)** | 데이터와 부하의 분산 |
| [partitioning/partitioning-strategies/](partitioning/partitioning-strategies/) | 범위·해시 분할과 일관된 해싱 |
| [partitioning/rebalancing/](partitioning/rebalancing/) | 파티션 이동, 재분배와 확장 |
| **[consensus-and-coordination/](consensus-and-coordination/)** | 노드 간 의사결정과 작업 조정 |
| [consensus-and-coordination/consensus-algorithms/](consensus-and-coordination/consensus-algorithms/) | 합의 문제와 합의 알고리즘 |
| [consensus-and-coordination/leader-election/](consensus-and-coordination/leader-election/) | 리더 선출과 리더 변경 |
| [consensus-and-coordination/locks-and-leases/](consensus-and-coordination/locks-and-leases/) | 분산 락, 리스와 fencing token |
| **[messaging/](messaging/)** | 메시지 전달과 처리의 보장 |
| [messaging/communication-patterns/](messaging/communication-patterns/) | 큐, 발행·구독과 메시징 구조 |
| [messaging/delivery-semantics/](messaging/delivery-semantics/) | 전달 보장의 의미와 적용 범위 |
| [messaging/ordering/](messaging/ordering/) | 전체·파티션·키 단위 순서 보장 |
| [messaging/deduplication-and-idempotency/](messaging/deduplication-and-idempotency/) | 중복 식별과 멱등 처리 |
| **[distributed-transactions/](distributed-transactions/)** | 여러 참여자의 변경을 조정하는 방법 |
| [distributed-transactions/atomic-commit/](distributed-transactions/atomic-commit/) | 2PC 등 원자적 커밋 프로토콜 |
| [distributed-transactions/sagas-and-compensation/](distributed-transactions/sagas-and-compensation/) | Saga, 보상과 실패 처리 |
| [distributed-transactions/transactional-messaging/](distributed-transactions/transactional-messaging/) | Transactional Outbox 등 데이터 변경·메시지 발행 연계 |

## 배치 기준

여러 노드의 협력과 정확성을 다룹니다. Kafka에 관한 글은 해당 전달·순서·복제 주제에 두고 기술별 목차에서 모읍니다. 스트림 변환·집계는 데이터 시스템에 정리합니다.

문서는 개념, 문제, 해결 기법과 선택 근거를 중심으로 작성합니다. 구현·실험은 해당 문서 가까이에 두며, 기술별 탐색은 [기술별 목차](../indexes/technologies/)에서 연결합니다.
