# The Long Game — Prajwal Kulkarni

The digital headquarters of **Prajwal Kulkarni**, an AI &amp; Data Science engineer building
toward AI that becomes companies. A single-page experience built as a study in *the long game*:
chess as a design language for strategy and patience, and the poise of a premium investment
firm for how value compounds over time.

**Live site:** https://prajwal-kulk.netlify.app/

## Highlights

- **Intro gate** that dissolves like a clearing chessboard into the site.
- **Living background** — a faint board where squares pulse like unseen moves being played.
- **Knight's Tour** hero animation (Warnsdorff's heuristic), computed live in the browser.
- **Positions** — projects presented as a portfolio ledger with conviction and returns.
- Day / night themes, custom chess-reticle cursor, magnetic controls, and a few easter eggs
  for the curious (try the Konami code).

## Tech

A single, self-contained `index.html` — no build step, no dependencies, no framework.
Vanilla HTML, CSS (custom-property design tokens, both themes), and JavaScript (Canvas
for the board animations). Fully responsive and reduced-motion aware.

## Structure

```
index.html    The entire site (styles + markup + scripts inlined)
resume.pdf     One-page résumé, linked from the Endgame section
```

## Run locally

Just open `index.html` in a browser. For behaviour identical to production
(so the résumé PDF and paths resolve exactly), serve the folder:

```bash
python -m http.server 5173
# then open http://localhost:5173
```

## Deploy

Connected to Netlify via GitHub — every push to `main` redeploys automatically.
No build command; publish directory is the repository root.

---

Contact: [kprajwal206@gmail.com](mailto:kprajwal206@gmail.com) ·
[GitHub](https://github.com/stupefyingcoder) ·
[LinkedIn](https://www.linkedin.com/in/prajwal-kulkarni-398359153)
