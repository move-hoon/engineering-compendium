# 보호·위협 대응

시스템과 데이터를 보호하는 원리, 위협과 대응 방법을 정리합니다.

## 중분류·소분류

굵은 경로는 중분류이며, 그 아래 경로는 해당 주제를 나눈 소분류입니다.

| 경로 | 정리할 내용 |
| --- | --- |
| **[security-foundations/](security-foundations/)** | 보안 문제를 파악하고 설계하는 기초 |
| [security-foundations/threat-modeling/](security-foundations/threat-modeling/) | 공격자, 자산, 신뢰 경계와 위협 분석 |
| [security-foundations/security-principles/](security-foundations/security-principles/) | 최소 권한, 심층 방어와 안전한 기본값 |
| **[cryptography/](cryptography/)** | 데이터의 기밀성·무결성·진위 보호 |
| [cryptography/encryption/](cryptography/encryption/) | 대칭·비대칭 암호와 암호화 방식 |
| [cryptography/hashing-and-authentication-codes/](cryptography/hashing-and-authentication-codes/) | 해시와 메시지 인증 코드 |
| [cryptography/digital-signatures/](cryptography/digital-signatures/) | 전자서명, 검증과 인증서 |
| [cryptography/key-management/](cryptography/key-management/) | 키 생성, 보관, 교체와 폐기 |
| **[authentication/](authentication/)** | 사용자와 시스템의 신원 확인 |
| [authentication/credentials-and-factors/](authentication/credentials-and-factors/) | 비밀번호, MFA, 패스키와 인증 요소 |
| [authentication/sessions/](authentication/sessions/) | 로그인 상태, 세션 수명과 폐기 |
| [authentication/identity-federation/](authentication/identity-federation/) | OIDC 등 외부 신원 제공자와의 인증 연계 |
| **[authorization/](authorization/)** | 허용할 행위와 접근 범위의 결정 |
| [authorization/access-control-models/](authorization/access-control-models/) | RBAC, ABAC와 정책 평가 |
| [authorization/delegation/](authorization/delegation/) | OAuth 등 권한 위임과 범위 제한 |
| **[application-security/](application-security/)** | 애플리케이션의 취약점과 안전한 구현 |
| [application-security/vulnerabilities-and-mitigations/](application-security/vulnerabilities-and-mitigations/) | 인젝션, XSS, CSRF, SSRF와 대응 |
| [application-security/secure-development/](application-security/secure-development/) | 입력 검증, 안전한 구현과 보안 검토 |
| **[infrastructure-security/](infrastructure-security/)** | 실행 환경과 시스템 간 접근 보호 |
| [infrastructure-security/network-protection/](infrastructure-security/network-protection/) | 네트워크 격리와 접근 통제 |
| [infrastructure-security/workload-security/](infrastructure-security/workload-security/) | 워크로드 신원과 실행 환경 보호 |
| [infrastructure-security/secrets-management/](infrastructure-security/secrets-management/) | 비밀정보 보관, 전달과 교체 |
| **[software-supply-chain-security/](software-supply-chain-security/)** | 의존성과 빌드·배포 경로의 신뢰 |
| [software-supply-chain-security/dependency-security/](software-supply-chain-security/dependency-security/) | 의존성 검증, 취약점과 SBOM |
| [software-supply-chain-security/build-integrity-and-provenance/](software-supply-chain-security/build-integrity-and-provenance/) | 빌드 출처, 서명과 무결성 검증 |
| **[privacy-and-data-protection/](privacy-and-data-protection/)** | 개인정보 처리와 노출 최소화 |
| [privacy-and-data-protection/data-minimization/](privacy-and-data-protection/data-minimization/) | 수집·사용 범위와 데이터 최소화 |
| [privacy-and-data-protection/de-identification/](privacy-and-data-protection/de-identification/) | 마스킹, 가명화와 비식별화의 한계 |
| [privacy-and-data-protection/retention-and-deletion/](privacy-and-data-protection/retention-and-deletion/) | 보존 기간, 삭제와 데이터 수명 관리 |

## 배치 기준

보호 원리와 위협 대응이 중심이면 여기에 둡니다. 특정 기술의 설명이 중심인 문서와는 링크로 연결합니다.

문서는 개념, 문제, 해결 기법과 선택 근거를 중심으로 작성합니다. 구현·실험은 해당 문서 가까이에 두며, 기술별 탐색은 [기술별 목차](../indexes/technologies/)에서 연결합니다.
