# Jotform (jotform)

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

Jotform is an online form builder with strong workflow, payments and data collection capabilities. The Jotform API exposes forms, submissions, reports, folders, users, files and webhooks across three regional/compliance endpoints (US standard, EU, HIPAA). API-key authentication via header or query string.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/jotform/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jotform/refs/heads/main/apis.yml)

## Tags

- Forms
- Surveys
- No-Code
- Data Collection
- Workflow
- HIPAA
- EU

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-30

## APIs

### Jotform REST API (Standard / US)

Standard Jotform API. Read/write access to forms, submissions, reports, folders, files, system, user and webhooks endpoints. APIKEY header authentication.

- **Human URL:** [https://api.jotform.com/docs/](https://api.jotform.com/docs/)
- **Base URL:** `https://api.jotform.com`

#### Tags

- REST
- Forms
- Submissions
- Webhooks

#### Properties

- [Documentation](https://api.jotform.com/docs/)
- [Authentication](https://api.jotform.com/docs/#authentication)
- [OpenAPI](openapi/jotform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jotform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jotform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/jotform-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [SDK](https://github.com/jotform)

### Jotform REST API (EU)

EU-resident variant of the Jotform API for customers on EU plans / EU data residency.

- **Human URL:** [https://api.jotform.com/docs/](https://api.jotform.com/docs/)
- **Base URL:** `https://eu-api.jotform.com`

#### Tags

- REST
- EU
- Data Residency

#### Properties

- [Postman Collection](collections/jotform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jotform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Jotform REST API (HIPAA)

HIPAA-compliant variant of the Jotform API for healthcare customers on Gold/Enterprise tiers.

- **Human URL:** [https://api.jotform.com/docs/](https://api.jotform.com/docs/)
- **Base URL:** `https://hipaa-api.jotform.com`

#### Tags

- REST
- HIPAA
- Healthcare

#### Properties

- [Postman Collection](collections/jotform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jotform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/jotform)
- [Website](https://www.jotform.com/)
- [Documentation](https://api.jotform.com/docs/)
- [Pricing](https://www.jotform.com/pricing/)
- [Git Hub](https://github.com/jotform)
- [Status Page](https://status.jotform.com/)
- [Plans](plans/jotform-plans-pricing.yml)
- [Rate Limits](rate-limits/jotform-rate-limits.yml)
- [Fin Ops](finops/jotform-finops.yml)
- [Integrations](https://www.jotform.com/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
