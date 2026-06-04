# Ohio State University (ohio-state-university)

Ohio State University is a large public land-grant research university in Columbus, Ohio, United States, ranked #208 in the QS World University Rankings 2025. It does not run a single centralized public developer portal; its public, programmatically accessible footprint is fragmented across units, with the clearest documented APIs coming from University Libraries' Knowledge Bank institutional repository and an institution-wide Shibboleth SAML Single Sign-On service.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ohio-state-university/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ohio-state-university-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Institutional Repository, Open Access, United States

## APIs

- **Knowledge Bank DSpace REST API** — DSpace 7.6 REST API (JSON HAL) for the Libraries' institutional repository. Docs: https://library.osu.edu/kb · Base: https://kb.osu.edu/server/api
- **Knowledge Bank OAI-PMH Interface** — OAI-PMH 2.0 metadata harvesting endpoint. Docs: https://library.osu.edu/kb/faqs · Base: https://kb.osu.edu/server/oai/request
- **Web Single Sign-On (Shibboleth)** — SAML 2.0 web authentication via Shibboleth, InCommon Federation member. Docs: https://cybersecurity.osu.edu/services/web-single-sign

## Plans

[plans/ohio-state-university-plans-pricing.yml](plans/ohio-state-university-plans-pricing.yml)

## Rate Limits

[rate-limits/ohio-state-university-rate-limits.yml](rate-limits/ohio-state-university-rate-limits.yml)

## FinOps

[finops/ohio-state-university-finops.yml](finops/ohio-state-university-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.osu.edu/
- GitHub: https://github.com/osulibraries
- LinkedIn: https://www.linkedin.com/school/the-ohio-state-university/
- Authentication: https://cybersecurity.osu.edu/services/web-single-sign
- Plans, Rate Limits, FinOps, and Review pointers (see files above and `review.yml`).

## Notes

All endpoints were probed during research. The Knowledge Bank DSpace REST API (DSpace 7.6) and OAI-PMH interface were verified live returning real metadata. The Web SSO service is documented but gated to registered campus service owners. The enterprise Data Catalog is powered by data.world and gated to Ohio State affiliates — no public open-data API was confirmed. A previously cited `opic.osu.edu/developers` page returned 404 and is not cataloged. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
