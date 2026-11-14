# 3D Annie — GitHub Pages 앱

## GitHub에 올리기
1. GitHub에서 새 저장소(repository)를 만듭니다.
2. 이 폴더 안의 파일과 `icons` 폴더를 저장소 최상위(root)에 업로드합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Deploy from a branch**를 선택합니다.
5. Branch는 `main`, 폴더는 `/(root)`로 선택하고 Save를 누릅니다.
6. 잠시 후 표시되는 `https://사용자이름.github.io/저장소이름/` 주소로 접속합니다.

## 아이폰에 설치
1. Safari에서 GitHub Pages 주소를 엽니다.
2. 공유 버튼을 누릅니다.
3. **홈 화면에 추가**를 선택합니다.
4. 추가한 Annie 아이콘으로 실행합니다.

## 안드로이드에 설치
Chrome에서 배포 주소를 연 뒤 메뉴(⋮)에서 **앱 설치** 또는 **홈 화면에 추가**를 선택합니다.

## 참고
- HTTPS로 배포되어야 서비스 워커와 PWA 설치 기능이 정상 작동합니다.
- Spotify 계정 연동은 Spotify 개발자 대시보드의 Redirect URI에 실제 GitHub Pages 주소를 등록해야 합니다.
- 외부 CDN 및 Spotify 서비스는 인터넷 연결이 필요합니다.
- 이 구성은 설치형 웹앱(PWA)이며 App Store/Play Store 네이티브 앱은 아닙니다.
