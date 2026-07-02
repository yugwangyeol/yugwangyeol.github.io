# Gwangyeol Yu — Academic Homepage

GitHub Pages 개인 홈페이지입니다. Martin Saveski 템플릿 계열(좌측 사이드바 + 우측 섹션)을 참고했습니다.

## 배포 방법

1. 새 저장소 `yugwangyeol.github.io` 생성 (username = GitHub 아이디).
2. `index.html`과 `assets/` 폴더를 저장소 루트에 push.
3. Settings → Pages → Branch를 `main / (root)`로 설정.
4. 몇 분 후 `https://yugwangyeol.github.io` 접속.

## 프로필 사진

`assets/profile/me.jpg`에 본인 사진(정사각형 권장, 400×400 이상)을 넣으세요.
없으면 자동으로 숨겨집니다.

## 논문 썸네일 (선택)

`index.html`의 `.pub-thumb` 안 placeholder `<div class="ph">`를
`<img src="assets/publications/mimic.png" alt="...">`로 교체하면 이미지가 표시됩니다.

## 수정할 곳

- 소속/학위: 사이드바 `.role`, Education 섹션
- 링크: 사이드바 `.links` (Google Scholar, LinkedIn 등 추가 가능)
- 논문 링크: 각 `.pub` 하단에 `<div class="pub-links"><a href="...">arXiv</a></div>` 추가
- 끝
