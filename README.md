# Lexion (lexion)

Lexion is an AI-powered contract lifecycle management (CLM) platform that centralizes agreements in an intelligent repository, extracts key terms and dates, and drives no-code intake and approval workflows across legal, sales, procurement, finance, and HR. Founded in 2019 out of the Allen Institute for AI, Lexion was acquired by Docusign in May 2024 for ~$165M and folded into Docusign's Intelligent Agreement Management (IAM) platform and Docusign Navigator. Lexion exposes an enterprise, sales-led integration API but does not publish a self-serve, openly documented public API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lexion/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lexion/refs/heads/main/apis.yml)

## API Availability

Lexion advertises a custom integration **API** to push contract terms and metadata into external systems (NetSuite, Coupa, and others), but it is an **enterprise, sales-led** offering. As of this writing there is **no self-serve, openly documented public REST API** — no published base URL, authentication scheme, or endpoint reference. Lexion was **acquired by Docusign in May 2024** (~$165M) and is being folded into Docusign's Intelligent Agreement Management (IAM) platform and Docusign Navigator; net-new developer/API surface is increasingly delivered through Docusign's developer platform. This catalog documents Lexion's product surfaces honestly; the OpenAPI artifact intentionally carries an empty `paths: {}` because no public endpoints are documented.

## Tags

- Contract Management
- CLM
- AI
- Legal Tech
- Document Extraction
- Workflow

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Lexion Contract Repository

Centralized intelligent repository for agreements, surfacing contracts, parties, key dates, and metadata. Lexion offers an enterprise integration API to push contract terms and metadata into external systems, but no self-serve public REST reference, base URL, or endpoint catalog is published; access is sales-led.

- **Human URL:** [https://www.lexion.ai/integrations/api](https://www.lexion.ai/integrations/api)

#### Tags

- Contracts
- Repository
- Metadata

#### Properties

- [Documentation](https://www.lexion.ai/integrations/api)
- [OpenAPI](openapi/lexion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lexion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lexion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lexion Extraction & Insights

AI-based extraction of clauses, key terms, renewal dates, and contract insights, plus AI Contract Assist for review against playbooks. Surfaced through the Lexion product and its enterprise integration API; no openly documented public extraction endpoints are published.

- **Human URL:** [https://www.lexion.ai/integrations/api](https://www.lexion.ai/integrations/api)

#### Tags

- AI
- Extraction
- Insights

#### Properties

- [Documentation](https://www.lexion.ai/integrations/api)
- [OpenAPI](openapi/lexion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lexion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lexion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lexion Workflows

No-code intake, approval, document-generation, and routing workflows, with email-, Slack-, and Microsoft Teams-driven request submission. Workflow automation is configured in-product; no openly documented public workflow API surface is published.

- **Human URL:** [https://www.lexion.ai/integrations/api](https://www.lexion.ai/integrations/api)

#### Tags

- Workflow
- Intake
- Automation

#### Properties

- [Documentation](https://www.lexion.ai/integrations/api)
- [OpenAPI](openapi/lexion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lexion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lexion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lexion Integrations

Pre-built connectors for Email, Microsoft Word, Salesforce, HubSpot, Slack, Microsoft Teams, Coupa, NetSuite, and DocuSign, plus a custom integration API for connecting Lexion to other business systems. The custom API is enterprise and sales-led, without a published self-serve developer reference.

- **Human URL:** [https://www.lexion.ai/integrations/api](https://www.lexion.ai/integrations/api)

#### Tags

- Integrations
- Salesforce
- DocuSign

#### Properties

- [Documentation](https://www.lexion.ai/integrations/api)
- [OpenAPI](openapi/lexion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lexion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lexion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/lexion)
- [Website](https://www.lexion.ai)
- [Documentation](https://www.lexion.ai/integrations/api)
- [Plans](plans/lexion-plans-pricing.yml)
- [Rate Limits](rate-limits/lexion-rate-limits.yml)
- [Fin Ops](finops/lexion-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
