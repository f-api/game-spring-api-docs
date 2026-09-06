# 게임 서버 API 문서

Spring 과제에 쓰이는 게임 서버 API 문서를 한곳에서 관리한다. 각 문서는 `openapi.yaml`이 원본이고
`api-docs.html`이 그것을 렌더링한다. `main`에 push 하면 GitHub Pages가 자동으로 갱신한다.

| 과제 | 게임 | API 문서 |
| --- | --- | --- |
| Spring 기본 | [붉은 달의 성채](https://nhahan.github.io/crimson-citadel/) · [에셋 갤러리](https://nhahan.github.io/crimson-citadel/#assets) | [basic/api-docs.html](https://f-api.github.io/game-spring-api-docs/basic/api-docs.html) |
| Spring 숙련 | WebCraft | [expert/api-docs.html](https://f-api.github.io/game-spring-api-docs/expert/api-docs.html) |

## 구조

```
basic/    붉은 달의 성채 저장 서버 API (openapi.yaml, api-docs.html)
expert/   WebCraft 게임 서버 API (openapi.yaml, api-docs.html)
redoc.standalone.js   두 문서가 함께 쓰는 렌더러 (CDN 없이 동작)
index.html            두 문서로 가는 입구
```
