# Oncare Dashboard

Single-file dashboard (`index.html`), served from `main` via GitHub Pages.

## Build stamp — update on EVERY change
The header banner shows `build: …` from `window.__BUILD__` near the top of `index.html`.
Whenever you change anything in `index.html` (rules, mappings, benchmarks, UI), update that
line in the same commit so the user can see the change is live:

    window.__BUILD__ = 'YYYY-MM-DD vNN — short description of the change';

- Date: today's date (IST).
- Version: previous `vNN` + 1.
- Description: a few words on what changed (e.g. "relevancy: Patient Died now irrelevant").
