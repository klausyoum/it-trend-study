## 서버 사이드 테스트 자동화 여정 – 1. 테스트 자동화를 시작한 계기와 그 첫 발걸음
https://engineering.linecorp.com/ko/blog/server-side-test-automation-journey-1/

**@klaus.youm**
- 테스트는 경우에 따라 단순히 기능의 동작을 확인하는 수준을 넘어 지속적으로 서비스의 품질을 측정하고 개선하기 위한 데이터로 활용
- 지금 당장 시작할 수 있는 테스트 자동화 활동 찾기
    - 단위 테스트 실행 자동화 및 결과 확인 방법 개선하기
    - 설정 테스트 추가 및 자동화하기
    - 연계 컴포넌트 상태 확인 테스트 자동화 및 확인 방법 개선하기
    - 성능 테스트 자동화하기
        - ![Test automation of LINE Media Platform](https://engineering-org.line-apps.com/ko/testauto1-7/)
    - 피드백을 좀 더 빨리 전달하기
- 2편에서 'Docker를 활용하여 통합 테스트(integration test) 수준의 회귀 테스트(regression test) 환경을 구축한 사례를 소개' 예정임.

## 서버스펙을 사용한 도커 이미지 테스트 자동화 - RSpec 기반 인프라스트럭처 테스트 프레임워크
https://www.44bits.io/ko/post/automating-docker-image-test-using-server-spec

**@klaus.youm**
- Serverspec은 원래 SSH를 사용해 구성 관리 도구와 함께 사용을 목적으로 만들어진 도구
- 단순히 기존 서버 환경 뿐만 아니라, 빌드를 통해 완성된 이미지를 구성하는 도커와 같은 컨테이너 시스템을 테스트 가능
- Chef Inspec도 널리 알려진 오픈소스 툴임.
