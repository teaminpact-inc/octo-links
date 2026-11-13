# octo-links
octo.teaminpact.com - invite links &amp; app link association files

## 파일

- `.well-known/apple-app-site-association` — iOS 유니버설 링크. appID `N7NLN3LS82.com.teaminpact.octopus`, 경로 `/i/*`(초대 링크) · `/c/*`(옥토 코드 QR).
- `.well-known/assetlinks.json` — Android 앱 링크. 패키지 `com.teaminpact.octopus`. 지문 순서: ① Play 앱 서명 키(Play Console › 앱 무결성, Play에서 받은 앱), ② 업로드 키(`octo_upload`, 2026-11-06 생성), ③ 개발 Mac의 debug 키.
- `404.html` — `/i/<토큰>`(초대 링크) · `/c/<코드>`(옥토 코드 QR) 안내. "앱에서 열기"(Android intent · iOS `octopus://`)와 스토어 버튼, 카카오톡 같은 앱 안 브라우저에선 앱 열기를 한 번 자동 시도.

앱 쪽 설정은 octopus 저장소 `docs/product/backend.md` "초대 링크" 절.
