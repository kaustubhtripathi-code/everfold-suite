# AGENTS.md — everfold-suite

Public single-page showcase for **Everfold Suite** (an Everfold Labs bundle: FreelancerOS +
Snapline + ScribeGlass + JARVIS/Vaani). Live on GitHub Pages; low-churn marketing page.
**This repo is PUBLIC**: nothing private or keyed ever goes in here.

Naming: repo `everfold-suite` = brand "Everfold Suite" = owner's local folder
`productivity-suite-site`. Formerly "Studio Stack" / repo `studio-stack`; that brand is dead.

## Stack & layout
Plain static HTML, no build step. Self-contained `index.html` (only external dep: Google
Fonts); real product screenshots + demo video in `assets/`. `ci/site_check.py` is the CI
link/asset checker and stager.

## Setup
None. Needs `python3` (3.12+) and `node` (checker runs `node --check` on any JS files).

## Run / build / test / lint
- Preview: `python3 -m http.server 8000` (unverified)
- Check (what CI runs; stage outside the repo so no `_site/` is created):
  `python3 ci/site_check.py --repo everfold-suite --output /tmp/everfold-suite-_site` (verified 2026-10-11).
  The script refuses an existing output dir; delete it before re-running. Never commit `_site/`.

## Environment variables
None required.

## Codex cloud environment
- Setup script: `python3 --version && node --version` (nothing to install)
- Internet during agent phase: off is fine
- Secrets to add: none

## Deployment (do not break)
- https://kaustubhtripathi-code.github.io/everfold-suite/ via GitHub Pages.
- `.github/workflows/ci-cd.yml` checks every push/PR and deploys the staged artifact with
  `actions/deploy-pages` only from `main`. A push to `main` = live. Do not push to `main`
  without owner approval; use a branch + PR. Do not edit the workflow or `ci/` unless asked.
- The old Pages URL `/studio-stack/` is dead (GitHub does not redirect Pages after a rename).
  everfold-site's catalogue has a bundle card linking here; keep the URL stable.

## Rules for agents (owner decisions, do not undo)
1. On-device tools (Snapline + ScribeGlass local) are a "free forever" banner, not a pricing
   tier; FreelancerOS is the paid platform (Pro $12 / Team $29 / Enterprise).
2. **No Snapline download link.** The public release was deliberately taken down; Snapline
   is "included with every FreelancerOS plan". Never re-publish a download without asking.
3. JARVIS section keeps personas generic ("switchable voices/personalities"); never name a
   persona after a real person.
4. Wordmark links to everfold-site; keep the Everfold Labs branding.

## Open work
- None pending. `ci/portfolio-20260907` is already merged into `main`. See `HANDOVER.md` for history.
