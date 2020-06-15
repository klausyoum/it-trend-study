## 백엔드가 이정도는 해줘야 함 - 6. API 스펙 설계와 문서화 방식 결정
[(1)](https://velog.io/@city7310/%EB%B0%B1%EC%97%94%EB%93%9C%EA%B0%80-%EC%9D%B4%EC%A0%95%EB%8F%84%EB%8A%94-%ED%95%B4%EC%A4%98%EC%95%BC-%ED%95%A8-6.-API-%EC%8A%A4%ED%8E%99-%EC%84%A4%EA%B3%84%EC%99%80-%EB%AC%B8%EC%84%9C%ED%99%94-%EB%B0%A9%EC%8B%9D-%EA%B2%B0%EC%A0%95-1)
[(2)](https://velog.io/@city7310/%EB%B0%B1%EC%97%94%EB%93%9C%EA%B0%80-%EC%9D%B4%EC%A0%95%EB%8F%84%EB%8A%94-%ED%95%B4%EC%A4%98%EC%95%BC-%ED%95%A8-6.-API-%EC%8A%A4%ED%8E%99-%EC%84%A4%EA%B3%84%EC%99%80-%EB%AC%B8%EC%84%9C%ED%99%94-%EB%B0%A9%EC%8B%9D-%EA%B2%B0%EC%A0%95-2)

**@klaus.youm**
- API 문서화 선택지
    - Excel
    - SwaggerHub(Example)
    - 소스코드에 문서 임베딩
    - ReDoc을 직접 관리
    - ReDoc을 GitHub Pages(github.io)에서 관리(Example)
    - Slate를 직접 관리
    - Slate를 GitHub Pages(github.io)에서 관리(Example)
    - GitBook
- 소스 코드와 문서를 분리하여 문서화 작성 방식을 선택. API 문서 수정이 필요할 때마다 어플리케이션 전체를 다시 빌드/배포해야 하므로.
