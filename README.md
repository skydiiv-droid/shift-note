# 인계장 (shift-note)

근무 인계장 작성·인쇄용 PWA. A4 1페이지에 최대 13명, 오프라인 사용·홈화면 설치 지원.

- **바로 쓰기:** https://skydiiv-droid.github.io/shift-note/
- 저장은 안 되고(새로고침 시 초기화), 기기 간 이동은 툴바의 **연동** 코드로 복사/붙여넣기.

## 구성
- `index.html` — 앱 본체
- `manifest.webmanifest` — PWA 매니페스트
- `sw.js` — 서비스워커 (오프라인 캐시)
- `icon-192.png`, `icon-512.png` — 앱 아이콘

## 배포 메모
`sw.js`를 수정해 재배포할 때는 상단의 `CACHE` 버전(`handoff-v1` → `v2`…)을 반드시 올려야 업데이트가 반영됩니다.
