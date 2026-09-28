# Game Tagger

Keyboard-first basketball game video tagger (AAU 12U). Single static HTML file, no build, no backend.

- Load one or more video clips per game, tag stats by jersey number + key
- Live box score with minutes on court, exact-5-on-court enforcement
- Export CSV / parent report (HTML) / raw JSON
- All data stays in the browser (localStorage). Videos are never uploaded.

## Keys
Type jersey number, then: `A/S` 2PT made/miss · `D/F` 3PT · `G/H` FT · `R` REB · `T` AST · `Y` STL · `U` TO
`I`/`O` sub in/out · `P` clock stopped · `Z` undo · `E` game end · `Space` play/pause · `←/→` ±5s

## Deploy
Static hosting only: serve `index.html` (GitHub Pages, Cloudflare Pages, Netlify, Vercel).
