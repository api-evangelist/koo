# Koo

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Koo was an Indian microblogging and social networking platform built by Bombinate Technologies — a multilingual, India-first alternative to Twitter/X supporting Hindi, Kannada, Tamil, Telugu, Marathi and other regional languages. Backed by Accel and Tiger Global, it ceased operations in 2024.

**Status: defunct.** The enrichment pipeline verified this on 2026-07-19:

- `kooapp.com` and `www.kooapp.com` return HTTP 404 — the domain is parked on Wix nameservers with no site connected.
- No `developers.`, `docs.`, or `api.` subdomain resolves, and none was ever captured in the Wayback Machine across ~50,000 archived `kooapp.com` URLs.
- All probed `/.well-known/` paths return 404 (see `well-known/koo-well-known.yml`).
- The `koo-app` GitHub org has no public repositories; parent org `bombinatetech` holds only forks of general-purpose open source libraries — no Koo API, SDK, or client library.
- No first-party packages found on any registry.

Koo never published a public API program, so no API artifacts were generated — fabricating them would misrepresent the company. This repo is retained as a historical record. Domain-level probe data lives in `security/koo-domain-security.yml`.

Backed by: accel, tiger-global — https://www.kooapp.com/ (parked)
