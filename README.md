# StudyLog-Doc

# AlgoWithMe-Doc
알고 있니? 개발 문서

## API 명세

이 프로젝트는 OpenAPI Specification으로 API가 명세되어 있습니다.

해당 스펙은 [dev-dive.github.io/StudyLog/](https://dev-dive.github.io/StudyLog-Doc/)로 Swagger UI를 적용하여 배포되어 있습니다.

해당 링크를 통해 API 명세를 확인할 수 있습니다.


## API Mock Server

이 프로젝트는 OpenAPI Specification으로 API가 명세되어 있습니다. 

따라서 OAS를 활용한 API Mocking이 가능합니다.

### 사용 방법

1. Prism 설치

```shell
npm install -g @stoplight/prism-cli

# OR

yarn global add @stoplight/prism-cli
```

🛠️ 주의 NodeJS 18.16 버전 이상이 필요합니다. [관련 이슈](https://github.com/stoplightio/prism/issues/2305)

2. Mocking

```shell
prism mock -p 8080 https://dev-dive.github.io/StudyLog-Doc/api/root.yaml
```

http://localhost:8080으로 API Mock Server가 배포됩니다.
