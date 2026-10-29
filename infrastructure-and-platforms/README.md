# 실행 환경·배포

프로그램을 실행할 자원과 환경을 구성하고 제공하는 방법을 정리합니다.

## 중분류·소분류

굵은 경로는 중분류이며, 그 아래 경로는 해당 주제를 나눈 소분류입니다.

| 경로 | 정리할 내용 |
| --- | --- |
| **[system-administration/](system-administration/)** | 호스트와 운영체제의 구성·관리 |
| [system-administration/host-configuration/](system-administration/host-configuration/) | 계정, 권한, 패키지와 시스템 설정 |
| [system-administration/service-management/](system-administration/service-management/) | 서비스 실행, 프로세스 관리와 시스템 서비스 구성 |
| **[compute/](compute/)** | 계산 자원과 실행 환경 제공 |
| [compute/virtual-machines/](compute/virtual-machines/) | 가상화, VM 이미지, 인스턴스와 자원 구성 |
| [compute/serverless-execution/](compute/serverless-execution/) | 함수 실행, 트리거, 동시 실행과 서버리스 환경 |
| **[containers/](containers/)** | 컨테이너의 생성과 실행 환경 |
| [containers/images-and-builds/](containers/images-and-builds/) | Dockerfile, 이미지 레이어와 빌드 |
| [containers/execution-and-isolation/](containers/execution-and-isolation/) | 컨테이너 실행, namespace, cgroup과 자원 제한 |
| [containers/networking/](containers/networking/) | 컨테이너 네트워크와 연결 구성 |
| [containers/storage/](containers/storage/) | 볼륨, 마운트와 컨테이너 데이터 보존 |
| **[orchestration/](orchestration/)** | 워크로드의 배치와 원하는 상태 유지 |
| [orchestration/scheduling-and-placement/](orchestration/scheduling-and-placement/) | 스케줄링, 자원 요청과 배치 조건 |
| [orchestration/reconciliation-and-lifecycle/](orchestration/reconciliation-and-lifecycle/) | 상태 조정, 컨트롤러와 워크로드 생명주기 |
| [orchestration/service-discovery/](orchestration/service-discovery/) | 실행 중인 서비스의 발견과 연결 |
| [orchestration/autoscaling/](orchestration/autoscaling/) | 확장 지표, 정책과 자동 확장 구성 |
| **[networking/](networking/)** | 실행 환경의 네트워크 구성 |
| [networking/virtual-networks/](networking/virtual-networks/) | VPC, 서브넷, 라우팅 테이블과 게이트웨이 |
| [networking/ingress-and-gateways/](networking/ingress-and-gateways/) | 외부 요청의 진입 경로와 라우팅 구성 |
| [networking/service-mesh/](networking/service-mesh/) | 서비스 간 통신을 관리하는 프록시와 정책 구성 |
| **[storage/](storage/)** | 실행 환경에 제공하는 저장 자원 |
| [storage/block-storage/](storage/block-storage/) | 블록 장치, 볼륨, 연결과 스냅샷 구성 |
| [storage/file-storage/](storage/file-storage/) | 공유 파일시스템과 마운트 구성 |
| [storage/object-storage/](storage/object-storage/) | 버킷, 오브젝트와 수명주기 구성 |
| **[infrastructure-as-code/](infrastructure-as-code/)** | 실행 환경을 코드로 정의·관리 |
| [infrastructure-as-code/provisioning/](infrastructure-as-code/provisioning/) | 자원 선언, 모듈과 프로비저닝 |
| [infrastructure-as-code/configuration-management/](infrastructure-as-code/configuration-management/) | 운영체제·서비스의 구성 자동화 |
| [infrastructure-as-code/state-and-drift/](infrastructure-as-code/state-and-drift/) | 상태, 잠금, 실제 환경과 선언의 차이 관리 |
| **[build-and-delivery/](build-and-delivery/)** | 변경을 빌드하고 실행 환경에 전달 |
| [build-and-delivery/build-and-artifacts/](build-and-delivery/build-and-artifacts/) | 빌드, 패키징, 레지스트리와 아티팩트 |
| [build-and-delivery/pipelines/](build-and-delivery/pipelines/) | CI/CD 단계, 실행 조건과 파이프라인 구성 |
| [build-and-delivery/deployment-and-rollback/](build-and-delivery/deployment-and-rollback/) | 롤링·블루그린·카나리 배포와 롤백 |
| **[cloud-platforms/](cloud-platforms/)** | 클라우드 전체의 구성과 자원 관리 체계 |
| [cloud-platforms/accounts-and-organizations/](cloud-platforms/accounts-and-organizations/) | 계정 분리, 조직과 여러 계정의 구성 |
| [cloud-platforms/regions-and-zones/](cloud-platforms/regions-and-zones/) | 리전·가용 영역과 환경 배치 |
| [cloud-platforms/resource-governance/](cloud-platforms/resource-governance/) | 자원 정책, 태그, 한도와 관리 기준 |
| **[platform-engineering/](platform-engineering/)** | 개발자가 공통으로 사용하는 실행·개발 기반 |
| [platform-engineering/developer-environments/](platform-engineering/developer-environments/) | 개발 환경의 구성과 재현 |
| [platform-engineering/self-service-platforms/](platform-engineering/self-service-platforms/) | 개발자 포털과 셀프서비스 환경 제공 |
| [platform-engineering/reusable-platform-capabilities/](platform-engineering/reusable-platform-capabilities/) | 공통 템플릿, 실행 기반과 재사용 기능 |

## 배치 기준

실행 환경의 구성이 중심입니다. DynamoDB의 데이터 모델은 데이터 시스템에, Kafka의 전달 보장은 분산 시스템에 둡니다. 여러 서비스를 조합한 구성은 중심 목적에 맞는 이 영역의 주제에 정리합니다.

문서는 개념, 문제, 해결 기법과 선택 근거를 중심으로 작성합니다. 구현·실험은 해당 문서 가까이에 두며, 기술별 탐색은 [기술별 목차](../indexes/technologies/)에서 연결합니다.
