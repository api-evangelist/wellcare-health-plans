# WellCare Health Plans

WellCare Health Plans was a managed care company focused exclusively on government-sponsored managed care services through Medicaid, Medicare Advantage, and Medicare Prescription Drug Plans before being acquired by Centene Corporation. Now operating under Centene, WellCare provides FHIR-compliant APIs for interoperability and patient access as required by CMS Interoperability and Patient Access final rules (CMS-9115-F).

**Website:** https://www.wellcare.com
**Developer Portal:** https://partners.centene.com/apis
**Interoperability Portal:** https://www.wellcare.com/en/interoperability-and-patient-access

## APIs

### WellCare FHIR Patient Access API

FHIR R4 patient access API enabling members and authorized third-party apps to access health data including claims, clinical information, medications, and immunizations. Supports SMART on FHIR authorization and up to 5 years of historical data.

- **Base URL:** https://partners.centene.com
- **OpenAPI:** [wellcare-fhir-patient-access-api-openapi.yml](openapi/wellcare-fhir-patient-access-api-openapi.yml)

**Endpoints:** Get Patient, List Coverage, List Explanation of Benefit, List Conditions, List Observations, List Medication Requests, List Immunizations, List Encounters

### WellCare FHIR Provider Directory API

FHIR R4 provider directory API providing access to in-network practitioners, organizations, locations, and insurance plan information following the Da Vinci PDex Plan-Net implementation guide.

- **Base URL:** https://partners.centene.com
- **OpenAPI:** [wellcare-fhir-provider-directory-api-openapi.yml](openapi/wellcare-fhir-provider-directory-api-openapi.yml)

**Endpoints:** Search/Get Practitioner, Search/Get Organization, Search Locations, Search Practitioner Roles, Search Insurance Plans

## Artifacts

### OpenAPI Specifications
- [FHIR Patient Access API](openapi/wellcare-fhir-patient-access-api-openapi.yml)
- [FHIR Provider Directory API](openapi/wellcare-fhir-provider-directory-api-openapi.yml)

### JSON Schema
- [FHIR Patient Schema](json-schema/wellcare-fhir-patient-schema.json)
- [FHIR Explanation of Benefit Schema](json-schema/wellcare-fhir-eob-schema.json)

### JSON Structure
- [FHIR Patient Structure](json-structure/wellcare-fhir-patient-structure.json)

### Examples
- [Get Patient Example](examples/wellcare-fhir-patient-access-api-getPatient-example.json)
- [List Explanation of Benefit Example](examples/wellcare-fhir-patient-access-api-listExplanationOfBenefit-example.json)
- [Search Practitioners Example](examples/wellcare-fhir-provider-directory-api-searchPractitioners-example.json)

### Spectral Rules
- [WellCare Health Plans Rules](rules/wellcare-health-plans-rules.yml)

### Capabilities (Naftiko)
- [Member Care Coordination](capabilities/member-care-coordination.yaml) — Unified workflow combining Patient Access + Provider Directory APIs (11 tools)
- **Shared:** [FHIR Patient Access](capabilities/shared/fhir-patient-access.yaml)
- **Shared:** [FHIR Provider Directory](capabilities/shared/fhir-provider-directory.yaml)

### JSON-LD
- [WellCare Health Plans Context](json-ld/wellcare-health-plans-context.jsonld)

### Vocabulary
- [WellCare Health Plans Vocabulary](vocabulary/wellcare-health-plans-vocabulary.yml)

## Tags

Healthcare, FHIR, Interoperability, Patient Access, Provider Directory, Managed Care, Medicaid, Medicare

## Maintainers
**FN:** API Evangelist
**Email:** info@apievangelist.com
