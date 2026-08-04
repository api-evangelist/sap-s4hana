# SAP S/4HANA (sap-s4hana)

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

Collection of SAP S/4HANA Cloud and On-Premise APIs for enterprise resource planning.

**APIs.json:** [https://api.sap.com/apis.json](https://api.sap.com/apis.json)

## Tags

- Business Applications
- Cloud
- Enterprise Resource Planning
- ERP
- Finance
- Human Resources
- Inventory
- Logistics
- Manufacturing
- Plant Maintenance
- Procurement
- S/4HANA
- Sales
- SAP

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### SAP S/4HANA Business Partner API

API for creating, reading, updating, and deleting business partner master data.

#### Tags

- Business Partner
- Customer
- ERP
- Master Data
- Supplier

#### Properties

- [OpenAPI](https://api.sap.com/api/API_BUSINESS_PARTNER/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/873c58e32fa642eea4ffb53d80819fa3.html)
- [Console](https://api.sap.com/api/API_BUSINESS_PARTNER/tryout)
- [Authentication](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/26f2b5aa3f3a4019b7d08978095b9e6a.html)
- [API Reference](https://api.sap.com/api/API_BUSINESS_PARTNER/resource)
- [JSON Schema](https://api.sap.com/api/API_BUSINESS_PARTNER/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Sales Order API

API for managing sales orders including creation, updates, and status changes.

#### Tags

- ERP
- Order Management
- Sales
- Sales Order

#### Properties

- [OpenAPI](openapi/sap-s4hana-sales-order-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sap-s4hana-sales-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/sap-s4hana-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [OpenAPI](https://api.sap.com/api/API_SALES_ORDER_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/cd99a61e5e3f45789c954055c1e31de0/46e2b3e1e0d44419b86e4f0f6e90a0c9.html)
- [Console](https://api.sap.com/api/API_SALES_ORDER_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_SALES_ORDER_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_SALES_ORDER_SRV/schema) — [JSON Schema](https://json-schema.org/specification)

### SAP S/4HANA Purchase Order API

API for creating and managing purchase orders in procurement processes.

#### Tags

- ERP
- Procurement
- Purchase Order
- Purchasing

#### Properties

- [OpenAPI](https://api.sap.com/api/API_PURCHASEORDER_PROCESS_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/68bf513d4c6742ddb5c0268d46b48b7c/7e0da70d14b44e0cac79c2a29c21b695.html)
- [Console](https://api.sap.com/api/API_PURCHASEORDER_PROCESS_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_PURCHASEORDER_PROCESS_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_PURCHASEORDER_PROCESS_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Material Document API

API for posting goods movements and managing inventory transactions.

#### Tags

- ERP
- Goods Movement
- Inventory
- Material Document
- Warehouse

#### Properties

- [OpenAPI](https://api.sap.com/api/API_MATERIAL_DOCUMENT_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0dd0e7f348b04fc7b4e6e63bc9e1db9f/e5ced76872764cbbb8d78e81e21e7f35.html)
- [Console](https://api.sap.com/api/API_MATERIAL_DOCUMENT_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_MATERIAL_DOCUMENT_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_MATERIAL_DOCUMENT_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Product Master API

API for managing product and material master data.

#### Tags

- ERP
- Master Data
- Material
- Product

#### Properties

- [OpenAPI](https://api.sap.com/api/API_PRODUCT_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/48a7b615c24444a9b3a6f2810f88db71.html)
- [Console](https://api.sap.com/api/API_PRODUCT_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_PRODUCT_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_PRODUCT_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Journal Entry API

API for creating and managing financial journal entries.

#### Tags

- Accounting
- ERP
- Finance
- General Ledger
- Journal Entry

#### Properties

- [OpenAPI](https://api.sap.com/api/API_JOURNALENTRY_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/b8c083f8f1614da6bf6f7a6e06c4f9be/e0f6c2e84e214c8c8d77a24b40a11ae8.html)
- [Console](https://api.sap.com/api/API_JOURNALENTRY_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_JOURNALENTRY_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_JOURNALENTRY_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Billing Document API

API for reading, canceling, and retrieving PDFs of billing documents in sales and distribution.

#### Tags

- Billing
- ERP
- Finance
- Invoice
- Sales

#### Properties

- [OpenAPI](https://api.sap.com/api/API_BILLING_DOCUMENT_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/03c04db2a7434731b7fe21dca77440da/65680dabb62546029175655482f85edc.html)
- [Console](https://api.sap.com/api/API_BILLING_DOCUMENT_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_BILLING_DOCUMENT_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_BILLING_DOCUMENT_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Supplier Invoice API

API for creating and processing supplier invoices referenced to purchase orders.

#### Tags

- Accounts Payable
- ERP
- Finance
- Procurement
- Supplier Invoice

#### Properties

- [OpenAPI](https://api.sap.com/api/API_SUPPLIERINVOICE_PROCESS_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0864cb07010642b3bde45a20de4975bc/8ddf1d448ce74a799390a1706d90ca3d.html)
- [Console](https://api.sap.com/api/API_SUPPLIERINVOICE_PROCESS_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_SUPPLIERINVOICE_PROCESS_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_SUPPLIERINVOICE_PROCESS_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Customer Return API

API for integrating external applications with customer return processing including advanced returns management.

#### Tags

- Customer Return
- ERP
- Logistics
- Returns Management
- Sales

#### Properties

- [OpenAPI](https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/03c04db2a7434731b7fe21dca77440da/69bd2e81cb394eb0b3d8eae85d6b4517.html)
- [Console](https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Purchase Requisition API

API for creating, updating, and managing purchase requisitions in procurement workflows.

#### Tags

- ERP
- Procurement
- Purchase Requisition
- Purchasing

#### Properties

- [OpenAPI](https://api.sap.com/api/API_PURCHASEREQ_PROCESS_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Console](https://api.sap.com/api/API_PURCHASEREQ_PROCESS_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_PURCHASEREQ_PROCESS_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_PURCHASEREQ_PROCESS_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Outbound Delivery API

API for creating, reading, updating, and deleting outbound deliveries including goods issue and picking operations.

#### Tags

- ERP
- Logistics
- Outbound Delivery
- Shipping
- Warehouse

#### Properties

- [OpenAPI](https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/588780cab2774a7ab9fffca3a7f919fe/113abb06f3fe4e94987d35d5f86ba1ac.html)
- [Console](https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/tryout)
- [API Reference](https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/resource)
- [JSON Schema](https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Inbound Delivery API

API for creating, reading, updating, and deleting inbound deliveries for procurement and logistics.

#### Tags

- ERP
- Inbound Delivery
- Logistics
- Receiving
- Warehouse

#### Properties

- [OpenAPI](https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/588780cab2774a7ab9fffca3a7f919fe/f3ff58c5e7ec43c7b55a503be6633567.html)
- [Console](https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/tryout)
- [API Reference](https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/resource)
- [JSON Schema](https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Cost Center API

API for reading cost center master data used in controlling and cost management.

#### Tags

- Controlling
- Cost Center
- ERP
- Finance
- Master Data

#### Properties

- [OpenAPI](https://api.sap.com/api/API_COSTCENTER_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/6b39bd1d0e5e4099a5b65d835c29c696/5792333ddf3c47eaad4314b071dfd684.html)
- [Console](https://api.sap.com/api/API_COSTCENTER_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_COSTCENTER_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_COSTCENTER_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA GL Account API

API for reading general ledger account master data in chart of accounts.

#### Tags

- Accounting
- ERP
- Finance
- General Ledger
- GL Account
- Master Data

#### Properties

- [OpenAPI](https://api.sap.com/api/API_GLACCOUNTINCHARTOFACCOUNTS_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Console](https://api.sap.com/api/API_GLACCOUNTINCHARTOFACCOUNTS_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_GLACCOUNTINCHARTOFACCOUNTS_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_GLACCOUNTINCHARTOFACCOUNTS_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Bank Master API

API for reading bank master data including bank keys, SWIFT codes, and bank details.

#### Tags

- Bank
- ERP
- Finance
- Master Data
- Payment

#### Properties

- [OpenAPI](https://api.sap.com/api/API_BANKDETAIL_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_ON-PREMISE/e296651f454c4284ade361292c633d69/1de6770532554d43a1d026f57e7dd46e.html)
- [Console](https://api.sap.com/api/API_BANKDETAIL_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_BANKDETAIL_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_BANKDETAIL_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Production Order API

API for reading production order data including components, operations, and status information.

#### Tags

- ERP
- Manufacturing
- Production Order
- Production Planning

#### Properties

- [OpenAPI](https://api.sap.com/api/API_PRODUCTION_ORDER_2_SRV/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Console](https://api.sap.com/api/API_PRODUCTION_ORDER_2_SRV/tryout)
- [API Reference](https://api.sap.com/api/API_PRODUCTION_ORDER_2_SRV/resource)
- [JSON Schema](https://api.sap.com/api/API_PRODUCTION_ORDER_2_SRV/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Maintenance Order API

API for reading maintenance order data used in plant maintenance and enterprise asset management.

#### Tags

- Asset Management
- ERP
- Maintenance Order
- Plant Maintenance

#### Properties

- [OpenAPI](https://api.sap.com/api/API_MAINTENANCEORDER/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/2dfa044a255f49e89a3050daf3c61c11/ff951ebb44664d87b2a8db9290a41dc2.html)
- [Console](https://api.sap.com/api/API_MAINTENANCEORDER/tryout)
- [API Reference](https://api.sap.com/api/API_MAINTENANCEORDER/resource)
- [JSON Schema](https://api.sap.com/api/API_MAINTENANCEORDER/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP S/4HANA Workforce Timesheet API

API for creating, reading, updating, and deleting workforce timesheet entries with automatic posting to controlling.

#### Tags

- ERP
- Human Resources
- Time Management
- Timesheet
- Workforce

#### Properties

- [OpenAPI](https://api.sap.com/api/API_MANAGE_WORKFORCE_TIMESHEET/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/b08cb360201544ec803330fefa59b0f7/fa198e62c6d24788bd1f82082feb3096.html)
- [Console](https://api.sap.com/api/API_MANAGE_WORKFORCE_TIMESHEET/tryout)
- [API Reference](https://api.sap.com/api/API_MANAGE_WORKFORCE_TIMESHEET/resource)
- [JSON Schema](https://api.sap.com/api/API_MANAGE_WORKFORCE_TIMESHEET/schema) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sap-s4hana-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-s4hana-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/SAP)
- [LinkedIn](https://www.linkedin.com/showcase/sap-s-4hana)
- [Portal](https://api.sap.com)
- [Getting Started](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/1e45cfd73e814aa6b1a1118e2c1d3cec.html)
- [Authentication](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/26f2b5aa3f3a4019b7d08978095b9e6a.html)
- [Changelog](https://api.sap.com/releasenotes)
- [Support](https://support.sap.com)
- [Terms of Service](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html)
- [Privacy Policy](https://www.sap.com/about/legal/privacy.html)
- [A P I  Catalog](https://api.sap.com/products/SAPS4HANACloud/apis/all)
- [A P I  Packages](https://api.sap.com/products/SAPS4HANACloud/apis/packages)
- [O Data  V4  A P Is](https://api.sap.com/products/SAPS4HANACloud/apis/ODATAV4)
- [R E S T  A P Is](https://api.sap.com/products/SAPS4HANACloud/apis/REST)
- [On- Premise  A P I  Catalog](https://api.sap.com/products/SAPS4HANA/apis/all)
- [On- Premise  A P I  Packages](https://api.sap.com/products/SAPS4HANA/apis/packages)
- [Private  Edition  A P Is](https://api.sap.com/products/SAPS4HANACloudPrivateEdition/apis/packages)
- [Community](https://community.sap.com/t5/enterprise-resource-planning-blog-posts-by-sap/sap-s-4hana-apis-and-where-to-find-them/ba-p/13723939)
- [Status Page](https://www.sap.com/about/cloud-trust-center/cloud-service-status.html)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
