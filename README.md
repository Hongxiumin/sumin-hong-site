# Sumin Hong — Personal Site

## 폴더 구성
- `index.html` — 실제 홈페이지 (content.json을 읽어 렌더링)
- `content.json` — 사이트에 표시되는 모든 텍스트 데이터
- `admin.html` — content.json을 편집하는 관리자 페이지

## GitHub Pages로 올리는 방법

1. GitHub에서 새 저장소 생성 (예: `suminhong.github.io` 또는 아무 이름)
2. 이 폴더의 `index.html`, `content.json`, `admin.html` 세 파일을 저장소에 업로드
   - GitHub 웹사이트에서 "Add file → Upload files"로 드래그앤드롭 가능
3. 저장소 Settings → Pages → Source를 "Deploy from a branch" → `main` / `/(root)`로 설정
4. 몇 분 후 `https://<사용자명>.github.io/<저장소명>/` 에서 사이트 확인 가능
5. 관리자 페이지는 `https://<사용자명>.github.io/<저장소명>/admin.html` 로 접속

## 콘텐츠 수정 방법 (이후)

1. `admin.html` 접속 → 원하는 항목 수정 → 상단 "content.json 다운로드" 클릭
2. 다운로드된 `content.json`을 저장소의 기존 `content.json`에 덮어써서 커밋(업로드)
3. GitHub Pages가 자동으로 다시 배포되며, 잠시 후 실제 사이트에 반영됩니다

※ `admin.html`은 파일을 직접 수정하지 않고 새 `content.json`을 "다운로드"만 해줍니다 —
보안상 브라우저에서 저장소에 직접 쓸 수는 없기 때문에, 다운로드한 파일을 저장소에 업로드하는
한 단계가 필요합니다. (GitHub 계정을 연결해주시면 이 업로드 단계도 자동화해 드릴 수 있어요.)
