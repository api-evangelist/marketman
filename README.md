# MarketMan (marketman)

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

MarketMan is a cloud-based restaurant inventory and purchasing management platform (part of the Meal Ticket portfolio) for back-of-house operations - inventory counts, supplier catalogs, purchase orders, deliveries, invoices, recipes/menu costing, and POS sales. The MarketMan API V3 is a JSON REST API with separate Buyer and Vendor surfaces, token authentication, and webhooks for order events.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/marketman/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/marketman/refs/heads/main/apis.yml)

## Tags

- Restaurant
- Inventory
- Purchasing
- Supply Chain
- Food Service

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### MarketMan Inventory & Items API

Buyer inventory endpoints for retrieving items, preps, inventory items, menu items and UOM types, setting inventory counts, and reading transfers, waste events, and production events.

- **Human URL:** [https://api-doc.marketman.com/](https://api-doc.marketman.com/)
- **Base URL:** `https://api.marketman.com/v3`

#### Tags

- Inventory
- Items
- Menu Items

#### Properties

- [Documentation](https://api-doc.marketman.com/)
- [OpenAPI](openapi/marketman-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/marketman.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marketman.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MarketMan Vendors API

Buyer endpoint for listing the vendors (suppliers) connected to an account, plus the vendor-side products, assortments, price levels, and customers surfaces used by suppliers integrating with MarketMan.

- **Human URL:** [https://api-doc.marketman.com/](https://api-doc.marketman.com/)
- **Base URL:** `https://api.marketman.com/v3`

#### Tags

- Vendors
- Suppliers
- Catalog

#### Properties

- [Documentation](https://api-doc.marketman.com/)
- [OpenAPI](openapi/marketman-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/marketman.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marketman.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MarketMan Purchase Orders API

Buyer orders endpoints to read orders by delivery date or sent date, list vendor catalog items, and create purchase orders against a vendor catalog.

- **Human URL:** [https://api-doc.marketman.com/](https://api-doc.marketman.com/)
- **Base URL:** `https://api.marketman.com/v3`

#### Tags

- Purchase Orders
- Orders
- Procurement

#### Properties

- [Documentation](https://api-doc.marketman.com/)
- [OpenAPI](openapi/marketman-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/marketman.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marketman.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MarketMan Invoices & Docs API

Buyer docs endpoints to retrieve invoices and accounting documents by document date and to mark documents as exported for downstream accounting/ERP reconciliation.

- **Human URL:** [https://api-doc.marketman.com/](https://api-doc.marketman.com/)
- **Base URL:** `https://api.marketman.com/v3`

#### Tags

- Invoices
- Documents
- Accounting

#### Properties

- [Documentation](https://api-doc.marketman.com/)
- [OpenAPI](openapi/marketman-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/marketman.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marketman.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MarketMan Deliveries API

Vendor-side delivery note endpoints (GetDeliveryNotesByDate, ValidateDoc, SetDocs) used to submit and retrieve delivery documents tied to fulfilled orders.

- **Human URL:** [https://api-doc.marketman.com/](https://api-doc.marketman.com/)
- **Base URL:** `https://api.marketman.com/v3`

#### Tags

- Deliveries
- Delivery Notes
- Receiving

#### Properties

- [Documentation](https://api-doc.marketman.com/)
- [OpenAPI](openapi/marketman-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/marketman.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marketman.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MarketMan Recipes & Menu Profitability API

Menu and recipe costing endpoints - menu items, menu item availability, and menu profitability reporting - that surface recipe-driven food cost and margin data for an account.

- **Human URL:** [https://api-doc.marketman.com/](https://api-doc.marketman.com/)
- **Base URL:** `https://api.marketman.com/v3`

#### Tags

- Recipes
- Menu Costing
- Profitability

#### Properties

- [Documentation](https://api-doc.marketman.com/)
- [OpenAPI](openapi/marketman-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/marketman.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marketman.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MarketMan Webhooks API

Buyer and vendor webhook management - create, list, and delete webhooks and look up webhook events by order - to subscribe to order-create and related events.

- **Human URL:** [https://api-doc.marketman.com/](https://api-doc.marketman.com/)
- **Base URL:** `https://api.marketman.com/v3`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://api-doc.marketman.com/)
- [OpenAPI](openapi/marketman-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/marketman.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/marketman.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/marketman)
- [Website](https://www.marketman.com)
- [Documentation](https://api-doc.marketman.com/)
- [Plans](plans/marketman-plans-pricing.yml)
- [Rate Limits](rate-limits/marketman-rate-limits.yml)
- [Fin Ops](finops/marketman-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
