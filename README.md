# HBS Move Planner

A single-file mobile web app to plan shopping & packing for the move to Harvard Business School.

- **Shopping India** and **Shopping USA** lists, plus a **Packing** list.
- Items checked off a shopping list become active in Packing (greyed/locked until bought).
- Smart offline category auto-detection (no API), quantity, comments, per-item bag numbers.
- Excel import/export and a downloadable template.
- All data is stored locally in the browser (`localStorage`).

## Run locally
Just open `index.html` in a browser.

## Deploy
Static site — no build step. Hosted on Vercel; every push to `main` auto-deploys.
