# Formbricks (formbricks)

Formbricks is an open-source experience management and survey platform (a privacy-first Typeform / Qualtrics alternative). Its REST API lets you create and manage surveys, collect and query responses, manage contacts and their attributes, and wire up webhooks, with a Public Client API (no auth) for survey delivery and a Management API authenticated with an x-api-key header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/formbricks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/formbricks/refs/heads/main/apis.yml)

## Tags

- Surveys
- Experience Management
- Feedback
- Forms
- Open Source

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Formbricks Surveys API

List, create, retrieve, update, and delete surveys, plus generate single-use survey links, through the Management API under /api/v2/management/surveys.

- **Human URL:** [https://formbricks.com/docs/api-v2-reference](https://formbricks.com/docs/api-v2-reference)
- **Base URL:** `https://app.formbricks.com/api`

#### Tags

- Surveys
- Forms
- Management

#### Properties

- [Documentation](https://formbricks.com/docs/api-reference/rest-api)
- [API Reference](https://formbricks.com/docs/api-v2-reference)
- [OpenAPI](openapi/formbricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/formbricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formbricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/formbricks/formbricks)

### Formbricks Responses API

Create, list, filter by survey, update, and delete survey responses. Responses carry per-question data, time-to-complete (ttc), finished state, and meta (source, url, userAgent, country).

- **Human URL:** [https://formbricks.com/docs/api-v2-reference/management-api--responses/get-responses](https://formbricks.com/docs/api-v2-reference/management-api--responses/get-responses)
- **Base URL:** `https://app.formbricks.com/api`

#### Tags

- Responses
- Feedback
- Data

#### Properties

- [Documentation](https://formbricks.com/docs/api-v2-reference/management-api--responses/create-a-response)
- [API Reference](https://formbricks.com/docs/api-v2-reference)
- [OpenAPI](openapi/formbricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/formbricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formbricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/formbricks/formbricks)

### Formbricks Contacts and Attributes API

List and retrieve contacts, bulk-upsert contacts with their attributes, and manage contact attribute keys that define the segmentation schema for an environment.

- **Human URL:** [https://formbricks.com/docs/api-v2-reference](https://formbricks.com/docs/api-v2-reference)
- **Base URL:** `https://app.formbricks.com/api`

#### Tags

- Contacts
- Attributes
- Segmentation

#### Properties

- [Documentation](https://formbricks.com/docs/api-reference/rest-api)
- [API Reference](https://formbricks.com/docs/api-v2-reference)
- [OpenAPI](openapi/formbricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/formbricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formbricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/formbricks/formbricks)

### Formbricks Webhooks API

List, create, and delete webhooks that fire real-time HTTP notifications on responseCreated, responseUpdated, and responseFinished triggers, optionally scoped to specific surveyIds.

- **Human URL:** [https://formbricks.com/docs/developer-docs/webhooks](https://formbricks.com/docs/developer-docs/webhooks)
- **Base URL:** `https://app.formbricks.com/api`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://formbricks.com/docs/developer-docs/webhooks)
- [API Reference](https://formbricks.com/docs/api-v2-reference/management-api--webhooks/get-webhooks)
- [OpenAPI](openapi/formbricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/formbricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formbricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/formbricks/formbricks)

### Formbricks Management API

Account and configuration surface - the Me endpoint that returns the environment an API key belongs to, and Action Class management for defining the code and no-code actions that trigger in-product surveys.

- **Human URL:** [https://formbricks.com/docs/api-v2-reference](https://formbricks.com/docs/api-v2-reference)
- **Base URL:** `https://app.formbricks.com/api`

#### Tags

- Management
- Account
- Action Classes

#### Properties

- [Documentation](https://formbricks.com/docs/api-reference/rest-api)
- [API Reference](https://formbricks.com/docs/api-v2-reference)
- [OpenAPI](openapi/formbricks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/formbricks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formbricks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub](https://github.com/formbricks/formbricks)

## Common Properties

- [GitHub Organization](https://github.com/formbricks)
- [LinkedIn](https://www.linkedin.com/company/formbricks)
- [Website](https://www.formbricks.com)
- [Documentation](https://formbricks.com/docs)
- [Plans](plans/formbricks-plans-pricing.yml)
- [Rate Limits](rate-limits/formbricks-rate-limits.yml)
- [Fin Ops](finops/formbricks-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
