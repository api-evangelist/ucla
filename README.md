# University of California, Los Angeles (ucla)

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
