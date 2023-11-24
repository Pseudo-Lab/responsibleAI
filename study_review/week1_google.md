## Google Responsible AI 리뷰
- 원문 링크 : https://ai.google/responsibility/responsible-ai-practices/
- 번역 자료 : [google responsible AI 번역](../translation/google_responsibleAI.md)
- General recommended practices for AI
    - 시스템 디자인 시에 고려할 사항들에 대한 소개
- 공정성
    - 데이터에 편향이 있다면 ML 모델이 그를 학습하거나 또 증폭시킬 수 있다는 위험 존재
    - 모든 상황이나 문화에 대해 공정한 시스템을 구축하는 것에 대한 어려움
    - 공정성에 대한 표준 정의의 부재, 표준 정의를 세우는 것의 어려움
- 해석 가능성
    - 모델이 이해 가능하다면 Responsible AI에도 도움
    - 그러나 최근 생성 AI는 수백만 또는 수백억 개의 파라미터를 지녀 해석에 어려움 존재
- 프라이버시
    - 개인 정보 보호는 가장 중요한 파트
    - 개인 정보가 모델을 통해 누출되지 않도록 선제적인 조치가 필요
- 안전 및 보안
    - AI 발전에 따라 중요도가 높아지는 주제
    - 적대적 학습에 대한 연구가 진행 중
## 자유 토론
### 주제 1 : 데이터셋
- 구글의 데이터셋 구축 방식에 관심
    - The Data Cards Playbook → 데이터셋 구축 방식 소개, 커뮤니티 기여
- 데이터셋 구축 시 윤리적 이슈 고려?
    - 현재는 구축 자체에 초점, LLM의 영향이 큰듯
    - Hallucination을 줄이는 것이 중요 사안
    - 크롤링 → 최근에는 윤리적 이슈가 되고 문제가 될 수 있다는 것을 인식
    - 기술 발전에 따라 윤리적 이슈 또한 고려되고 있지만 느리게 뒤따르는 느낌 (기술 발전 속도가 빠르기에)
### 주제 2 : 정책 및 심리적 지원
- 구글이 윤리적 문제를 먼저 인지했을 지도(방대한 컨텐츠), 국내 기업의 AI 윤리 정책에 대한 궁금증 생겨, 단23 발표에서 팀네이버 사례 소개
    - 법률적인 규정 또는 기타 정책들이 어떻게 만들어지고 연구되고 있는지 궁금
    - AI 윤리 담당자가 번아웃이 많이 온다는 기사, 각종 혐오 표현 및 사회적, 정치적 편향에 노출되기 때문에 심리적 지원이 필요해 보여
### 주제 3 : 보안 및 이미지 저작권
- 구글의 생성 이미지 워터 마크에 관심
- 이미지를 변형 불가능하게 만드는 기술에 대한 관심
- 딥페이크 및 이미지 저작권 이슈, 예술가들의 데이터 권리 논의