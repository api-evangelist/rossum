# Rossum (rossum)

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
