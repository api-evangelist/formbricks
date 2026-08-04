# Formbricks (formbricks)

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
