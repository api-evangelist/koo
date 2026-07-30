# Koo

Koo was an Indian microblogging and social networking platform built by Bombinate Technologies — a multilingual, India-first alternative to Twitter/X supporting Hindi, Kannada, Tamil, Telugu, Marathi and other regional languages. Backed by Accel and Tiger Global, it ceased operations in 2024.

**Status: defunct.** The enrichment pipeline verified this on 2026-07-19:

- `kooapp.com` and `www.kooapp.com` return HTTP 404 — the domain is parked on Wix nameservers with no site connected.
- No `developers.`, `docs.`, or `api.` subdomain resolves, and none was ever captured in the Wayback Machine across ~50,000 archived `kooapp.com` URLs.
- All probed `/.well-known/` paths return 404 (see `well-known/koo-well-known.yml`).
- The `koo-app` GitHub org has no public repositories; parent org `bombinatetech` holds only forks of general-purpose open source libraries — no Koo API, SDK, or client library.
- No first-party packages found on any registry.

Koo never published a public API program, so no API artifacts were generated — fabricating them would misrepresent the company. This repo is retained as a historical record. Domain-level probe data lives in `security/koo-domain-security.yml`.

Backed by: accel, tiger-global — https://www.kooapp.com/ (parked)
