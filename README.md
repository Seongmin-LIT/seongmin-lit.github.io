# Seongmin Park — CV website

GitHub Pages용 정적 사이트. 프레임워크 없이 HTML + CSS만 사용.

## 파일
- `index.html` — 페이지 전체 (콘텐츠 수정은 여기서)
- `style.css` — 스타일 (색상은 상단 `:root` 변수에서 일괄 변경)
- `assets/` — 이미지 폴더 (직접 만들어서 넣기)

## 할 일
1. GitHub 링크 — `index.html`에서 `https://github.com/`을 본인 프로필 URL로 교체
2. Publications / Service 섹션 — 준비되면 `index.html`의 주석 해제
3. Life 사진 추가 — 새 사진은 `assets/life-3.jpg` 등으로 넣고 `index.html`의 Life 섹션에 `<figure>` 추가

## 이미지
배포되는 건 웹용으로 변환한 파일만입니다 (원본은 `.gitignore` 처리).
- `assets/profile.jpg` — 600×600, 사이드바 프로필 (원형 크롭됨)
- `assets/life-1.jpg` — LIT Lab 워크숍
- `assets/life-2.jpg` — ICT 챌린지 2026 시상식

원본에서 다시 만들려면 Pillow(+HEIC는 `pillow-heif`)로 리사이즈 후 저장.

## 배포 (GitHub Pages)
1. 새 저장소 생성 (개인 사이트면 `username.github.io`)
2. 이 폴더의 파일들을 저장소 루트에 push
3. Settings → Pages → Branch를 `main`으로 설정
