# World Cup 2026 — Live Wallpaper

A single-page, auto-updating guide to all 104 matches of the FIFA World Cup 2026 (USA · Canada · Mexico, 11 June – 19 July), designed as a 2560×1440 wallpaper.

**Live demo:** https://lmsam.github.io/worldcup2026-wallpaper/

(Enable GitHub Pages: Settings → Pages → Deploy from branch → `main` / root)

## Features

- All 12 groups with live-ranked tables (Pts → Goal difference → Goals scored, per FIFA tiebreak rules) and every group fixture with UK kick-off time (BST) and TV channel (BBC/ITV)
- Full knockout bracket in true bracket geometry — Round of 32 through to a gold-framed Final, with connector lines
- Live scores via ESPN's public scoreboard API; polls every 60 s during matches and sleeps until the next kickoff otherwise
- 4 colour themes (Stadium Night, Fiesta, Matchday Pitch, Retro Paper)
- Show/hide TV channels toggle
- Custom background: click 🖼 Background and paste any image URL, or drop a `bg.jpg`/`bg.png`/`bg.webp` in this folder
- Optional artwork slot: add a transparent `wc26-art.png` and it appears top-centre
- ⬇ one-click 4K wallpaper PNG export (3840×2160)

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app — no build, no dependencies beyond two CDN scripts |
| `wc26-art.png` | (optional) your artwork, shown top-centre |
| `bg.*` | (optional) full-page backdrop image |

## Notes

Unofficial fan project. Not affiliated with or endorsed by FIFA, the BBC, ITV or ESPN. Match schedule and UK broadcast assignments transcribed from published listings; scores fetched client-side from ESPN's public API. All times BST.
