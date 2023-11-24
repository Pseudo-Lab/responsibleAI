## AWS Responsible AI 리뷰
- 원문 링크 : https://aws.amazon.com/ko/machine-learning/responsible-ai/
- 번역 자료 : [aws responsible AI 번역](../translation/aws_responsibleAI.md)
- 책임 있는 AI의 핵심 차원
    - 공정성
    - 설명 가능성
    - 개인 정보 보호 및 보안
    - 견고성
    - 거버넌스
    - 투명성
- Services and tools
    - 편향 감지 : [Amazon SageMaker Clarify](https://aws.amazon.com/sagemaker/clarify/)
    - 모델 예측 설명 : [Amazon SageMaker Clarify](https://aws.amazon.com/sagemaker/clarify/)
    - 모니터링 및 인적 검토 : [Amazon SageMaker Model Monitor](https://aws.amazon.com/sagemaker/ml-governance/), [Amazon Augmented AI](https://aws.amazon.com/augmented-ai/)
    - 거버넌스 개선 : [ML Governance from Amazon SageMaker](https://aws.amazon.com/sagemaker/ml-governance/)
    - 책임감 있게 생성 AI 구축 : [Amazon CodeWhisperer](https://aws.amazon.com/codewhisperer/), [Amazon Titan](https://aws.amazon.com/bedrock/titan/)

## 자유 토론
### 주제 1 : AWS Responsible AI 리뷰
- In General
    - 머신러닝에 치중된 느낌이 있다. Azure의 Responsible AI와 유사하다.
    - End-to-End AI Lifecycle에 Responsible AI를 통합한다는 내용이 인상적.
    - AI 교육에도 열심인 것 같다. 내외부의 교육 활동이 활발하고 이를 잘 알리고 있다.
- Services and tools
    - 기업들이 자사의 사업 방향성과 맞게 Responsible AI 관행을 실시한다는 느낌을 받는다.
    - 저번 Meta에서는 광고나 피드 관련된 내용이 많았던 것처럼 AWS는 클라우드 컴퓨팅 서비스와 툴, 머신 러닝에 대한 내용이 눈에 띈다.
    - AI 모델에 관련된 설명이 담긴 AI 서비스 카드를 제공하는데 이러한 모델 및 사용에 대한 설명을 제공하는 것이 요즘의 관례인 것 같다.
## 주제 2 : 오픈 소스
- 관련 뉴스 1. 현대 AI 주춧돌 '오픈소스' 기술·문화… 미래 AI 품질·윤리 다진다 : https://www.ajunews.com/view/20230929093301810
- 파운데이션 모델도 윤리 및 책임을 고려해야 한다.
- 오픈 소스를 무분별하게 사용? → Model Card나 라이센스 등을 제공하여 가이드라인을 제시하고 있다. 하지만 관리 감독은 또 다른 문제이다.
- 오픈 소스 페이지에서부터 윤리적 측면이 고려된다면 좋을 것 같다.
## 주제 3 : 핀란드 교도소 수감자 대상 데이터 라벨링
- 관련 뉴스 1. These Prisoners Are Training AI : https://www.wired.com/story/prisoners-training-ai-finland/
- 인력 활용 방안? 재소자의 용역 활동의 일환?
- 처음에는 인력 활용 측면에서 좋은 방안이라 생각했다. 하지만 이후 노동력 보다는 수감자의 교화에 포커스가 맞춰져야 하는 것이 아닌가하는 생각이 들었다.
## 주제 4 : 개인 정보 및 컨텐츠 제공 동의
- 관련 링크 1. AI 윤리 레터, 오픈AI 크롤러가 내민 딜레마 : https://ai-ethics.stibee.com/p/23/
- 서비스를 이용하기 위해 또 컨텐츠가 검색되기 위해 정보 제공 동의가 필요
- 개인 정보나 컨텐츠가 볼모로 잡힌다는 느낌이 있다. 지금은 그래도 개인의 선택에 달린 느낌이지만 추후에 서비스 이용 외에 다른 선택지가 없게 되는 때가 올까 걱정된다.
---
- 추가 자료 1 : 책임 있는 AI 거버넌스 프레임워크 구축을 위한 내부자 가이드
    - 관련 링크 1. Equal AI : [https://www.equalai.org](https://www.equalai.org/)
    - 관련 뉴스 2. “인간과 기업에 유익한 ‘책임있는 AI’” 원칙 눈길 : https://www.apple-economy.com/news/articleView.html?idxno=72003
    - AI 시스템을 채택, 개발, 사용 및 구현하는 모든 규모, 부문 또는 성숙도의 조직을 위한 리소스, 내외부의 약속을 통해 책임감 있게 사용
- 추가 자료 2 : 디지털 권리 장전
    - 관련 링크 1. 디지털 공동번영사회의 가치와 원칙에 관한 헌장 - 디지털 권리장전 : https://eiec.kdi.re.kr/policy/materialView.do?num=243174
    - 과학기술정보통신부가 23.9.25.(월) 국무회의에서 「디지털 권리장전」을 보고하고 전체 내용을 공개
    - ▲자유와 권리 보장, ▲공정한 접근과 기회의 균등, ▲안전과 신뢰의 확보, ▲디지털 혁신의 촉진, ▲인류 후생의 증진 등 28개조가 담긴 본문으로 구성