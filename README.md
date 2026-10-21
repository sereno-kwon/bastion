# Bastion Cycles Korea

bastioncycles.co.kr 원페이지 정적 사이트 (GitHub Pages). tsubasabicycles.co.kr과 같은 구조입니다.

- `index.html` 원페이지 본체 (BRAND · ARCHETYPE · MODELS · PROCESS · GALLERY · SHOWROOM)
- `404.html` 기존 아임웹 하위 주소(/archetype, /showroom 등)를 섹션으로 연결, 저널·뉴스·영상 주소는 홈으로 이동
- `brand/`, `archetype/` 등 하위 폴더: 자주 쓰이던 기존 주소의 리디렉션 페이지
- `images/` 섹션별 이미지 (`hero`, `brand`, `archetype`, `models`, `process`, `gallery`, `showroom`)
- `.github/image-manifest.txt` + `fetch-images.yml` 아임웹 CDN 이미지 이전용 워크플로

## 이미지
매니페스트를 수정해 main에 푸시하면 Actions가 이미지를 받아 `images/`에 커밋합니다.
이미 받은 파일은 건너뛰므로, 이미지를 교체할 때는 해당 파일을 지우거나 새 파일명으로 추가합니다.
