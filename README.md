# Rossum (rossum)

Rossum is an AI-powered document processing platform specialised in transactional documents — invoices, purchase orders, contracts — with cognitive data capture, validation workflows and integration extensions. The Rossum REST API is exposed across two deployment domains: the legacy elis.rossum.ai and per-tenant rossum.app.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **REST v1 (legacy)** — `https://api.elis.rossum.ai/v1` — organizations, users, workspaces, queues, schemas, documents, annotations, hooks. Token auth (~162h tokens). [Docs](https://elis.rossum.ai/api/docs/).
- **Tenant API (newer)** — `https://<tenant>.rossum.app/api/v1` — same surface, served from each customer's tenant subdomain.

## OpenAPI
Rossum publishes interactive API documentation but does not host a downloadable OpenAPI/Swagger document at a public anonymous URL as of 2026-05-08; pipeline did not retrieve a spec into `openapi/`. Python SDK and CLI are open source under github.com/rossumai.

## Tags
AI, Document AI, IDP, Invoices, OCR, Workflow, AP Automation

## Common Properties
- [Website](https://rossum.ai/) · [API Docs](https://elis.rossum.ai/api/docs/) · [Developer Hub](https://developers.rossum.ai/) · [Pricing](https://rossum.ai/pricing/)
- [GitHub](https://github.com/rossumai)
- [Plans](plans/rossum-plans-pricing.yml) — partially reconciled (Starter $18K/yr; higher tiers via sales)
- [Rate Limits](rate-limits/rossum-rate-limits.yml) — reconciled (10 req/s)
- [FinOps](finops/rossum-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
- **Starter** — from $18,000/yr; unlimited seats, ingestion, extraction, validation, API access.
- **Business** — adds custom logic, master data matching, intelligent mailbox, ERP integrations.
- **Enterprise (Recommended)** — adds SSO, sandbox, document translation, custom branding.
- **Ultimate** — multi-document, custom email domains, embeddable, 3-year archive.
- One-year minimum; per-page overage above bundle.

## Rate Limits (reconciled)
- 10 req/s general endpoints.
- 10 req/min on page-spatial-data translation.
- 40 MB max upload size; 429 + Retry-After.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
