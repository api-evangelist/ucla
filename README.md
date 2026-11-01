# University of California, Los Angeles

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

The University of California, Los Angeles is a public land-grant research university in the University of California system, ranked 29th in the QS World University Rankings, and it is one of the few institutions in this cohort that genuinely runs a central API program rather than renting one. UCLA operates its own API gateway at api.ucla.edu, fronted by Apigee under a certificate issued to the university, and a Drupal/Apigee developer portal at developer.api.ucla.edu that catalogues eight API products. Seven of those products publish a real machine-readable contract, anonymously downloadable, and all seven describe routes on UCLA's own gateway - six Swagger 2.0 contracts covering the student information system (classes, class sections, courses, GE foundations, a 61-operation Registrar data dictionary, the mainframe production calendar, a connectivity health check and the MyUCLA portal menu) plus one OpenAPI 3.0.3 contract for a campus weather station. Ninety-one operations in total, every one of them a read. UCLA also runs its own Shibboleth identity provider, registered by InCommon under entityID urn:mace:incommon:ucla.edu with REFEDS Research & Scholarship and SIRTFI certification - the most complete machine-readable artifact the university publishes, and the one no API catalogue had looked at. UCLA Library self-hosts a Cantaloupe IIIF image server, a Hyrax digital collections platform and a Dataverse instance, all on ucla.edu hosts under UCLA's own TLS certificates. What UCLA does not have is any way in: every credential requires a UCLA logon and a human approval, there is no self-service path, no status page, no changelog, no llms.txt, no machine-readable catalog index, and no rate-limit or error documentation. The learning management system, BruinLearn, is Instructure Canvas on a vanity subdomain and is recorded as a tenant relationship rather than as UCLA engineering.

**Areas:** University · Higher Education · Education · United States · California · UC System · Public Research University · Course Catalog · Student Information · Identity Federation · Research Repository · Library

## University of California, Los Angeles on APIs.io

