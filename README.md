# Department of Veterans Affairs (VA) (department-of-veterans-affairs)

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

The Department of Veterans Affairs (VA) provides health care, benefits, and memorial services to U.S. military Veterans and their families. The VA API Platform at developer.va.gov publishes a structured catalog of APIs spanning Veteran identity confirmation, benefits claims, appeals, document intake, education, loan guaranty, facilities, forms, and HL7 FHIR clinical health data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/department-of-veterans-affairs/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Healthcare
- Veterans

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### VA Facilities API

Search and retrieve VA medical facilities, benefits offices, vet centers, and cemeteries by location, service, or identifier.

- **Human URL:** [https://developer.va.gov/explore/api/va-facilities](https://developer.va.gov/explore/api/va-facilities)
- **Base URL:** `https://api.va.gov/services/va_facilities/v1`

#### Tags

- Facilities
- Health
- Benefits

#### Properties

- [Documentation](https://developer.va.gov/explore/api/va-facilities)
- [OpenAPI](openapi/va-facilities-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/va-facility-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/facility-example.json)
- [Sandbox](https://developer.va.gov/explore/api/va-facilities/sandbox-access)
- [Changelog](https://developer.va.gov/explore/api/va-facilities/release-notes)

### VA Forms API

Programmatic catalog of official VA forms with current PDF URLs and revision metadata.

- **Human URL:** [https://developer.va.gov/explore/api/va-forms](https://developer.va.gov/explore/api/va-forms)
- **Base URL:** `https://api.va.gov/services/va_forms/v0`

#### Tags

- Forms

#### Properties

- [Documentation](https://developer.va.gov/explore/api/va-forms)
- [OpenAPI](openapi/va-forms-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/va-form-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/form-example.json)
- [Sandbox](https://developer.va.gov/explore/api/va-forms/sandbox-access)
- [Changelog](https://developer.va.gov/explore/api/va-forms/release-notes)

### VA Benefits Claims API

Submit and track VA benefits claims (Form 526), intent-to-file notices, and Power of Attorney records.

- **Human URL:** [https://developer.va.gov/explore/api/benefits-claims](https://developer.va.gov/explore/api/benefits-claims)
- **Base URL:** `https://api.va.gov/services/claims/v2`

#### Tags

- Benefits
- Claims

#### Properties

- [Documentation](https://developer.va.gov/explore/api/benefits-claims)
- [OpenAPI](openapi/va-benefits-claims-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/va-claim-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/claim-example.json)
- [Authentication](https://developer.va.gov/explore/api/benefits-claims/authorization-code)
- [Sandbox](https://developer.va.gov/explore/api/benefits-claims/sandbox-access)
- [Changelog](https://developer.va.gov/explore/api/benefits-claims/release-notes)

### VA Benefits Intake API

Submit and track PDF documents for benefits applications via a guided upload workflow.

- **Human URL:** [https://developer.va.gov/explore/api/benefits-intake](https://developer.va.gov/explore/api/benefits-intake)
- **Base URL:** `https://api.va.gov/services/vba_documents/v1`

#### Tags

- Benefits
- Intake
- Documents

#### Properties

- [Documentation](https://developer.va.gov/explore/api/benefits-intake)
- [OpenAPI](openapi/va-benefits-intake-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Sandbox](https://developer.va.gov/explore/api/benefits-intake/sandbox-access)
- [Changelog](https://developer.va.gov/explore/api/benefits-intake/release-notes)

### VA Appeals Status API

Retrieve the status, events, and issues of a Veteran's appeals, supplemental claims, and higher-level reviews.

- **Human URL:** [https://developer.va.gov/explore/api/appeals-status](https://developer.va.gov/explore/api/appeals-status)
- **Base URL:** `https://api.va.gov/services/appeals/v1`

#### Tags

- Appeals
- Status

#### Properties

- [Documentation](https://developer.va.gov/explore/api/appeals-status)
- [OpenAPI](openapi/va-appeals-status-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/va-appeal-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Changelog](https://developer.va.gov/explore/api/appeals-status/release-notes)

### VA Clinical Health API (FHIR)

Read HL7 FHIR R4 clinical resources for a Veteran via SMART-on-FHIR authorization.

- **Human URL:** [https://developer.va.gov/explore/api/clinical-health](https://developer.va.gov/explore/api/clinical-health)
- **Base URL:** `https://api.va.gov/services/fhir/v0/r4`

#### Tags

- Health
- FHIR
- Clinical

#### Properties

- [Documentation](https://developer.va.gov/explore/api/clinical-health)
- [OpenAPI](openapi/va-clinical-health-fhir-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://developer.va.gov/explore/api/clinical-health/release-notes)

### VA Veteran Confirmation API

Confirm a person's Veteran status given basic identifying information.

- **Human URL:** [https://developer.va.gov/explore/api/veteran-confirmation](https://developer.va.gov/explore/api/veteran-confirmation)
- **Base URL:** `https://api.va.gov/services/veteran_confirmation/v1`

#### Tags

- Verification
- Identity

#### Properties

- [Documentation](https://developer.va.gov/explore/api/veteran-confirmation)
- [OpenAPI](openapi/va-veteran-confirmation-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/va-veteran-confirmation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Sandbox](https://developer.va.gov/explore/api/veteran-confirmation/sandbox-access)
- [Changelog](https://developer.va.gov/explore/api/veteran-confirmation/release-notes)

### VA Address Validation API

Verify and standardize U.S. and international addresses for Veterans and their families.

- **Human URL:** [https://developer.va.gov/explore/api/address-validation](https://developer.va.gov/explore/api/address-validation)

#### Tags

- Address
- Validation

#### Properties

- [Documentation](https://developer.va.gov/explore/api/address-validation)
- [Sandbox](https://developer.va.gov/explore/api/address-validation/sandbox-access)
- [Changelog](https://developer.va.gov/explore/api/address-validation/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Benefits Documents API

Retrieve VA-generated benefit documents (decision letters, award letters, certifications) for Veterans.

- **Human URL:** [https://developer.va.gov/explore/api/benefits-documents](https://developer.va.gov/explore/api/benefits-documents)

#### Tags

- Benefits
- Documents

#### Properties

- [Documentation](https://developer.va.gov/explore/api/benefits-documents)
- [Changelog](https://developer.va.gov/explore/api/benefits-documents/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Benefits Reference Data API

Reference data lookups for benefits-claim form fields (countries, states, disabilities, treatment centers, etc.).

- **Human URL:** [https://developer.va.gov/explore/api/benefits-reference-data](https://developer.va.gov/explore/api/benefits-reference-data)

#### Tags

- Reference Data
- Benefits

#### Properties

- [Documentation](https://developer.va.gov/explore/api/benefits-reference-data)
- [Changelog](https://developer.va.gov/explore/api/benefits-reference-data/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Community Care Eligibility API

Determine whether a Veteran is eligible for community-care services under VA referral programs.

- **Human URL:** [https://developer.va.gov/explore/api/community-care-eligibility](https://developer.va.gov/explore/api/community-care-eligibility)

#### Tags

- Health
- Eligibility

#### Properties

- [Documentation](https://developer.va.gov/explore/api/community-care-eligibility)
- [Changelog](https://developer.va.gov/explore/api/community-care-eligibility/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Decision Reviews API

Submit supplemental claims, higher-level reviews, and Notices of Disagreement under appeals modernization.

- **Human URL:** [https://developer.va.gov/explore/api/decision-reviews](https://developer.va.gov/explore/api/decision-reviews)

#### Tags

- Appeals
- Decision Reviews

#### Properties

- [Documentation](https://developer.va.gov/explore/api/decision-reviews)
- [Changelog](https://developer.va.gov/explore/api/decision-reviews/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Direct Deposit Management API

Read and update a Veteran's direct-deposit information for benefit payments.

- **Human URL:** [https://developer.va.gov/explore/api/direct-deposit-management](https://developer.va.gov/explore/api/direct-deposit-management)

#### Tags

- Payments
- Direct Deposit

#### Properties

- [Documentation](https://developer.va.gov/explore/api/direct-deposit-management)
- [Changelog](https://developer.va.gov/explore/api/direct-deposit-management/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Education Benefits API

Submit and track GI Bill and VA education benefit applications and entitlement data.

- **Human URL:** [https://developer.va.gov/explore/api/education-benefits](https://developer.va.gov/explore/api/education-benefits)

#### Tags

- Education
- Benefits

#### Properties

- [Documentation](https://developer.va.gov/explore/api/education-benefits)
- [Changelog](https://developer.va.gov/explore/api/education-benefits/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Loan Guaranty API

Access VA-guaranteed home-loan eligibility, certificates of eligibility (COE), and loan data.

- **Human URL:** [https://developer.va.gov/explore/api/loan-guaranty](https://developer.va.gov/explore/api/loan-guaranty)

#### Tags

- Loans
- Loan Guaranty

#### Properties

- [Documentation](https://developer.va.gov/explore/api/loan-guaranty)
- [Changelog](https://developer.va.gov/explore/api/loan-guaranty/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Loan Review API

Lender-facing API for review, conditions, and modification of VA-guaranteed home loans.

- **Human URL:** [https://developer.va.gov/explore/api/loan-review](https://developer.va.gov/explore/api/loan-review)

#### Tags

- Loans
- Review

#### Properties

- [Documentation](https://developer.va.gov/explore/api/loan-review)
- [Changelog](https://developer.va.gov/explore/api/loan-review/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Guaranty Remittance API

Submit and track guaranty remittance payments for VA-guaranteed loans.

- **Human URL:** [https://developer.va.gov/explore/api/guaranty-remittance](https://developer.va.gov/explore/api/guaranty-remittance)

#### Tags

- Loans
- Payments

#### Properties

- [Documentation](https://developer.va.gov/explore/api/guaranty-remittance)
- [Changelog](https://developer.va.gov/explore/api/guaranty-remittance/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Letter Generator API

Generate official VA letters (e.g. service verification, benefit summary) on demand.

- **Human URL:** [https://developer.va.gov/explore/api/va-letter-generator](https://developer.va.gov/explore/api/va-letter-generator)

#### Tags

- Letters

#### Properties

- [Documentation](https://developer.va.gov/explore/api/va-letter-generator)
- [Changelog](https://developer.va.gov/explore/api/va-letter-generator/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Patient Health API (FHIR)

Veteran-authorized SMART-on-FHIR API exposing the patient's own health record.

- **Human URL:** [https://developer.va.gov/explore/api/patient-health](https://developer.va.gov/explore/api/patient-health)

#### Tags

- Health
- FHIR
- Patient

#### Properties

- [Documentation](https://developer.va.gov/explore/api/patient-health)
- [Changelog](https://developer.va.gov/explore/api/patient-health/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### VA Veteran Service History and Eligibility API

Retrieve a Veteran's service history and eligibility for VA programs.

- **Human URL:** [https://developer.va.gov/explore/api/veteran-service-history-and-eligibility](https://developer.va.gov/explore/api/veteran-service-history-and-eligibility)

#### Tags

- Service History
- Eligibility

#### Properties

- [Documentation](https://developer.va.gov/explore/api/veteran-service-history-and-eligibility)
- [Changelog](https://developer.va.gov/explore/api/veteran-service-history-and-eligibility/release-notes)
- [Postman Collection](collections/va-appeals-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-appeals-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-claims-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-claims-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-benefits-intake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-benefits-intake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-clinical-health-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-clinical-health-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-facilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-facilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-forms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-forms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/va-veteran-confirmation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/va-veteran-confirmation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/department-of-veterans-affairs)
- [LinkedIn](https://www.linkedin.com/company/department-of-veterans-affairs)
- [Portal](https://developer.va.gov/)
- [F A Q](https://developer.va.gov/support/faq)
- [Support](https://developer.va.gov/support/contact-us)
- [Onboarding](https://developer.va.gov/onboarding)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
