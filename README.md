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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of California, Los Angeles (UCLA) is a public land-grant research university ranked #30 in the QS World University Rankings 2025. UCLA operates a centralized API Developer Portal at [developer.api.ucla.edu](https://developer.api.ucla.edu/) that publishes a catalog of campus APIs covering student information, course and class data, the Registrar data dictionary, MyUCLA menu data, and enterprise integration services. Most products are documented but gated behind an access request and approval workflow, and UCLA Library additionally exposes IIIF-compliant digital collections manifests.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ucla/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ucla-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Student Information, Course Catalog, Library, IIIF, United States, California

## APIs

- **Classes API** — Classes offered in a selected term with sections, meeting times, locations, enrollment, units and instructors. [Docs](https://developer.api.ucla.edu/api/261)
- **Courses API** — All approved courses (current and historical) with descriptions, GE/diversity attributes and requisites. [Docs](https://developer.api.ucla.edu/api/271)
- **Dictionary API** — General data dictionary information and descriptions from the Registrar's Office. [Docs](https://developer.api.ucla.edu/api/366)
- **MyUCLA Menu Data API** — Information needed to build the MyUCLA megamenu. [Docs](https://developer.api.ucla.edu/api/61)
- **Production Calendar Jobs API** — Information about production calendar operations and scheduled jobs. [Docs](https://developer.api.ucla.edu/api/281)
- **UCLA Library Digital Collections IIIF** — IIIF JSON manifests for high-resolution digital collections imagery. [Docs](https://guides.library.ucla.edu/digital-collections/iiif)

Note: Most portal APIs require an approved access request and App Key/secret credentials; production base URLs are not publicly published.

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/ucla-plans-pricing.yml](plans/ucla-plans-pricing.yml)
- Rate Limits: [rate-limits/ucla-rate-limits.yml](rate-limits/ucla-rate-limits.yml)
- FinOps: [finops/ucla-finops.yml](finops/ucla-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ucla.edu/
- Developer Portal: https://developer.api.ucla.edu/
- GitHub: https://github.com/ucla
- LinkedIn: https://www.linkedin.com/school/ucla/

## Notes

All listed documentation URLs were probed live and returned HTTP 200 on 2026-06-03. The developer-pilot portal (developer-pilot.api.ucla.edu) did not resolve from outside the campus network. Portal API endpoints are gated behind an approval workflow, so no base URLs were fabricated. The IIIF library service is the one openly reachable data interface.

## Maintainers

- Kin Lane — kin@apievangelist.com
