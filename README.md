# Greenfield Studio — legal

Public hosting for Greenfield Studio's legal documents, so they have stable URLs that can be
referenced from game-portal submission forms and store listings.

| Document | URL |
|---|---|
| Privacy policy (web-portal builds of Minigolf Pro) | https://greenfieldstudio.github.io/legal/privacy.html |

## Scope note

`privacy.html` covers the **web-portal builds** of Minigolf Pro — the versions published on
portals such as Poki. Those builds have no account system, no cloud save and no analytics: game
progress is stored only in the player's own browser, and the studio collects nothing.

Other distributions of Minigolf Pro (itch.io, desktop) offer optional accounts and cloud saves,
and therefore collect more. Those are covered by a fuller policy shown inside the game itself.
Keep the two in step when either changes.

## Editing

Plain static HTML with inlined CSS — no build step, no dependencies. Edit and push; GitHub Pages
serves it directly. Update the "Last updated" date in the page whenever the content changes.
