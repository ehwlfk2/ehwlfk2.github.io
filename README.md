# ehwlfk2.github.io — 개인 프로필 · 포트폴리오 사이트 (초안 · 비공개)

- 표지 `index.html` = `도경진 프로필` (원본: `D:\projects\portfolio\mentor-profile.html`). 프로젝트 편 3개는 표지가 상대 링크로 여는 파일명을 그대로 둔다.
- 정본은 `D:\projects\portfolio` (비공개 저장소 `ehwlfk2/portfolio-src`). 이 저장소에는 **공개해도 되는 HTML 만** 올린다. 갱신은 원본을 고친 뒤 `portfolio-src` 의 `publish.ps1` 로 밀어 넣는다.
- 이미지는 전부 data URI 로 파일 안에 있다(표지 191KB · 편 305~512KB). 외부 이미지 · 외부 스크립트 없음.

## 공개 전환 절차(오너 승인 뒤)

1. 아래 점검표를 확인한다.
2. GitHub → 이 저장소 Settings → General → Danger Zone → Change visibility → Public.
3. Settings → Pages → Build and deployment: Deploy from a branch → `main` / `/ (root)` → Save. 몇 분 뒤 `https://ehwlfk2.github.io/` 가 열린다.
4. 프로필 README(`ehwlfk2/ehwlfk2`)에 링크 한 줄을 넣는다(초안: `portfolio-src/PROFILE-README.draft.md`).

## 공개 전 점검표

- [ ] 표지의 연락처(전화 1 · 메일 1 · `tel:` `mailto:` 링크)를 공개할지 결정
- [ ] 표지 `github.com/ehwlfk2` 링크 2건 — 프로필 링크라 공개 무방. 프로젝트 저장소(비공개) 링크는 없다(실측 0)
- [ ] 라이브 링크 6건(pages.dev · workers.dev) 응답 확인
- [ ] 편 3개의 실측 수치 · 날짜가 오래되지 않았는지
- [ ] Pages 는 무료 계정에서 공개 저장소만 된다. 비공개로 두는 동안은 LAN 초안 `http://192.168.219.101:4100/pm/portfolio-draft/` 로 본다