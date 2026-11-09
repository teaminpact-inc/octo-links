# octo-links
octo.teaminpact.com - invite links &amp; app link association files

## 파일

- `.well-known/apple-app-site-association` — iOS 유니버설 링크. appID `N7NLN3LS82.com.teaminpact.octopus`, 경로 `/i/*`.
- `.well-known/assetlinks.json` — Android 앱 링크. 패키지 `com.teaminpact.octopus`. 지문 순서: ① 업로드 키(`octo_upload`, 2026-11-06 생성), ② 개발 Mac의 debug 키. **Play 앱 서명 키 SHA-256**(Play Console › 앱 무결성)은 Play 배포 전에 추가해야 Play에서 받은 앱의 링크가 검증된다.
- `404.html` — 앱이 없을 때 `/i/<코드>`를 열면 초대 코드와 스토어 버튼을 보여준다.

앱 쪽 설정은 octopus 저장소 `docs/product/backend.md` "초대 링크" 절.
