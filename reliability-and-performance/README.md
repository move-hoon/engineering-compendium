# 측정·진단·운영

시스템 상태와 성능을 측정하고 장애를 예방·진단·복구하는 방법을 정리합니다.

## 중분류·소분류

굵은 경로는 중분류이며, 그 아래 경로는 해당 주제를 나눈 소분류입니다.

| 경로 | 정리할 내용 |
| --- | --- |
| **[observability/](observability/)** | 시스템 상태를 관측하기 위한 신호와 계측 |
| [observability/logging/](observability/logging/) | 구조화 로그, 수집, 검색과 상관관계 |
| [observability/metrics/](observability/metrics/) | 계측, 시계열, 집계와 대시보드 |
| [observability/tracing/](observability/tracing/) | 스팬, 분산 추적, 컨텍스트 전파와 샘플링 |
| **[service-level-management/](service-level-management/)** | 서비스 품질의 목표와 운영 판단 |
| [service-level-management/indicators-and-objectives/](service-level-management/indicators-and-objectives/) | SLI와 SLO의 정의·측정 |
| [service-level-management/error-budgets/](service-level-management/error-budgets/) | 에러 버짓과 운영·변경 정책 |
| [service-level-management/alerting/](service-level-management/alerting/) | 실행 가능한 알림과 경보 설계 |
| **[performance-analysis/](performance-analysis/)** | 성능을 측정하고 병목을 찾는 방법 |
| [performance-analysis/measurement/](performance-analysis/measurement/) | 지연시간, 처리량, 백분위수와 측정 오류 |
| [performance-analysis/profiling/](performance-analysis/profiling/) | CPU, 메모리, 할당과 실행 프로파일링 |
| [performance-analysis/bottleneck-analysis/](performance-analysis/bottleneck-analysis/) | 자원·대기·여러 계층을 추적하는 병목 진단 |
| **[load-testing-and-benchmarking/](load-testing-and-benchmarking/)** | 부하를 재현하고 성능을 비교하는 실험 |
| [load-testing-and-benchmarking/workload-modeling/](load-testing-and-benchmarking/workload-modeling/) | 트래픽, 동시성, 도착률과 부하 시나리오 |
| [load-testing-and-benchmarking/test-execution/](load-testing-and-benchmarking/test-execution/) | 부하·스트레스·장시간 테스트의 실행과 통제 |
| [load-testing-and-benchmarking/result-analysis/](load-testing-and-benchmarking/result-analysis/) | 결과 해석, 비교 조건과 재현성 |
| **[capacity-and-efficiency/](capacity-and-efficiency/)** | 요구 부하를 수용할 자원과 비용의 판단 |
| [capacity-and-efficiency/capacity-planning/](capacity-and-efficiency/capacity-planning/) | 용량 산정, 포화도와 성장 예측 |
| [capacity-and-efficiency/queueing-models/](capacity-and-efficiency/queueing-models/) | 도착률, 대기열, 처리율과 지연의 관계 |
| [capacity-and-efficiency/resource-and-cost-efficiency/](capacity-and-efficiency/resource-and-cost-efficiency/) | 자원 활용률, 적정 용량과 비용 분석 |
| **[resilience/](resilience/)** | 실패와 부하 집중의 영향을 제한하는 기법 |
| [resilience/timeouts/](resilience/timeouts/) | 대기 시간 제한, 시간 예산과 취소 |
| [resilience/retries-and-backoff/](resilience/retries-and-backoff/) | 재시도 조건, 횟수, 간격과 부하 증폭 방지 |
| [resilience/jitter/](resilience/jitter/) | 실행·재시도·갱신 시점을 분산하는 무작위화 원리 |
| [resilience/circuit-breakers/](resilience/circuit-breakers/) | 실패 감지, 호출 차단과 복구 탐색 |
| [resilience/bulkheads/](resilience/bulkheads/) | 자원·동시성 격리를 통한 장애 확산 제한 |
| [resilience/load-shedding/](resilience/load-shedding/) | 과부하 시 요청 거절과 우선순위 처리 |
| **[incident-management/](incident-management/)** | 장애 발생 시 진단과 대응 |
| [incident-management/diagnosis-and-response/](incident-management/diagnosis-and-response/) | 상황 판단, 대응 절차와 복구 조치 |
| [incident-management/postmortems/](incident-management/postmortems/) | 원인 분석, 영향 정리와 재발 방지 |
| **[disaster-recovery/](disaster-recovery/)** | 큰 장애에 대비한 복구 준비와 검증 |
| [disaster-recovery/recovery-planning/](disaster-recovery/recovery-planning/) | RPO·RTO, 복구 범위와 절차 |
| [disaster-recovery/backup-and-restoration/](disaster-recovery/backup-and-restoration/) | 백업 전략과 복원 방법 |
| [disaster-recovery/recovery-testing/](disaster-recovery/recovery-testing/) | 복구 훈련과 복원 가능성 검증 |

## 배치 기준

여러 기술에 적용되는 측정·운영·복원 기법을 다룹니다. 캐시 스탬피드와 TTL jitter의 구체적 적용은 캐싱에 두고, jitter의 공통 원리와 연결합니다.

문서는 개념, 문제, 해결 기법과 선택 근거를 중심으로 작성합니다. 구현·실험은 해당 문서 가까이에 두며, 기술별 탐색은 [기술별 목차](../indexes/technologies/)에서 연결합니다.
