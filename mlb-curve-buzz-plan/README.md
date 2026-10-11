# MLB 26FW 커브패딩 버즈 플랜

정적 페이지입니다. `index.html`과 `refs/` 폴더를 같은 위치에 두면 그대로 열립니다.

## GitHub Pages로 링크 만들기
1. GitHub에서 새 저장소를 만듭니다 (예: `mlb-curve-buzz-plan`).
2. 이 폴더 안의 파일 전부(`index.html`, `refs/`, `.nojekyll`, `README.md`)를 저장소 최상단에 업로드합니다.
3. 저장소 **Settings → Pages → Build and deployment**에서 Source를 `Deploy from a branch`, Branch를 `main` / `/(root)`로 저장합니다.
4. 1–2분 뒤 `https://<계정명>.github.io/mlb-curve-buzz-plan/` 주소로 열립니다.

## 주의
- 사내 데이터(매출·내부 보고 수치)가 들어 있습니다. 공개 저장소에 올리면 링크를 모르는 사람도 검색으로 찾을 수 있으니, 공개 범위를 꼭 확인하세요. (`noindex` 태그는 넣어 두었지만 접근 자체를 막지는 못합니다.)
- 무료 GitHub Pages는 **공개 저장소**에서만 동작합니다. 비공개로 운영하려면 GitHub Enterprise/Pro의 Private Pages나 사내 호스팅을 써야 합니다.
- 영상·이미지는 `refs/` 폴더에 있습니다. 폴더 이름을 바꾸면 깨집니다.
