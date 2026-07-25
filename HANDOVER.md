# HANDOVER — productivity-suite-site ("Everfold Suite")

Suite showcase landing page for FreelancerOS + Snapline + ScribeGlass + JARVIS/Vaani.
**PUBLIC + LIVE: https://kaustubhtripathi-code.github.io/everfold-suite/**
(repo `kaustubhtripathi-code/everfold-suite` — the local folder is still
`productivity-suite-site`, so folder name ≠ repo name ≠ brand name. All three are the same
thing.)

**2026-07-25 rebrand — "Studio Stack" is DEAD as a brand.** The page now reads **Everfold
Suite**, an Everfold Labs product; the wordmark links to everfold-site and everfold-site's
catalogue carries a "Everfold Suite" bundle card pointing back here. Studio Stack was
superseded by Everfold Labs as the studio-wide brand and two competing storefronts under
different names was the problem this fixes.

**2026-07-25 repo rename — `studio-stack` → `everfold-suite`** (done, at user request).
The only inbound link anywhere was everfold-site's bundle card; it was updated to the new
Pages URL in the same pass. GitHub redirects the *repo* URL
(`github.com/…/studio-stack` → `…/everfold-suite`) but **does NOT redirect the Pages URL** —
`kaustubhtripathi-code.github.io/studio-stack/` is dead. If you ever find that old path in
a bookmark, post, or DM, it will 404; point it at `/everfold-suite/`.

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
