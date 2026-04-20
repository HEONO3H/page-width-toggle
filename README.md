# Page Width Toggle

노트별로 페이지 너비를 기본/넓게(Wide) 토글하는 Obsidian 플러그인.

## 기능

- **노트별 너비 토글** — 볼트 전체 설정과 무관하게 노트마다 개별 적용
- **4가지 진입점** — 리본 아이콘 / 명령 팔레트 / 에디터 우클릭 / 노트 ⋯ 메뉴

## 너비 상태

| 상태 | cssclasses | 너비 |
|---|---|---|
| 기본 | (없음) | Obsidian 기본값 |
| 넓게 | `wide` | 100% (창 너비) |

`narrow` (560px) 클래스도 CSS에 정의되어 있어 프론트매터에 직접 `cssclasses: [narrow]` 로 수동 적용 가능.

## 설치 방법

### 수동 설치
1. [Releases](https://github.com/HEONO3H/page-width-toggle/releases/latest)에서 `main.js`, `manifest.json`, `page-width.css` 다운로드
2. `main.js`, `manifest.json` → `.obsidian/plugins/page-width-toggle/` 에 복사
3. `page-width.css` → `.obsidian/snippets/` 에 복사
4. Obsidian → 설정 → 모양 → CSS 스니펫에서 `page-width` 활성화
5. 설정 → 커뮤니티 플러그인에서 `Page Width Toggle` 활성화

### BRAT으로 설치
1. [BRAT 플러그인](https://github.com/TfTHacker/obsidian42-brat) 설치
2. BRAT 설정 → `Add Beta Plugin` → `HEONO3H/page-width-toggle` 입력
3. 위 3~4번 스니펫 설치 단계는 동일하게 진행

## 라이선스

MIT
