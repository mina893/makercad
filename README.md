# MakerCAD 홈페이지

학교·학원을 위한 교육용 3D CAD 프로그램 **MakerCAD** 소개 페이지입니다.

## 구성
- `index.html` : 메인 페이지
- `styles.css` : 디자인 (반응형)
- `script.js` : 모바일 메뉴 / 스크롤 애니메이션
- `assets/` : 이미지
- `.nojekyll` : GitHub Pages 설정 파일 (지우지 마세요)

## GitHub Pages 올리는 방법
1. GitHub에서 새 저장소(Repository)를 만듭니다. (Public)
2. 저장소 화면에서 **Add file → Upload files**를 누릅니다.
3. 압축을 푼 파일·폴더를 **모두** 끌어다 놓고 **Commit changes**를 누릅니다.
   - `index.html`이 저장소 맨 위(루트)에 있어야 합니다.
4. **Settings → Pages**에서 Source `Deploy from a branch`, Branch `main` / `(root)` 선택 후 Save.
5. 1~2분 뒤 `https://아이디.github.io/저장소이름/` 으로 접속됩니다.

## 수정 포인트
- 전화번호: `index.html`에서 `070-7123-9081` 검색
- 사이트 주소: `index.html`에서 `wisecoding.kr` 검색
- 가격: `id="pricing"` 영역

## 로고 파일
- `assets/makercad-logo-horizontal.png` : 상단 메뉴·하단 푸터용 가로형 로고 (배경 투명)
- `assets/makercad-icon.png` : 정사각형 아이콘 (M 심볼만)
- `assets/makercad-logo.png` : 글자 포함 전체 로고 (SNS 공유 이미지)
- `favicon.ico`, `assets/favicon-32.png`, `assets/apple-touch-icon.png` : 브라우저 탭·휴대폰 홈 화면 아이콘
- `assets/gripper-car-model.jpg`, `assets/gripper-car-ui.jpg` : 집게 자동차 프로젝트 섹션 이미지
- `assets/gripper-car-assembly.mp4` : 집게 자동차 조립 영상 (720p, 1.5배속, 약 5MB) · `assets/gripper-car-assembly-poster.jpg` : 영상 대표 이미지
- `assets/quadruped-motion.mp4`, `assets/quadruped-motion-poster.jpg` : 4족 보행로봇 로봇 동작 영상(31초, 약 1.7MB)과 대표 이미지

## 검색 등록 파일
- `robots.txt`, `sitemap.xml` : 네이버·구글이 사이트를 수집할 때 읽는 파일 (지우지 마세요)
- `CNAME` : 도메인 makercad.kr 연결 파일 (지우지 마세요)
- 한글 검색어 "메이커캐드"는 index.html의 title, description, keywords, 구조화 데이터(ld+json)에 들어 있습니다.
