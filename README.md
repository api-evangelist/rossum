# Rossum (rossum)

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

Rossum is an AI-powered document processing platform specialised in transactional documents — invoices, purchase orders, contracts — with cognitive data capture, validation workflows and integration extensions. The Rossum REST API exposes organizations, users, workspaces, queues, schemas, annotations, documents and hooks/extensions across two deployment domains (legacy elis.rossum.ai and the newer per-tenant rossum.app).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rossum/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rossum/refs/heads/main/apis.yml)

## Tags

- AI
- Document AI
- IDP
- Invoices
- OCR
- Workflow
- AP Automation

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Rossum REST API v1

REST API for managing organizations, users, workspaces, queues, schemas, documents, annotations and webhook/serverless extensions (hooks). Token authentication; access tokens valid ~162 hours by default. Supports PDF/PNG/JPEG/TIFF/XLSX/DOCX/HTML uploads up to 40 MB.

- **Human URL:** [https://elis.rossum.ai/api/docs/](https://elis.rossum.ai/api/docs/)
- **Base URL:** `https://api.elis.rossum.ai/v1`

#### Tags

- REST
- Annotations
- Queues
- Schemas
- Hooks

#### Properties

- [Documentation](https://elis.rossum.ai/api/docs/)
- [API Reference](https://api.elis.rossum.ai/docs/)
- [Developer Hub](https://developers.rossum.ai/)
- [S D K Python](https://github.com/rossumai/rossum-api)
- [S D K C L I](https://github.com/rossumai/rossum)
- [Postman Collection](collections/rossum.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rossum.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rossum Tenant API (rossum.app)

Same REST surface served from each customer's tenant subdomain (https://<tenant>.rossum.app/api/v1/) for organisations created after November 2022 or migrated to the new platform.

- **Human URL:** [https://rossum.app/api/docs/openapi/guides/getting-started/](https://rossum.app/api/docs/openapi/guides/getting-started/)
- **Base URL:** `https://<tenant>.rossum.app/api/v1`

#### Tags

- REST
- Tenant
- Multi-region

#### Properties

- [Postman Collection](collections/rossum.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rossum.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rossum)
- [Website](https://rossum.ai/)
- [Documentation](https://elis.rossum.ai/api/docs/)
- [Developer Hub](https://developers.rossum.ai/)
- [Pricing](https://rossum.ai/pricing/)
- [Git Hub](https://github.com/rossumai)
- [Plans](plans/rossum-plans-pricing.yml)
- [Rate Limits](rate-limits/rossum-rate-limits.yml)
- [Fin Ops](finops/rossum-finops.yml)
- [Integrations](https://rossum.ai/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
