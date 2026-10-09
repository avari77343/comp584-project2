# COMP-584 Project 2 — Splatnet Field Guide

A responsive, Splatoon 3-inspired fan page built with HTML and CSS Flexbox for COMP-584. The artwork is original abstract ink-themed SVG artwork; this is an unofficial fan-made project and is not affiliated with Nintendo.

## Files
- `index.html` — page structure and six Flexbox layout rows
- `style.css` — responsive Flexbox layout and mobile/tablet breakpoints
- `images/` — original local SVG artwork
- `assets/desktop.png`, `tablet.png`, `mobile.png` — assignment reference screenshots from the starter project
- `PROJECT_NOTES.txt` — row-by-row implementation notes

## Run locally
Open `index.html` in a browser. All custom artwork is stored locally. The stylesheet uses Google Fonts as a progressive enhancement; fallback fonts are included.

## Publish with GitHub Pages
1. Create a **new public GitHub repository** named `comp584-project2-av`.
2. Upload the contents of this folder to the repository root (so `index.html` is at the root).
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for GitHub Pages to publish the site. Copy the published URL into the Canvas submission and add it here:

**GitHub Pages URL:**https://avari77343.github.io/comp584-project2/

## Flexbox requirements
- Rows 1 and 2 show four cards and two half-width cards.
- Row 3 uses a narrow feature column and a wide content column on desktop.
- Row 4 is a single full-width feature.
- Row 5 demonstrates a 1–2–1 desktop arrangement and changes item order at tablet/mobile breakpoints using CSS `order`.
- Row 6 is a unique six-item flexible checklist row.
