# 저장·조회·처리

데이터를 모델링하고 저장·조회·변환하는 원리와 설계 방법을 정리합니다.

## 중분류·소분류

굵은 경로는 중분류이며, 그 아래 경로는 해당 주제를 나눈 소분류입니다.

| 경로 | 정리할 내용 |
| --- | --- |
| **[data-modeling/](data-modeling/)** | 데이터 구조와 접근 요구에 맞춘 모델 설계 |
| [data-modeling/relational-modeling/](data-modeling/relational-modeling/) | 관계형 모델, 정규화와 관계 설계 |
| [data-modeling/document-and-key-value-modeling/](data-modeling/document-and-key-value-modeling/) | 문서·키값 모델과 접근 패턴에 따른 설계 |
| [data-modeling/graph-modeling/](data-modeling/graph-modeling/) | 노드, 관계와 그래프 데이터 모델 |
| [data-modeling/schema-evolution/](data-modeling/schema-evolution/) | 저장 데이터의 스키마 변경과 마이그레이션 |
| **[databases/](databases/)** | 데이터베이스의 내부 기능과 동작 |
| [databases/storage-engines/](databases/storage-engines/) | 페이지, 버퍼 풀, WAL, B+Tree, LSM Tree와 영속성 |
| [databases/indexing/](databases/indexing/) | 인덱스 구조, 선택도와 접근 경로 |
| [databases/query-processing/](databases/query-processing/) | SQL, 조인, 옵티마이저와 실행 계획 |
| [databases/transactions-and-concurrency-control/](databases/transactions-and-concurrency-control/) | ACID, 격리 수준, MVCC와 잠금 |
| **[caching/](caching/)** | 캐시의 배치·정책·정확성과 장애 대응 |
| [caching/topologies/](caching/topologies/) | 로컬·공유·다단계 캐시의 배치와 선택 기준 |
| [caching/access-patterns/](caching/access-patterns/) | Cache-aside, read-through, write-through 등 읽기·쓰기 패턴 |
| [caching/admission-and-eviction/](caching/admission-and-eviction/) | 캐시 진입, LRU·LFU·TinyLFU 등 정책과 선택 기준 |
| [caching/expiration-and-refresh/](caching/expiration-and-refresh/) | TTL, 만료 시각 분산, 사전 갱신과 갱신 정책 |
| [caching/invalidation-and-consistency/](caching/invalidation-and-consistency/) | 변경 전파, 무효화 순서와 원본·캐시 간 일관성 |
| [caching/failure-patterns/](caching/failure-patterns/) | 스탬피드, 핫 키, 캐시 장애와 대응 전략 |
| **[search-and-retrieval/](search-and-retrieval/)** | 저장된 정보의 색인과 검색 |
| [search-and-retrieval/full-text-search/](search-and-retrieval/full-text-search/) | 역색인, 텍스트 분석과 전문 검색 |
| [search-and-retrieval/vector-search/](search-and-retrieval/vector-search/) | 벡터 인덱스, 유사도와 근사 최근접 탐색 |
| [search-and-retrieval/ranking-and-relevance/](search-and-retrieval/ranking-and-relevance/) | 검색 순위, 관련성 평가와 개선 |
| **[data-processing/](data-processing/)** | 데이터 수집·변환·집계 |
| [data-processing/batch/](data-processing/batch/) | 유한한 데이터 집합의 배치 처리 |
| [data-processing/streaming/](data-processing/streaming/) | 이벤트 시간, 윈도우, 상태와 스트림 집계 |
| [data-processing/data-integration/](data-processing/data-integration/) | ETL·ELT, CDC와 시스템 간 데이터 연계 |
| **[analytical-systems/](analytical-systems/)** | 분석을 위한 모델과 시스템 |
| [analytical-systems/analytical-modeling/](analytical-systems/analytical-modeling/) | 분석 목적의 데이터 모델과 집계 구조 |
| [analytical-systems/analytical-query-processing/](analytical-systems/analytical-query-processing/) | OLAP, 컬럼 기반 실행과 분석 쿼리 처리 |
| [analytical-systems/warehouses-and-lakes/](analytical-systems/warehouses-and-lakes/) | 웨어하우스, 데이터 레이크와 저장·분석 구성 |

## 배치 기준

문제와 해결 방법이 본문의 중심입니다. Redis·DynamoDB 등 구현 기술에 관한 글도 다루는 주제에 배치하고, 기술별 목차에서 연결합니다.

문서는 개념, 문제, 해결 기법과 선택 근거를 중심으로 작성합니다. 구현·실험은 해당 문서 가까이에 두며, 기술별 탐색은 [기술별 목차](../indexes/technologies/)에서 연결합니다.
