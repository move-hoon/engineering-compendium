# 통신 원리·프로토콜

네트워크를 통해 데이터를 주고받는 원리와 통신 프로토콜을 정리합니다.

## 중분류·소분류

굵은 경로는 중분류이며, 그 아래 경로는 해당 주제를 나눈 소분류입니다.

| 경로 | 정리할 내용 |
| --- | --- |
| **[network-architecture/](network-architecture/)** | 네트워크의 계층과 연결 구조 |
| [network-architecture/layering-and-encapsulation/](network-architecture/layering-and-encapsulation/) | 계층 모델, 캡슐화와 패킷 구조 |
| [network-architecture/link-layer/](network-architecture/link-layer/) | 프레임, 링크 계층의 주소와 전달 |
| [network-architecture/addressing-and-routing/](network-architecture/addressing-and-routing/) | IP, 서브넷, 라우팅과 NAT |
| **[transport/](transport/)** | 종단 간 데이터 전달 |
| [transport/connection-management/](transport/connection-management/) | 연결 수립·종료, 연결 유지와 연결 풀 |
| [transport/reliable-delivery/](transport/reliable-delivery/) | 손실 복구, 재전송과 전달 신뢰성 |
| [transport/flow-and-congestion-control/](transport/flow-and-congestion-control/) | 수신 측 흐름 제어와 네트워크 혼잡 제어 |
| **[application-protocols/](application-protocols/)** | 애플리케이션 계층의 통신 규약 |
| [application-protocols/http/](application-protocols/http/) | HTTP 메시지, 버전별 동작, 캐싱과 조건부 요청 |
| [application-protocols/dns/](application-protocols/dns/) | 이름 해석, 레코드, 위임과 DNS 캐싱 |
| [application-protocols/websocket/](application-protocols/websocket/) | 연결 수립, 프레임과 양방향 통신 |
| **[rpc-and-serialization/](rpc-and-serialization/)** | 원격 호출과 데이터 교환 형식 |
| [rpc-and-serialization/communication-models/](rpc-and-serialization/communication-models/) | 요청·응답, 스트리밍 등 RPC 통신 모델 |
| [rpc-and-serialization/serialization-formats/](rpc-and-serialization/serialization-formats/) | 직렬화 형식, 인코딩과 메시지 표현 |
| [rpc-and-serialization/schema-evolution/](rpc-and-serialization/schema-evolution/) | 통신 스키마의 변경과 호환성 |
| **[traffic-delivery/](traffic-delivery/)** | 트래픽의 중계·분산·전달 |
| [traffic-delivery/proxies/](traffic-delivery/proxies/) | 정방향·역방향 프록시와 중계 동작 |
| [traffic-delivery/load-balancing/](traffic-delivery/load-balancing/) | 분산 알고리즘과 연결·요청 단위 부하 분산 |
| [traffic-delivery/content-delivery/](traffic-delivery/content-delivery/) | CDN과 콘텐츠 전달 구조 |

## 배치 기준

통신 원리와 프로토콜을 다룹니다. VPC·인그레스 등 실행 환경의 네트워크 구성은 인프라에 정리합니다.

문서는 개념, 문제, 해결 기법과 선택 근거를 중심으로 작성합니다. 구현·실험은 해당 문서 가까이에 두며, 기술별 탐색은 [기술별 목차](../indexes/technologies/)에서 연결합니다.
