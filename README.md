# Seongmin Park — CV website

GitHub Pages용 정적 사이트. 프레임워크 없이 HTML + CSS만 사용.

## 파일
- `index.html` — 페이지 전체 (콘텐츠 수정은 여기서)
- `style.css` — 스타일 (색상은 상단 `:root` 변수에서 일괄 변경)
- `assets/` — 이미지 폴더 (직접 만들어서 넣기)

## 할 일
1. `assets/profile.jpg` — 프로필 사진 추가 (정사각형 권장)
2. GitHub 링크 — `index.html`에서 `https://github.com/`을 본인 프로필 URL로 교체
3. Life 사진 — `assets/life-1.jpg` 등 추가 후, 주석대로 placeholder `<div>`를 `<img>`로 교체
4. Publications / Service 섹션 — 준비되면 `index.html`의 주석 해제

## 배포 (GitHub Pages)
1. 새 저장소 생성 (개인 사이트면 `username.github.io`)
2. 이 폴더의 파일들을 저장소 루트에 push
3. Settings → Pages → Branch를 `main`으로 설정
