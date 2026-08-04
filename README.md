# Printful (printful)

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

Printful is a print-on-demand and order-fulfillment platform that lets merchants design custom products and have them produced and shipped on demand. The Printful API (v2 and v1) exposes the product catalog, store products, order management, file library, mockup generator, shipping rates, warehouse products, and webhooks over a REST interface authenticated with OAuth 2.0 / Bearer tokens.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/printful/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/printful/refs/heads/main/apis.yml)

## Tags

- Print on Demand
- Fulfillment
- Ecommerce
- Dropshipping
- Merchandise

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Printful Catalog API

Browse Printful's print-on-demand catalog - products, variants, prices, sizes, images, availability, categories, and mockup styles/templates.

- **Human URL:** [https://developers.printful.com/docs/v2-beta/](https://developers.printful.com/docs/v2-beta/)
- **Base URL:** `https://api.printful.com/v2`

#### Tags

- Catalog
- Products
- Variants

#### Properties

- [Documentation](https://developers.printful.com/docs/v2-beta/)
- [API Reference](https://developers.printful.com/docs/v2-beta/)
- [OpenAPI](openapi/printful-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Printful Store Products API

Manage the products synced into a connected store, including store product and store variant records that map catalog items to a merchant's storefront.

- **Human URL:** [https://developers.printful.com/docs/](https://developers.printful.com/docs/)
- **Base URL:** `https://api.printful.com`

#### Tags

- Store Products
- Sync
- Variants

#### Properties

- [Documentation](https://developers.printful.com/docs/)
- [OpenAPI](openapi/printful-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Printful Orders API

Create, update, confirm, and manage orders and order items for on-demand fulfillment, plus order cost estimation tasks and shipment tracking.

- **Human URL:** [https://developers.printful.com/docs/v2-beta/](https://developers.printful.com/docs/v2-beta/)
- **Base URL:** `https://api.printful.com/v2`

#### Tags

- Orders
- Fulfillment
- Order Items

#### Properties

- [Documentation](https://developers.printful.com/docs/v2-beta/)
- [OpenAPI](openapi/printful-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Printful Files API

Upload and retrieve print files in the Printful file library for use on products and orders.

- **Human URL:** [https://developers.printful.com/docs/v2-beta/](https://developers.printful.com/docs/v2-beta/)
- **Base URL:** `https://api.printful.com/v2`

#### Tags

- Files
- File Library
- Uploads

#### Properties

- [Documentation](https://developers.printful.com/docs/v2-beta/)
- [OpenAPI](openapi/printful-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Printful Mockup Generator API

Generate product mockup images asynchronously via mockup tasks, using catalog mockup styles and templates.

- **Human URL:** [https://developers.printful.com/docs/v2-beta/](https://developers.printful.com/docs/v2-beta/)
- **Base URL:** `https://api.printful.com/v2`

#### Tags

- Mockup Generator
- Mockups
- Images

#### Properties

- [Documentation](https://developers.printful.com/docs/v2-beta/)
- [OpenAPI](openapi/printful-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Printful Shipping Rates API

Calculate available shipping rates and delivery options for a set of items shipped to a given destination.

- **Human URL:** [https://developers.printful.com/docs/v2-beta/](https://developers.printful.com/docs/v2-beta/)
- **Base URL:** `https://api.printful.com/v2`

#### Tags

- Shipping
- Rates
- Logistics

#### Properties

- [Documentation](https://developers.printful.com/docs/v2-beta/)
- [OpenAPI](openapi/printful-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Printful Warehouse API

List and retrieve warehouse products - merchant-owned inventory stored in Printful warehouses for pick, pack, and ship fulfillment.

- **Human URL:** [https://developers.printful.com/docs/v2-beta/](https://developers.printful.com/docs/v2-beta/)
- **Base URL:** `https://api.printful.com/v2`

#### Tags

- Warehouse
- Inventory
- Products

#### Properties

- [Documentation](https://developers.printful.com/docs/v2-beta/)
- [OpenAPI](openapi/printful-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Printful Webhooks API

Configure webhook endpoints and per-event subscriptions to receive push notifications for order, shipment, and product lifecycle events.

- **Human URL:** [https://developers.printful.com/docs/v2-beta/](https://developers.printful.com/docs/v2-beta/)
- **Base URL:** `https://api.printful.com/v2`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developers.printful.com/docs/v2-beta/)
- [OpenAPI](openapi/printful-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/printful.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/printful.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/printful)
- [LinkedIn](https://www.linkedin.com/company/printful)
- [Website](https://www.printful.com)
- [Documentation](https://developers.printful.com/docs/)
- [Plans](plans/printful-plans-pricing.yml)
- [Rate Limits](rate-limits/printful-rate-limits.yml)
- [Fin Ops](finops/printful-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
