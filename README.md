# eSIM Go (esimgo)

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
