# eSIM Go (esimgo)

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

eSIM Go is an eSIM connectivity and travel-data platform that lets resellers and brands launch their own eSIM products. Its REST API aggregates tier-1 telecom services across 190+ countries, exposing a data-bundle catalogue, order placement, eSIM assignment, install/QR provisioning, inventory, network coverage, and usage webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/esimgo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/esimgo/refs/heads/main/apis.yml)

## Tags

- eSIM
- Connectivity
- Travel Data
- Telecom
- Mobile

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### eSIM Go Catalogue API

Lists data bundles available to your organisation for ordering, with filtering by country, region, group, and description, plus per-bundle detail by name including data amount, duration, coverage, and price.

- **Human URL:** [https://docs.esim-go.com/api/v2_4/operations/catalogue/get/](https://docs.esim-go.com/api/v2_4/operations/catalogue/get/)
- **Base URL:** `https://api.esim-go.com/v2.4`

#### Tags

- Catalogue
- Bundles
- Data Plans

#### Properties

- [Documentation](https://docs.esim-go.com/api/v2_4/operations/catalogue/get/)
- [API Reference](https://docs.esim-go.com/api/v2_4/operations/catalogue/get/)
- [OpenAPI](openapi/esimgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/esimgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/esimgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### eSIM Go Orders API

Validates and processes bundle orders, optionally assigning bundles to specified eSIM ICCIDs, with order listing and per-reference order detail retrieval.

- **Human URL:** [https://docs.esim-go.com/api/v2_4/operations/orders/post/](https://docs.esim-go.com/api/v2_4/operations/orders/post/)
- **Base URL:** `https://api.esim-go.com/v2.4`

#### Tags

- Orders
- Provisioning
- Bundles

#### Properties

- [Documentation](https://docs.esim-go.com/api/v2_4/operations/orders/post/)
- [API Reference](https://docs.esim-go.com/api/v2_4/operations/orders/post/)
- [OpenAPI](openapi/esimgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/esimgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/esimgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### eSIM Go eSIMs API

Manages eSIMs assigned to your organisation - list and detail, apply bundles, retrieve install details (matchingId, SM-DP+ address, Apple install URL, LPA QR data), history, location, SMS, and bundle revocation.

- **Human URL:** [https://docs.esim-go.com/api/v2_4/operations/esims/get/](https://docs.esim-go.com/api/v2_4/operations/esims/get/)
- **Base URL:** `https://api.esim-go.com/v2.4`

#### Tags

- eSIMs
- Assignments
- QR Install

#### Properties

- [Documentation](https://docs.esim-go.com/api/v2_4/operations/esims/get/)
- [API Reference](https://docs.esim-go.com/api/v2_4/operations/esimsassignments/get/)
- [OpenAPI](openapi/esimgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/esimgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/esimgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### eSIM Go Inventory API

Reports the unassigned bundle inventory held by your organisation and supports refunding an unused bundle back from inventory.

- **Human URL:** [https://docs.esim-go.com/api/v2_4/operations/inventory/get/](https://docs.esim-go.com/api/v2_4/operations/inventory/get/)
- **Base URL:** `https://api.esim-go.com/v2.4`

#### Tags

- Inventory
- Bundles
- Refund

#### Properties

- [Documentation](https://docs.esim-go.com/api/v2_4/operations/inventory/get/)
- [OpenAPI](openapi/esimgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/esimgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/esimgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### eSIM Go Network API

Returns per-country network coverage data, including the mobile networks and supported speeds available for eSIM connectivity in each market.

- **Human URL:** [https://docs.esim-go.com/api/v2_4/operations/networks/get/](https://docs.esim-go.com/api/v2_4/operations/networks/get/)
- **Base URL:** `https://api.esim-go.com/v2.4`

#### Tags

- Network
- Coverage
- Countries

#### Properties

- [Documentation](https://docs.esim-go.com/api/v2_4/operations/networks/get/)
- [OpenAPI](openapi/esimgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/esimgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/esimgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### eSIM Go Webhooks

Server-to-server callbacks that POST eSIM usage and status events to a partner-configured callback URL, enabling real-time tracking of data consumption and bundle state changes.

- **Human URL:** [https://docs.esim-go.com/api/v2_4/](https://docs.esim-go.com/api/v2_4/)
- **Base URL:** `https://api.esim-go.com/v2.4`

#### Tags

- Webhooks
- Callbacks
- Usage

#### Properties

- [Documentation](https://docs.esim-go.com/api/v2_4/)
- [OpenAPI](openapi/esimgo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/esimgo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/esimgo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/esim-go)
- [Website](https://www.esim-go.com)
- [Documentation](https://docs.esim-go.com)
- [Plans](plans/esimgo-plans-pricing.yml)
- [Rate Limits](rate-limits/esimgo-rate-limits.yml)
- [Fin Ops](finops/esimgo-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
