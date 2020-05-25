## Do Not Use MSA - 마이크로서비스 아키텍처가 꼭 필요한가요?
https://www.samsungsds.com/global/ko/support/insights/1211360_2284.html

**@klaus.youm**
- 시장조사업체 가트너의 아키텍처 트렌드를 살펴보면 마이크로서비스 아키텍처는 이미 성숙기에 접어들었음.
- 마이크로서비스 아키텍처의 구현 4단계
- "모놀리식으로 관리하기에 특별히 복잡한 시스템을 운영할 상황이 아니면 마이크로서비스는 고려할 필요조차 없다" by 마틴 파울러
- 마지막으로 마이크로서비스 기반 애플리케이션을 도입하거나 또는 전향을 고민하고 있다면 최소한 아래 사항을 고려 필요
    - 비용: 특정 서비스 아키텍처를 도입할 경우 비용을 얼마나 절감할 수 있는가?
    - 개발 생산성: 마이크로서비스를 요구할 만큼 시스템 복잡도가 높은가? 또는 복잡도를 지나치게 높인 마이크로서비스가 생산성을 저해하고 있지는 않은가?
    - 운영: 개발팀에게 개발과 운영을 동시에 요구할 만큼 인프라가 준비되어 있는가?

## 마이크로 서비스 아키텍처와 개발문화
https://brunch.co.kr/@maengdev/3

**@klaus.youm**
- K8s 상에 Springboot, 스프링 프레임워크를 올리고, MSA를 구현 가능. Spring Cloud(Netflix)를 통해, MSA를 구현
- MSA가 가져올 변화
    1. 개발문화의 변화: 과감한 수정이 전사적 장애를 유발하지 않는 환경, 다양한 시도를 해볼 수 있는 환경
    2. 기술 부채(Technical Debt)의 빠른 청산: 해당 마이크로서비스 만의 기술 부채로 남겨둘 수 있음
    3. Poly glot 프로그래밍: 각 마이크로 서비스 간의 느슨한 결합으로 다양한 환경에서 개발된 서비스들을 통합 가능
    4. 코드레벨이 아닌 인프라와 네트워크 레벨의 대처능력 요구: 이제 개발자는 코드 만의 문제가 아니라 오케스트레이션의 장애에도 대처해야 함

## Moving SOA into Microservices Architecture with Micro Integration Platforms
https://medium.com/microservices-learning/moving-soa-into-msa-with-micro-integration-platforms-d5934bb4c554
