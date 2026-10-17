# Formwheel Story — The Orbit Chronicles

**Season 1: Complete Edition** · Difficulty B (Mystery Exploration)

Six-chapter Korean-language interactive story, from Chapter 0: The First Spin through Chapter 5: One More Spin.

## Play

Open `index.html` in a browser or enable GitHub Pages under **Settings → Pages → Deploy from a branch → main / (root)**.

Expected URL after Pages deployment: https://semicolonxss.github.io/Formwheel_Story/

## Season 1 contents

| # | Chapter | Mechanic |
|---|---|---|
| 0 | The First Spin | Choose ECHO/NOVA/VOID/RIFT identity and restore a clue |
| 1 | Echo Protocol | ROT3 cipher |
| 2 | Lost Records | Hexadecimal ASCII cipher |
| 3 | Broken Orbit | Ordered signal recovery |
| 4 | Four Signals | Signal lore puzzle |
| 5 | One More Spin | Final code and choice-dependent ending |

## Features
- Responsive dark-purple Orbit theme; shares Hub favicon and Hub link
- Chapter unlocking, replay of completed chapters, three hints per puzzle
- Exploration journal, story-only records, and browser-local save/reset
- Optional links to existing projects for exploration

## Scope and limitations

**This is a complete playable standalone Season 1 story, not full cross-repository integration.** Progress uses browser localStorage (`formwheel_story_season1_v1`). It is **not** synced to Formwheel ID / Firebase. Story records are not actual AQS achievements or XP. Project links are optional; there is no cross-project event verification or integrated ECHO Quiz room. This is intentionally disclosed in the UI. Real rewards must be validated server-side before implementing AQS payout.

## Next integration milestones

1. Sign in with shared Formwheel ID and safely synchronize story progress.
2. Integrate Quiz ECHO special room and approved Secret triggers.
3. Add verified AQS XP/achievement issuance (anti-replay, authentication, restricted DB rules).
4. Add an unobtrusive Story entry point in Hub.
5. Test mobile browsers, keyboard navigation, and Pages deployment.
