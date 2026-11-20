# DraftedCV (template repo)

GitHub Pages template repo for DraftedCV client CVs. Live: https://stocks84.github.io/draftedcv/

## Stack
Static HTML/CSS (two-page A4 print layout). No framework, no build step, no package.json.

## Commands
- Install: none
- Run: open the folder in a browser, or `python3 -m http.server 8000`
- Test / lint: none. Smoke check: `test -s index.html && test -s daniel-hartwell/index.html`
- Build: none. GitHub Pages publishes from `main`.

## Layout
- `index.html` — repo landing page
- `daniel-hartwell/` — master template (fictional demo CV). Live: https://stocks84.github.io/draftedcv/daniel-hartwell/
- New client: copy that folder to a lowercase hyphenated name, swap details and `headshot.jpg`, and regenerate `qr-code.png` for the Pages URL.

## Conventions
- Never commit real client data. Content here is fictional only (no real names, employers, or contact details).
- Never commit secrets or Will's personal Gmail; use `124254214+Stocks84@users.noreply.github.com` instead. Git author must be `Stocks84 <124254214+Stocks84@users.noreply.github.com>`. Do not push to `main` or merge without Will's approval.

## End-of-job report
Every finished coding job must be reported in this shape. Only list a check under CHECKS RUN if it actually ran; anything untested goes under NOT CHECKED, never left out.

PROJECT: repo and branch
PULL REQUEST: link (or not created)
PREVIEW: link or how to open it (or unavailable)
BUILT: what changed, in plain words
CHECKS RUN: what ran and the result
NOT CHECKED: what nobody tested (e.g. real phone, live data, emails)
KNOWN ISSUES: list, or none
COST / USAGE: where to see it; never guess a number
NEXT DECISION: exactly what Will needs to say yes or no to
