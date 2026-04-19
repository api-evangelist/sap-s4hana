# SAP S/4HANA APIs (sap-s4hana)
Collection of SAP S/4HANA Cloud and On-Premise APIs for enterprise resource planning.

**URL:** [Visit APIs.json URL](https://api.sap.com/apis.json)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Business Applications, Cloud, Enterprise Resource Planning, ERP, Finance, Human Resources, Inventory, Logistics, Manufacturing, Plant Maintenance, Procurement, S/4HANA, Sales, SAP

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-18

## APIs

### SAP S/4HANA Sales Order API
API for managing sales orders including creation, updates, and status changes.

**Human URL:** [https://api.sap.com/api/API_SALES_ORDER_SRV/overview](https://api.sap.com/api/API_SALES_ORDER_SRV/overview)

#### Tags:

 - ERP, Order Management, Sales, Sales Order

#### Properties

- [OpenAPI](openapi/sap-s4hana-sales-order-openapi.yml)
- [JSONSchema](json-schema/sap-s4hana-sales-order-schema.json)
- [JSONLD](json-ld/sap-s4hana-context.jsonld)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD/cd99a61e5e3f45789c954055c1e31de0/46e2b3e1e0d44419b86e4f0f6e90a0c9.html)

## Common Properties

- [Portal](https://api.sap.com)
- [GettingStarted](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/1e45cfd73e814aa6b1a1118e2c1d3cec.html)
- [Authentication](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/26f2b5aa3f3a4019b7d08978095b9e6a.html)
- [ChangeLog](https://api.sap.com/releasenotes)
- [Support](https://support.sap.com)
- [TermsOfService](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html)
- [PrivacyPolicy](https://www.sap.com/about/legal/privacy.html)
- [StatusPage](https://www.sap.com/about/cloud-trust-center/cloud-service-status.html)

## Features

| Name | Description |
|------|-------------|
| OData V2 and V4 APIs | RESTful APIs following OData protocol for standardized CRUD operations and query capabilities. |
| Deep Insert | Create complex documents with header and dependent entities in a single API request. |
| Optimistic Concurrency | ETag-based concurrency control to prevent conflicting updates to business documents. |
| Real-Time Integration | Synchronous API access to live ERP data for real-time business process integration. |
| Multi-Module Coverage | APIs spanning finance, sales, procurement, logistics, manufacturing, and HR modules. |

## Use Cases

| Name | Description |
|------|-------------|
| Order-to-Cash | Automate the sales process from sales order creation through delivery and billing. |
| Procure-to-Pay | Streamline procurement from purchase requisition through purchase order, receipt, and invoice. |
| Financial Close | Automate journal entries, cost center reporting, and GL account management for period close. |
| Supply Chain Visibility | Track inbound and outbound deliveries, inventory movements, and material documents in real time. |

## Integrations

| Name | Description |
|------|-------------|
| SAP Business Technology Platform | Native integration with SAP BTP for extensions, analytics, and AI/ML capabilities. |
| SAP Integration Suite | Pre-built integration flows for connecting S/4HANA with third-party applications. |
| Microsoft Office | Integration with Excel and Outlook for business data analysis and communication workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [SAP S/4HANA Sales Order API](openapi/sap-s4hana-sales-order-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Sales Order API](capabilities/shared/sales-order.yaml) -- 10 operations for sales order CRUD, items, partners, pricing, and text management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Order-to-Cash](capabilities/order-to-cash.yaml) | Sales Order | 10 | Sales Operations |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
