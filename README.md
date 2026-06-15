# wellcare-health-plans (wellcare-health-plans)

WellCare Health Plans was a managed care company that focused exclusively on government-sponsored managed care services through Medicaid, Medicare Advantage, and Medicare Prescription Drug Plans before being acquired by Centene Corporation. Now operating under Centene, WellCare provides FHIR- compliant APIs for interoperability and patient access as required by CMS Interoperability and Patient Access final rules (CMS-9115-F). The Centene Developer Partner Portal at partners.centene.com/apis provides access to WellCare FHIR APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/wellcare-health-plans/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wellcare-health-plans/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### WellCare FHIR Patient Access API

The WellCare FHIR Patient Access API enables members and authorized third-party applications to securely access and exchange health data including medical, pharmacy, dental, and vision claims and clinical information. The API supports HL7 FHIR R4 standards and SMART on FHIR authorization, providing access to up to 5 years of historical health information. Required under CMS Interoperability and Patient Access final rule (CMS-9115-F) for Medicaid and Medicare Advantage plans.

- **Human URL:** [https://www.wellcare.com/en/interoperability-and-patient-access](https://www.wellcare.com/en/interoperability-and-patient-access)
- **Base URL:** `https://partners.centene.com`

#### Tags

- Healthcare
- FHIR
- Interoperability
- Patient Access
- Managed Care
- Medicaid
- Medicare

#### Properties

- [Documentation](https://www.wellcare.com/en/interoperability-and-patient-access)
- [Portal](https://partners.centene.com/apis)
- [OpenAPI](openapi/wellcare-fhir-patient-access-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellcare-fhir-patient-access-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellcare-fhir-patient-access-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/wellcare-fhir-patient-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wellcare-fhir-eob-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/wellcare-fhir-patient-structure.json)
- [Example](examples/wellcare-fhir-patient-access-api-getPatient-example.json)
- [Example](examples/wellcare-fhir-patient-access-api-listExplanationOfBenefit-example.json)
- [Spectral Ruleset](rules/wellcare-health-plans-rules.yml)

### WellCare FHIR Provider Directory API

The WellCare FHIR Provider Directory API provides access to up-to-date provider directory information, enabling third-party applications to query in-network physicians, specialists, hospitals, and other healthcare providers. The API follows HL7 FHIR R4 standards and Da Vinci Provider Directory implementation guide (PDex Plan-Net), supporting CMS interoperability requirements for Medicaid and Medicare Advantage plans.

- **Human URL:** [https://www.wellcare.com/en/interoperability-and-patient-access](https://www.wellcare.com/en/interoperability-and-patient-access)
- **Base URL:** `https://partners.centene.com`

#### Tags

- Healthcare
- FHIR
- Interoperability
- Provider Directory
- Managed Care
- Medicaid
- Medicare

#### Properties

- [Documentation](https://www.wellcare.com/en/interoperability-and-patient-access)
- [Portal](https://partners.centene.com/apis)
- [OpenAPI](openapi/wellcare-fhir-provider-directory-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wellcare-fhir-provider-directory-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wellcare-fhir-provider-directory-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/wellcare-fhir-provider-directory-api-searchPractitioners-example.json)
- [Spectral Ruleset](rules/wellcare-health-plans-rules.yml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/wellcare)
- [Website](https://www.wellcare.com)
- [Developer Portal](https://partners.centene.com/apis)
- [Interoperability Portal](https://www.wellcare.com/en/interoperability-and-patient-access)
- [Git Hub Org](https://github.com/wellcare-health-plans)
- [J S O N L D Context](json-ld/wellcare-health-plans-context.jsonld)
- [Vocabulary](vocabulary/wellcare-health-plans-vocabulary.yml)
