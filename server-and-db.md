## 그래프 데이터베이스 기술 동향 및 적용 사례
https://www.itfind.or.kr/publication/regular/weeklytrend/pastList/read.do?selectedId=1115&selectedCategory=B_ITA_01&pageSize=10&pageIndex=1

**@klaus.youm**
- 과거에는 데이터 통계 분석을 통한 객관적인 정보 파악만으로 충분한 가치가 있었음 -> 현재는 효과적인 시각화와 데이터 간의 관계를 분석하여 숨겨진 의미를 찾고, 미래를 예측하고 대안을 제시할 수 있는 시스템이 요구
- Graph Database
    - 데이터를 실시간으로 저장, 운영, 처리하여 최선의 데이터 운영 환경을 마련하기 위한 기술을 구현한 솔루션. 데이터 간의 관계 중심으로 표현 및 처리가 중요한 모든 업무에 활용 가능.
        - **Graph Storage**: 데이터를 저장하기 위한 저장소
        - **Graph Processing Engine**: 그래프 데이터를 실시간 처리하기 위한 그래프 프로세싱 엔진
        - **Graph Query Language**: 그래프 데이터를 효율적으로 저장하고 처리하기 위해 지원되는 쿼리 언어
    - GDB의 장점  
        - 스키마가 없는 구조(Schema-less): 새로운 속성 값을 가지 노드가 추가될 수 있고, 새롭게 입력된 데이터를 다른 데이터들과 연결해주는 것만으로도 작업을 끝낼 수 있음.
        - 질의 처리 속도: RDB는 조인이 늘어날수록 부담이 증가. GDB는 데이터 간의 관계들을 따라 조회하여 부담없는 처리가 가능.
        - 직관적인 모델링: RDB는 현실 모형을 테이블 형태에 맞추는 과정을 통해, 데이터의 직관성을 떨어뜨림.
    - 적용 사례: Personalized Eucation Service, Performance Management System
    - GDB의 시장
        - 가트너에서 2019년 10대 데이터 분석 기술 트렌드에 '그래프' 데이터 분석이 포함.
        - 2022년까지 GDB 시장이 연간 100% 성장 예상.
        - GDB는 AI와 ML이 통합된 Knowledge Grapsh로 많이 활용.
    - 비트나인: 대한민국의 그래프 데이터베이스 연구개발 전문 기업, https://bitnine.tistory.com/
    
