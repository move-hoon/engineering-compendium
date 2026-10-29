# AI 원리·시스템·활용

AI의 학습·추론 원리부터 에이전트와 개발 업무 활용까지 정리합니다.

## 중분류·소분류

굵은 경로는 중분류이며, 그 아래 경로는 해당 주제를 나눈 소분류입니다.

| 경로 | 정리할 내용 |
| --- | --- |
| **[machine-learning-fundamentals/](machine-learning-fundamentals/)** | 머신러닝의 학습 문제와 기본 원리 |
| [machine-learning-fundamentals/learning-problems/](machine-learning-fundamentals/learning-problems/) | 지도·비지도 학습 등 문제와 목표의 정의 |
| [machine-learning-fundamentals/optimization/](machine-learning-fundamentals/optimization/) | 손실 함수, 경사 기반 최적화와 학습 과정 |
| [machine-learning-fundamentals/generalization/](machine-learning-fundamentals/generalization/) | 과적합, 정규화와 일반화 |
| **[models-and-architectures/](models-and-architectures/)** | 모델 계열과 구조 |
| [models-and-architectures/classical-machine-learning/](models-and-architectures/classical-machine-learning/) | 선형 모델, 트리와 전통적 ML 모델 |
| [models-and-architectures/neural-networks/](models-and-architectures/neural-networks/) | 신경망의 구성과 표현 학습 |
| [models-and-architectures/transformers/](models-and-architectures/transformers/) | 어텐션과 Transformer 구조 |
| [models-and-architectures/multimodal-models/](models-and-architectures/multimodal-models/) | 텍스트·이미지·음성 등 여러 모달리티의 모델링 |
| **[training-and-adaptation/](training-and-adaptation/)** | 데이터로 모델을 학습·적응시키는 과정 |
| [training-and-adaptation/datasets/](training-and-adaptation/datasets/) | 학습 데이터 구성, 정제와 분할 |
| [training-and-adaptation/pretraining/](training-and-adaptation/pretraining/) | 사전학습 목표와 학습 구성 |
| [training-and-adaptation/fine-tuning/](training-and-adaptation/fine-tuning/) | 미세조정, LoRA 등 모델 적응 기법 |
| **[inference-and-serving/](inference-and-serving/)** | 모델 추론과 서비스 제공 |
| [inference-and-serving/inference-optimization/](inference-and-serving/inference-optimization/) | 양자화, 배칭과 추론 최적화 |
| [inference-and-serving/serving-architecture/](inference-and-serving/serving-architecture/) | 모델 배치, 요청 처리와 서빙 구조 |
| [inference-and-serving/resource-management/](inference-and-serving/resource-management/) | 가속기, 메모리와 KV 캐시 관리 |
| **[prompting-and-context/](prompting-and-context/)** | 모델에 지시와 정보를 제공하는 방법 |
| [prompting-and-context/instruction-design/](prompting-and-context/instruction-design/) | 지시, 예시와 프롬프트 구성 |
| [prompting-and-context/structured-outputs/](prompting-and-context/structured-outputs/) | 출력 형식, 스키마와 검증 |
| [prompting-and-context/context-management/](prompting-and-context/context-management/) | 컨텍스트 선택, 압축과 길이 관리 |
| **[retrieval-augmented-generation/](retrieval-augmented-generation/)** | 외부 정보를 검색해 답변에 연결하는 구성 |
| [retrieval-augmented-generation/ingestion-and-chunking/](retrieval-augmented-generation/ingestion-and-chunking/) | 문서 수집, 분할과 검색 준비 |
| [retrieval-augmented-generation/retrieval-and-reranking/](retrieval-augmented-generation/retrieval-and-reranking/) | 검색 경로, 필터링과 재정렬 |
| [retrieval-augmented-generation/grounded-generation/](retrieval-augmented-generation/grounded-generation/) | 검색 근거를 활용한 생성과 출처 연결 |
| **[agents/](agents/)** | 도구와 상태를 활용해 작업을 수행하는 AI 시스템 |
| [agents/tool-use/](agents/tool-use/) | 도구 인터페이스, 호출과 결과 처리 |
| [agents/planning-and-execution/](agents/planning-and-execution/) | 작업 분해, 실행 루프, 상태와 실행 환경 |
| [agents/memory/](agents/memory/) | 작업 간 정보 저장, 회상과 메모리 관리 |
| [agents/skills/](agents/skills/) | 재사용 가능한 지식·절차·스크립트의 구성과 활용 |
| [agents/multi-agent-systems/](agents/multi-agent-systems/) | 에이전트 간 역할 분담, 통신과 조정 |
| **[evaluation-and-safety/](evaluation-and-safety/)** | AI 시스템의 품질·안전성 검증과 통제 |
| [evaluation-and-safety/quality-evaluation/](evaluation-and-safety/quality-evaluation/) | 평가 데이터, 지표와 회귀 평가 |
| [evaluation-and-safety/robustness-and-security/](evaluation-and-safety/robustness-and-security/) | 환각, 적대적 입력과 프롬프트 인젝션 대응 |
| [evaluation-and-safety/permissions-and-human-oversight/](evaluation-and-safety/permissions-and-human-oversight/) | 권한 경계, 사람의 검토와 개입 설계 |
| **[ai-assisted-engineering/](ai-assisted-engineering/)** | 개발과 업무 흐름에 AI를 적용하는 방법 |
| [ai-assisted-engineering/coding-and-refactoring/](ai-assisted-engineering/coding-and-refactoring/) | 코드 작성, 탐색과 리팩터링 |
| [ai-assisted-engineering/review-and-testing/](ai-assisted-engineering/review-and-testing/) | 코드 리뷰, 테스트 생성과 검증 보조 |
| [ai-assisted-engineering/documentation/](ai-assisted-engineering/documentation/) | 문서 작성, 정리와 지식 탐색 |
| [ai-assisted-engineering/workflow-automation/](ai-assisted-engineering/workflow-automation/) | 여러 작업을 연결하는 AI 활용 워크플로와 AX |

## 배치 기준

AI의 동작과 활용이 중심인 문서를 다룹니다. 일반적인 CI/CD·테스트 자동화는 각각 인프라와 소프트웨어공학에 둡니다.

문서는 개념, 문제, 해결 기법과 선택 근거를 중심으로 작성합니다. 구현·실험은 해당 문서 가까이에 두며, 기술별 탐색은 [기술별 목차](../indexes/technologies/)에서 연결합니다.
