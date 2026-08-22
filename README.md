# University of California, Los Angeles (ucla)

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

The University of California, Los Angeles (UCLA) is a public land-grant research university in the University of California system, ranked 29th in the QS World University Rankings. It is one of the few institutions in this cohort that genuinely runs a central API program rather than renting one: UCLA operates its own Apigee-fronted gateway at `api.ucla.edu` under a certificate issued to the university, and a developer portal at [developer.api.ucla.edu](https://developer.api.ucla.edu/) cataloguing eight API products, seven of which publish a complete, anonymously downloadable OpenAPI contract. UCLA also runs its own Shibboleth identity provider, registered by InCommon. What it does not run is any self-service path — every credential requires a UCLA logon and a human approval.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ucla/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ucla-api-evangelist&utm_content=repo

## Type

University / Public Research University — Index / Consumer / 3rd-Party

## Tags

University, Higher Education, Education, United States, California, UC System, Public Research University, Course Catalog, Student Information, Identity Federation, Research Repository, Library, IIIF, Campus Life

## Who operates what

Every surface below carries an `x-operator` in `apis.yml`. A university is a federation of buyers, and the question that matters is not whether a specification exists but who runs the thing it describes.

| Surface | Operator | Evidence |
|---|---|---|
| Six SIS APIs + Weather API | **institution** | `servers[]` on `api.ucla.edu`; TLS `O=University of California, Los Angeles` |
| Shibboleth IdP | **institution** | `entityID urn:mace:incommon:ucla.edu`, scope `ucla.edu`, endpoints on `shb.ais.ucla.edu` |
| Library IIIF (Cantaloupe) | **institution** | UCLA-issued TLS; self-hosted on UCLA Library's own AWS account |
| Digital Collections | **institution** | UCLA IP, UCLA-issued TLS, no vendor CNAME |
| UCLA Dataverse | **institution** | UCLA-issued TLS, no vendor CNAME, self-installed open-source Dataverse |
| BruinLearn | **tenant** | `bruinlearn.ucla.edu` CNAMEs to `ucla-vanity.instructure.com` |

## APIs

- **UCLA Classes API** — 6 operations. Classes and class sections for a term, including a dedicated UCLA Extension route. [Contract](openapi/ucla-sis-classes-openapi.yml) · [Docs](https://developer.api.ucla.edu/api/261)
- **UCLA Courses API** — 7 operations. Approved courses, requisites, diversity attributes and the General Education foundation structure. [Contract](openapi/ucla-sis-courses-openapi.yml) · [Docs](https://developer.api.ucla.edu/api/271)
- **UCLA Registrar Dictionary API** — 61 operations enumerating every coded value the other SIS APIs return. [Contract](openapi/ucla-sis-dictionary-openapi.yml) · [Docs](https://developer.api.ucla.edu/api/366)
- **UCLA Production Calendar Jobs API** — 1 operation. The Registrar's mainframe batch schedule. [Contract](openapi/ucla-sis-production-calendar-jobs-openapi.yml) · [Docs](https://developer.api.ucla.edu/api/281)
- **UCLA Verify Connectivity to SIS API** — 1 operation. A catalogued health check. [Contract](openapi/ucla-sis-verify-connectivity-openapi.yml) · [Docs](https://developer.api.ucla.edu/api/346)
- **MyUCLA Menu Data API** — 1 operation. The student portal navigation tree. [Contract](openapi/ucla-myucla-menu-data-openapi.yml) · [Docs](https://developer.api.ucla.edu/api/61)
- **UCLA Weather API** — 14 operations. Campus weather station observations. The only OpenAPI 3.0.3 contract UCLA publishes. [Contract](openapi/ucla-weather-openapi.yml) · [Docs](https://developer.api.ucla.edu/api/51)
- **UCLA Shibboleth Identity Provider** — SAML 1.1 + 2.0, REFEDS R&S, SIRTFI. [Federation record](identity-federation/ucla-identity-federation.yml)
- **UCLA Library IIIF Image Service** — Cantaloupe 5.0.5, IIIF Image API 2.x and 3.0.
- **UCLA Library Digital Collections** — bot-challenged; recorded, not credited.
- **UCLA Dataverse** — bot-challenged; recorded, not credited.
- **BruinLearn (Canvas LMS)** — tenant relationship, LTI 1.3.

91 operations across seven contracts, every one of them a read. None is callable without a UCLA-approved App Key.

## Notable findings

- The seven contracts are not linked anywhere on the portal. Each specification URL lives inside the `swaggerUIFormatter` block of the product page's `drupal-settings-json`. UCLA publishes no machine-readable index of its own catalog.
- **462 response keys** across the six SIS contracts are declared with a **leading space** — `" 400"`, `" 401"`, `" 500"`. A conformant Swagger 2.0 validator sees one declared response per operation and no error responses at all.
- The production gateway answers **500 with plain text** on any unrouted path; the QA gateway correctly answers 404 with a structured fault.
- UCLA Library's Cantaloupe IIIF server returns a **full Java stack trace naming its private S3 bucket** on every 403, including for a deliberate nonsense identifier.
- 175 parameter `description` fields contain a bare sample value (`"151"`, `"ENGCOMP"`, `"99F"`) instead of a description.
- The Weather contract's `info.description` points at `weather.atmos.ucla.edu`, which resolves in DNS but accepts no connection.

## Artifacts

- OpenAPI: [openapi/](openapi/) — with pristine pre-refine copies in [openapi/_original/](openapi/_original/)
- JSON Schema: [json-schema/](json-schema/) — the reachable schema subset per contract
- Identity Federation: [identity-federation/ucla-identity-federation.yml](identity-federation/ucla-identity-federation.yml)
- Authentication: [authentication/ucla-authentication.yml](authentication/ucla-authentication.yml)
- Scopes: [scopes/ucla-scopes.yml](scopes/ucla-scopes.yml)
- Errors: [errors/ucla-errors.yml](errors/ucla-errors.yml)
- Conformance: [conformance/ucla-conformance.yml](conformance/ucla-conformance.yml)
- Lifecycle: [lifecycle/ucla-lifecycle.yml](lifecycle/ucla-lifecycle.yml)
- Rules: [rules/ucla-rules.yml](rules/ucla-rules.yml)
- Vocabulary: [vocabulary/ucla-vocabulary.yml](vocabulary/ucla-vocabulary.yml)
- Agentic Access: [agentic-access/ucla-agentic-access.yml](agentic-access/ucla-agentic-access.yml)
- Examples: [examples/index.yml](examples/index.yml)
- JSON-LD: [json-ld/ucla-context.jsonld](json-ld/ucla-context.jsonld)
- Plans & Pricing: [plans/ucla-plans-pricing.yml](plans/ucla-plans-pricing.yml)
- Rate Limits: [rate-limits/ucla-rate-limits.yml](rate-limits/ucla-rate-limits.yml)
- FinOps: [finops/ucla-finops.yml](finops/ucla-finops.yml)
- Review: [review.yml](review.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.ucla.edu/
- Developer Portal: https://developer.api.ucla.edu/
- Identity Federation: https://mdq.incommon.org/entities/urn%3Amace%3Aincommon%3Aucla.edu
- Course Catalog: https://catalog.registrar.ucla.edu/
- Research Repository: https://dataverse.ucla.edu/
- Research Computing: https://oarc.ucla.edu/
- AI Policy: https://dts.ucla.edu/initiatives/ai/ai-use-policy-guide
- GitHub: https://github.com/ucla · https://github.com/UCLALibrary
- LinkedIn: https://www.linkedin.com/school/ucla/

## Notes

Re-profiled on 2026-08-19 under the API Evangelist university pipeline, which settles operator attribution before saving any contract. Roughly 60 URLs were fetched across 15 hosts. Nothing was removed — UCLA held no vendor-attributed contract to strip, because the June 2026 profile had saved no contracts at all. Six surfaces were added and BruinLearn was newly recorded as a tenant relationship rather than credited to UCLA. `dataverse.ucla.edu` and `digital.library.ucla.edu` answer HTTP 200 with an Anubis proof-of-work bot challenge on every path, so OAI-PMH conformance could not be read and is not claimed.

## Maintainers

- Kin Lane — kin@apievangelist.com
