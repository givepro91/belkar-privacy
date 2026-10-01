# belkar-privacy

[**벨카르: 검은 사냥꾼**](https://apps.apple.com/kr/app/id6815152175)의 공개 문서 사이트다. 개인정보 처리방침과 지원 페이지, 프레스 키트, 앱 안 업데이트 확인용 버전 파일을 올려 둔다. 게임 소스는 여기 없다.

GitHub Pages 로 `https://givepro91.github.io/belkar-privacy/` 에 배포된다.

| 경로 | 쓰임 |
|---|---|
| `index.html` | 개인정보 처리방침 (한국어 / English) |
| `support.html` | 고객 지원 · 문의 |
| `press/` | 프레스 키트 (en + ko) |
| `version.json` | 앱이 읽는 최신 버전 (`latest`) 과 필수 업데이트 기준 (`min`) |
| `assets/` | 아이콘 · 스크린샷 · 그래픽 |

## version.json

앱은 실행할 때 이 파일을 읽어 업데이트 안내를 띄운다. iOS 는 App Store 조회를 먼저 쓰고, 그 밖의 플랫폼이 이 파일을 본다. `min` 보다 낮은 버전은 필수 업데이트로 막는다.

```json
{ "latest": "0.3.2", "min": "0.1.0" }
```

출시할 때 `latest` 를 올린다.

## 게임

가로형 2D 픽셀 액션 로그라이트. Unity, Android 와 iOS. 2026-09-28 App Store 출시(174개국).

- App Store — https://apps.apple.com/kr/app/id6815152175
- 개발 영상 — [@givepro_dev](https://www.youtube.com/@givepro_dev)
- 만든 사람 — [장근식 (@givepro91)](https://github.com/givepro91)