Everything profiled for University of California, Los Angeles is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ucla/](https://apis.io/providers/ucla/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [UCLA Shibboleth Identity Provider (InCommon)](https://apis.io/apis/ucla/identity/) — UCLA's own Shibboleth identity provider and the most complete machine-readable artifact the university publishes. Registered by InCommon under entityID…
- [UCLA Library IIIF Image Service](https://apis.io/apis/ucla/library-iiif/) — UCLA Library self-hosts a Cantaloupe 5.0.5 image server exposing both IIIF Image API 2.x and 3.0 endpoints for its digital collections. Institution-operated…
- [UCLA Library Digital Collections](https://apis.io/apis/ucla/digital-collections/) — UCLA Library's digital collections platform, institution-hosted on a UCLA IP under a UCLA-issued certificate and developed in the open by the UCLA Library…
- [UCLA Dataverse](https://apis.io/apis/ucla/dataverse/) — UCLA's research data repository, running open-source Dataverse on a UCLA-owned host under a UCLA-issued certificate with no vendor CNAME - which…
- [BruinLearn (Canvas LMS)](https://apis.io/apis/ucla/bruinlearn/) — UCLA's learning management system. The brand, the courses, the learners and the subdomain are UCLA's; the REST API, the LTI 1.3 implementation, the key…
- [University of California, Los Angeles Class Sections API](https://apis.io/apis/ucla/ucla-class-sections-api/) — The Class Sections API from University of California, Los Angeles — 2 operation(s) for class sections.
- [University of California, Los Angeles Classes API](https://apis.io/apis/ucla/ucla-classes-api/) — The Classes API from University of California, Los Angeles — 4 operation(s) for classes.
- [University of California, Los Angeles Courses API](https://apis.io/apis/ucla/ucla-courses-api/) — The Courses API from University of California, Los Angeles — 5 operation(s) for courses.
- [University of California, Los Angeles Dictionary API](https://apis.io/apis/ucla/ucla-dictionary-api/) — The Dictionary API from University of California, Los Angeles — 61 operation(s) for dictionary.
- [University of California, Los Angeles GE Foundations API](https://apis.io/apis/ucla/ucla-ge-foundations-api/) — The GE Foundations API from University of California, Los Angeles — 2 operation(s) for ge foundations.
- [University of California, Los Angeles Infrastructure API](https://apis.io/apis/ucla/ucla-infrastructure-api/) — The Infrastructure API from University of California, Los Angeles — 1 operation(s) for infrastructure.
- [University of California, Los Angeles My UCLA API](https://apis.io/apis/ucla/ucla-myucla-api/) — The MyUCLA API from University of California, Los Angeles — 1 operation(s) for myucla.
- [University of California, Los Angeles Production Calendar Jobs API](https://apis.io/apis/ucla/ucla-production-calendar-jobs-api/) — The Production Calendar Jobs API from University of California, Los Angeles — 1 operation(s) for production calendar jobs.
- [University of California, Los Angeles Weather API](https://apis.io/apis/ucla/ucla-weather-api/) — The Weather API from University of California, Los Angeles — 14 operation(s) for weather.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ucla Agentic Access](https://apis.io/agentic-access/ucla/ucla-agentic-access/)

#### JSON Schema (7)

The data models the API reads and writes.

- [UCLA myUCLA menu data — schemas in use](https://apis.io/schemas/ucla/ucla-myucla-menu-data-schemas/)
- [UCLA sis classes — schemas in use](https://apis.io/schemas/ucla/ucla-sis-classes-schemas/)
- [UCLA sis courses — schemas in use](https://apis.io/schemas/ucla/ucla-sis-courses-schemas/)
- [UCLA sis dictionary — schemas in use](https://apis.io/schemas/ucla/ucla-sis-dictionary-schemas/)
- [UCLA sis production calendar jobs — schemas in use](https://apis.io/schemas/ucla/ucla-sis-production-calendar-jobs-schemas/)
- [UCLA sis verify connectivity — schemas in use](https://apis.io/schemas/ucla/ucla-sis-verify-connectivity-schemas/)
- [UCLA weather — schemas in use](https://apis.io/schemas/ucla/ucla-weather-schemas/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ucla Context](https://apis.io/jsonld/ucla/ucla-context/)

#### Examples (2)

Example requests and responses.

- [Ucla Apigee Invalid Token Error](https://apis.io/examples/ucla/ucla-apigee-invalid-token-error/)
- [Ucla Bruinlearn Lti Jwks](https://apis.io/examples/ucla/ucla-bruinlearn-lti-jwks/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [University of California, Los Angeles API Rules](https://apis.io/rules/ucla/ucla-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ucla Authentication](https://apis.io/security/ucla/ucla-authentication/)
- [Ucla Domain Security](https://apis.io/security/ucla/ucla-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Ucla Scopes](https://apis.io/scopes/ucla/ucla-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ucla Plans Pricing](https://apis.io/plans/ucla/ucla-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ucla Rate Limits](https://apis.io/rate-limits/ucla/ucla-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ucla Finops](https://apis.io/finops/ucla/ucla-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ucla.edu/)
- [Documentation](https://developer.api.ucla.edu/ucla-help)
- [API reference](https://developer.api.ucla.edu/api-catalog)
- [Support](https://developer.api.ucla.edu/ucla-help)
- [Blog](https://newsroom.ucla.edu/)
- [Terms of service](https://www.ucla.edu/terms-of-use)
- [Privacy policy](https://compliance.ucla.edu/privacy)
- [GitHub](https://github.com/ucla)

## API Evangelist rating

**Kin Score 41.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 58.2 |
| Contract governance | 3.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 45.2 |
| Access clarity | 39.5 |

**Agent readiness 23.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 34.3** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ucla/](https://apis.io/providers/ucla/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of California, Los Angeles: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ucla/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
