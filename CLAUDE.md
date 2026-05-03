# Mote Privacy Policy Repo

Repo-local `CLAUDE.md`.

This repo is the public/privacy-policy surface for Mote, not the main application repo.

Canonical project memory:
- `~/Claude/maciej/development/projects/mote/_PROJECT.md`
- `~/Claude/maciej/development/projects/mote/_LESSONS_LEARNED.md`

## Working rules

- Keep changes narrow and user-facing
- Preserve public URL stability
- Coordinate app-facing text changes with the main Mote project and store metadata when relevant
- Mirror meaningful user-facing updates in Notion

## GitHub

- This repo may be public by design because it hosts the privacy policy
- Do not store secrets, tokens, or internal-only notes here

## Files

- `index.html` — root with auto-redirect to PL/EN per browser locale
- `pl/` — Polish privacy policy
- `en/` — English privacy policy
- `app-ads.txt` — AdMob ads.txt declaration (added 2026-05-03; required for AdMob ads serving on Mote — publisher pub-5353750048775501, cert f08c47fec0942fa0)
  - Format: `google.com, pub-5353750048775501, DIRECT, f08c47fec0942fa0`
  - Verifies publisher ownership for `com.mojemote.app` (App Store + Google Play); ASC marketing URL + Play developer URL must declare `https://macsiem.github.io/mote-privacy/`
  - Do not remove without coordinating with AdMob console
