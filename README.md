# MarketMan (marketman)

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
