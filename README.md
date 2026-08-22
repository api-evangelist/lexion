# Lexion (lexion)

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
