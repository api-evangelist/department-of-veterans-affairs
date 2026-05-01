# Department of Veterans Affairs (VA)

The Department of Veterans Affairs (VA) provides health care, benefits, and memorial services to U.S. military Veterans and their families. The VA API Platform at [developer.va.gov](https://developer.va.gov/) publishes a structured catalog of APIs spanning Veteran identity confirmation, benefits claims, appeals, document intake, education, loan guaranty, facilities, forms, and HL7 FHIR clinical health data.

This repository inventories that catalog as an APIs.yml index plus generated artifacts for the APIs that have a meaningful, public surface area.

**APIs.yml:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Healthcare
- Veterans

## Repository Layout

- [`apis.yml`](apis.yml) — APIs.json/yml index
- [`openapi/`](openapi/) — OpenAPI 3.1 specifications for VA APIs
- [`json-schema/`](json-schema/) — Standalone JSON Schemas for the core domain objects
- [`json-ld/`](json-ld/) — JSON-LD context aligning VA terms to schema.org and FHIR
- [`vocabulary/`](vocabulary/) — Controlled VA-domain vocabulary
- [`capabilities/`](capabilities/) — High-level capability catalog
- [`rules/`](rules/) — Cross-cutting access, security, and PII rules
- [`examples/`](examples/) — Representative response payloads

## APIs in this Index

### Health & Clinical
- VA Facilities API
- VA Clinical Health API (FHIR)
- VA Patient Health API (FHIR)
- VA Community Care Eligibility API

### Benefits & Claims
- VA Benefits Claims API
- VA Benefits Intake API
- VA Benefits Documents API
- VA Benefits Reference Data API
- VA Decision Reviews API
- VA Appeals Status API
- VA Direct Deposit Management API
- VA Education Benefits API
- VA Letter Generator API

### Loan Guaranty
- VA Loan Guaranty API
- VA Loan Review API
- VA Guaranty Remittance API

### Forms & Verification
- VA Forms API
- VA Veteran Confirmation API
- VA Veteran Service History and Eligibility API
- VA Address Validation API

## Authentication

VA APIs use one of three authentication models:

- **API key** (`apikey` header) for read-only catalog APIs (Forms, Facilities, Veteran Confirmation, Benefits Intake)
- **OAuth 2.0 Authorization Code** for Veteran-authorized actions (Claims, Decision Reviews, Direct Deposit)
- **SMART-on-FHIR (OAuth 2.0)** for clinical health data

Sandbox: `https://sandbox-api.va.gov/...` — synthetic test data only.
Production: `https://api.va.gov/...`

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
