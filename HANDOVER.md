# HANDOVER — productivity-suite-site ("Everfold Suite")

Suite showcase landing page for FreelancerOS + Snapline + ScribeGlass + JARVIS/Vaani.
**PUBLIC + LIVE: https://kaustubhtripathi-code.github.io/studio-stack/**
(repo `kaustubhtripathi-code/studio-stack` — note the repo name differs from this folder).

**2026-07-25 rebrand — "Studio Stack" is DEAD as a brand.** The page now reads **Everfold
Suite**, an Everfold Labs product; the wordmark links to everfold-site and everfold-site's
catalogue carries a "Everfold Suite" bundle card pointing back here. Studio Stack was
superseded by Everfold Labs as the studio-wide brand and two competing storefronts under
different names was the problem this fixes.

⚠ **USER STEP (only you can do it):** the repo and therefore the Pages URL are still
`studio-stack`. Renaming the repo to e.g. `everfold-suite` changes the live URL and GitHub
Pages does **not** redirect old paths — everfold-site's bundle card and freelanceros-site's
footer both hardcode the current `/studio-stack/` URL, so rename and update those together
or not at all. Nothing is broken if you leave the repo name as is.

- Self-contained `index.html`; real Playwright screenshots + demo video in `assets\`.
- Redeploy = push to `main`; Pages serves from root.
- **Standing content rules (user decisions — do not undo):**
  1. On-device tools (Snapline + ScribeGlass local) are a "free forever" BANNER, not a
     pricing tier; FreelancerOS is the paid platform (Pro $12 / Team $29 / Enterprise).
  2. **No Snapline download link** — the public release was deliberately taken down 07-10;
     Snapline is "included with every FreelancerOS plan". Never re-publish without asking.
  3. JARVIS section keeps personas GENERIC ("switchable voices/personalities") — never name
     a persona based on a real person.
- This repo is PUBLIC — nothing private/keyed ever goes in here.
- User steps: none pending.

Last audit: 2026-07-12 (state = last commit `09e5805`, 2026-07-10 pricing-positioning video).
