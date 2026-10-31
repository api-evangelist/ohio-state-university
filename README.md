# Ohio State University

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The Ohio State University is a large public land-grant research university in Columbus, Ohio, United States. It operates no central developer portal and publishes no OpenAPI, no API key programme and no developer documentation for any of its surfaces. What it does operate, verified live on 2026-09-01, is a small set of genuinely institution-run programmable surfaces: an unauthenticated JSON class-search and campus-events API at content.osu.edu/v2 that identifies itself as "OSU Mobile API v2" and backs the public class search at classes.osu.edu; a CKAN 2.10.10 open data portal at data.chrr.ohio-state.edu run by the Center for Human Resource Research, which mints its own DataCite DOIs under prefix 10.82271; and an institution-wide Shibboleth SAML 2.0 Identity Provider published in the InCommon Federation under entityID urn:mace:incommon:osu.edu with REFEDS Research and Scholarship and SIRTFI assurance. Everything else that looks like an Ohio State API is a vendor platform running under an Ohio State name: the Knowledge Bank repository is DSpace hosted by Atmire, library discovery is Ex Libris Primo, and the LMS is Instructure Canvas. Those tenancies are recorded here as relationships, not as Ohio State contracts.

**Areas:** University · Higher Education · Education · United States · Public Research University · Course Catalog · Open Data · Research Data · Institutional Repository · Library · Identity Federation · Open Access

## Ohio State University on APIs.io

Everything profiled for Ohio State University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ohio-state-university/](https://apis.io/providers/ohio-state-university/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [CHRR Open Data Portal (CKAN)](https://apis.io/apis/ohio-state-university/chrr-ckan/) — CKAN 2.10.10 open data portal operated by Ohio State's Center for Human Resource Research. The full CKAN Action API is public for read (status_show,…
- [Web Single Sign-On (Shibboleth Identity Provider)](https://apis.io/apis/ohio-state-university/websso/) — Institution-wide web authentication and authorization operated by the Office of Technology and Digital Innovation on Shibboleth, supporting SAML 2.0 with…
- [InCommon Federation IdP Metadata](https://apis.io/apis/ohio-state-university/incommon-idp-metadata/) — Ohio State's SAML 2.0 Identity Provider as published in the InCommon Federation metadata aggregate, retrievable per-entity over the InCommon MDQ service.…
- [Knowledge Bank DSpace REST API](https://apis.io/apis/ohio-state-university/kb-rest/) — REST API for the Knowledge Bank, Ohio State University Libraries' DSpace 7.6 institutional repository. Exposes communities, collections, items and…
- [Knowledge Bank OAI-PMH Interface](https://apis.io/apis/ohio-state-university/kb-oai/) — OAI-PMH 2.0 metadata harvesting endpoint for the Knowledge Bank institutional repository, supporting the standard verbs over Dublin Core and other formats.…
- [Library Discovery (Ex Libris Primo VE)](https://apis.io/apis/ohio-state-university/primo-discovery/) — Library discovery for Ohio State University Libraries, delivered on Ex Libris Primo VE through the OhioLINK consortium (view 01OHIOLINK_OSU). Recorded as a…
- [Canvas LMS Tenancy](https://apis.io/apis/ohio-state-university/canvas-lms/) — Ohio State's Canvas learning management system tenancy, branded Carmen. Canvas exposes an LTI-capable REST API, but that contract is Instructure's and every…
- [DataCite Membership (GVUZ)](https://apis.io/apis/ohio-state-university/datacite-membership/) — The Ohio State University is a DataCite direct member, provider symbol GVUZ, active, linked to ROR https://ror.org/00rs6vg23 and created 2025-06-18. It…
- [Crossref Membership (member 7412)](https://apis.io/apis/ohio-state-university/crossref-membership/) — The Ohio State University Libraries is Crossref member 7412 with 4,927 registered DOIs, covering the journals and scholarly series the Libraries publishes.…
- [ROR Registration](https://apis.io/apis/ohio-state-university/ror/) — The Ohio State University is registered in the Research Organization Registry as https://ror.org/00rs6vg23, the identifier DataCite's provider record for…
- [Ohio State University Classes API](https://apis.io/apis/ohio-state-university/ohio-state-university-classes-api/) — Course and section search against the Student Information System term data.
- [Ohio State University Events API](https://apis.io/apis/ohio-state-university/ohio-state-university-events-api/) — Public campus events feed.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ohio State University Context](https://apis.io/jsonld/ohio-state-university/ohio-state-university-context/)

#### Examples (6)

Example requests and responses.

- [Ohio State University Campus Events Example](https://apis.io/examples/ohio-state-university/ohio-state-university-campus-events-example/)
- [Ohio State University Chrr Ckan Package List Example](https://apis.io/examples/ohio-state-university/ohio-state-university-chrr-ckan-package-list-example/)
- [Ohio State University Chrr Ckan Status Example](https://apis.io/examples/ohio-state-university/ohio-state-university-chrr-ckan-status-example/)
- [Ohio State University Classes Search Example](https://apis.io/examples/ohio-state-university/ohio-state-university-classes-search-example/)
- [Ohio State University Classes Searchable Terms Example](https://apis.io/examples/ohio-state-university/ohio-state-university-classes-searchable-terms-example/)
- [Ohio State University Datacite Provider Example](https://apis.io/examples/ohio-state-university/ohio-state-university-datacite-provider-example/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ohio State University Authentication](https://apis.io/security/ohio-state-university/ohio-state-university-authentication/)
- [Ohio State University Domain Security](https://apis.io/security/ohio-state-university/ohio-state-university-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ohio State University Plans Pricing](https://apis.io/plans/ohio-state-university/ohio-state-university-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ohio State University Rate Limits](https://apis.io/rate-limits/ohio-state-university/ohio-state-university-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ohio State University Finops](https://apis.io/finops/ohio-state-university/ohio-state-university-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.osu.edu/)
- [Blog](https://news.osu.edu/)
- [Privacy policy](https://it.osu.edu/privacy)
- [GitHub](https://github.com/osulibraries)

## API Evangelist rating

**Kin Score 20.5** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 22.1 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 23.8 |
| Access clarity | 15.8 |

**Agent readiness 24.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.6** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ohio-state-university/](https://apis.io/providers/ohio-state-university/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Ohio State University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ohio-state-university/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
