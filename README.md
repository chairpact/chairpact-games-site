# chairpact-games-site

Public web presence for Chairpact Games — served via GitHub Pages at `games.chairpact.com`.

## Files
The site lives in `docs/`, and GitHub Pages publishes from that folder. This README stays at the root and isn't part of the site.

- `docs/index.html` — the page (one row per game with its trailer, plus About)
- `docs/styles.css` — all styling (colours are variables at the top)
- `docs/CNAME` — tells GitHub Pages to serve this at games.chairpact.com


## Editing
- **Add a game:** copy one `<section class="game">…</section>` block in `docs/index.html` and change the name, text, icon, store links and YouTube video ID. Add `flip` to the class (`class="game flip"`) to put the video on the left, so rows alternate.
- **Add a trailer to Teddy Impact:** replace its `<div class="media showcase">…</div>` with a copy of another game's `<div class="media video">…</div>` and change the video ID.
- **Icons** load from Google Play's image servers. To self-host instead, save them into a `docs/assets/` folder and update the `src` paths.
- **Colours:** the neon red is `--neon` in `docs/styles.css`. Dark-mode colours are at the top of the file and light-mode colours are just below.
- **Title font:** Fondamento (Google Fonts). Change it in the `<link>` in `docs/index.html` and in `.neon` in `docs/styles.css`.
- **Contact email:** in the About section of `docs/index.html`.
