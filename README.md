# SAP Concur (concur)
SAP Concur provides a comprehensive suite of REST APIs for travel, expense, and invoice management. The Concur API platform enables integration with expense reporting, travel booking, invoice processing, receipt capture, and user management services.

**URL:** [https://raw.githubusercontent.com/api-evangelist/concur/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/concur/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Expense Management, Finance, Invoice, SAP, Travel

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### SAP Concur Expense API
REST API for managing expense reports, entries, allocations, and attendees.

### SAP Concur Travel API
REST API for managing travel itineraries and bookings.

### SAP Concur Invoice API
REST API for accounts payable invoice processing.

### SAP Concur Receipts API
REST API for submitting and managing digital receipts.

### SAP Concur Request API
REST API for managing pre-trip travel requests.

### SAP Concur User Provisioning API
SCIM 2.0-compliant user provisioning API.

### SAP Concur Events API
Event subscription API for real-time notifications.

### SAP Concur Lists API
REST API for managing custom lists and list items.

## Features

| Name | Description |
|------|-------------|
| Expense Report Management | Create, submit, and manage expense reports with approval workflows. |
| Receipt Digitization | Capture and process digital receipts from merchants. |
| Travel Booking Integration | Search and book travel through API-connected booking tools. |
| Invoice Processing | Automate accounts payable workflows. |
| Event Notifications | Real-time event subscriptions for status changes. |
| SCIM User Provisioning | Standards-based user provisioning. |

## Use Cases

| Name | Description |
|------|-------------|
| ERP Integration | Integrate Concur expense data with ERP systems. |
| Travel Management | Build travel booking integrations. |
| Receipt Automation | Automatically capture and match digital receipts. |
| Spend Analytics | Extract data for spend analytics and compliance reporting. |
| Employee Onboarding | Automate Concur user provisioning. |

## Integrations

| Name | Description |
|------|-------------|
| SAP S/4HANA | Financial posting integration for SAP ERP. |
| SAP SuccessFactors | HR integration for employee data synchronization. |
| Uber for Business | Automated ride receipt submission. |
| Lyft | Ground transportation receipt integration. |
| Microsoft Teams | Approval and notification integration. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [concur-expense-api.yaml](openapi/concur-expense-api.yaml)

### JSON Schema

- [concur-expense-api-expense-report-schema.json](json-schema/concur-expense-api-expense-report-schema.json)
- [concur-expense-api-expense-schema.json](json-schema/concur-expense-api-expense-schema.json)

### JSON Structure

- [concur-expense-api-expense-report-structure.json](json-structure/concur-expense-api-expense-report-structure.json)
- [concur-expense-api-expense-structure.json](json-structure/concur-expense-api-expense-structure.json)

### JSON-LD

- [concur-context.jsonld](json-ld/concur-context.jsonld)

### Examples

- [concur-expense-api-expense-report-example.json](examples/concur-expense-api-expense-report-example.json)
- [concur-expense-api-expense-example.json](examples/concur-expense-api-expense-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [expense.yaml](capabilities/shared/expense.yaml)

### Workflow Capabilities

- [spend-management.yaml](capabilities/spend-management.yaml)

## Vocabulary

- [concur-vocabulary.yaml](vocabulary/concur-vocabulary.yaml)

## Rules

- [concur-spectral-rules.yml](rules/concur-spectral-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
