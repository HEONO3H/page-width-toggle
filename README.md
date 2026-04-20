# Page Width Toggle

An Obsidian plugin that toggles per-note page width between the default and wide modes with one click.

## Features

- **Per-note width** — does not affect vault-wide "readable line length" settings
- **4 entry points** — ribbon icon, command palette, editor right-click menu, note more-options menu

## Width states

| State | `cssclasses` | Width |
|---|---|---|
| Default | (none) | Obsidian default |
| Wide | `wide` | 100% of window width |

A `narrow` (560px) class is also defined in the CSS snippet. It is not part of the toggle cycle, but you can apply it manually via `cssclasses: [narrow]` in a note's frontmatter.

## Installation

### Manual

1. Download `main.js`, `manifest.json`, and `page-width.css` from the [latest release](https://github.com/HEONO3H/page-width-toggle/releases/latest)
2. Copy `main.js` and `manifest.json` to your vault's `.obsidian/plugins/page-width-toggle/` folder
3. Copy `page-width.css` to your vault's `.obsidian/snippets/` folder
4. Obsidian → Settings → Appearance → CSS snippets → enable **page-width**
5. Settings → Community plugins → enable **Page Width Toggle**

### BRAT (beta)

1. Install the [BRAT plugin](https://github.com/TfTHacker/obsidian42-brat)
2. BRAT settings → `Add Beta Plugin` → enter `HEONO3H/page-width-toggle`
3. Install the CSS snippet manually as in steps 3–4 above

## License

MIT

---

## 한국어 (Korean)

노트별로 페이지 너비를 기본/넓게(Wide) 토글하는 Obsidian 플러그인.

### 기능
- **노트별 너비 토글** — 볼트 전체 설정과 무관하게 노트마다 개별 적용
- **4가지 진입점** — 리본 아이콘 / 명령 팔레트 / 에디터 우클릭 / 노트 ⋯ 메뉴

### 너비 상태
| 상태 | cssclasses | 너비 |
|---|---|---|
| 기본 | (없음) | Obsidian 기본값 |
| 넓게 | `wide` | 100% (창 너비) |

`narrow` (560px) 클래스도 스니펫에 정의되어 있으며, 프론트매터에 `cssclasses: [narrow]`로 수동 적용 가능합니다.

### 설치
수동 설치: [최신 릴리스](https://github.com/HEONO3H/page-width-toggle/releases/latest)에서 `main.js`, `manifest.json`, `page-width.css` 다운로드.
- `main.js`, `manifest.json` → `.obsidian/plugins/page-width-toggle/`
- `page-width.css` → `.obsidian/snippets/`
- Obsidian → 설정 → 모양 → CSS 스니펫에서 `page-width` 활성화
- 설정 → 커뮤니티 플러그인에서 **Page Width Toggle** 활성화

BRAT: `Add Beta Plugin` → `HEONO3H/page-width-toggle` 입력.
