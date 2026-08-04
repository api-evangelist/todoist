# Todoist (todoist)

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

Todoist is a productivity platform providing task management APIs for developers. The Todoist API v1 unifies the Sync and REST APIs into a single interface, offering programmatic access to tasks, projects, sections, labels, reminders, comments, workspaces, and webhooks. SDKs are available in Python and TypeScript.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Productivity
- Tasks
- To-Do
- Task Management
- Collaboration

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-30

## APIs

### Todoist API

The Todoist API v1 provides programmatic access to Todoist task management, projects, sections, labels, reminders, comments, workspaces, and more. Supports OAuth 2.0 and personal API tokens for authentication. Includes incremental sync via the /sync endpoint for efficient client-server data synchronization.

- **Human URL:** [https://developer.todoist.com/api/v1/](https://developer.todoist.com/api/v1/)
- **Base URL:** `https://api.todoist.com/api/v1`

#### Tags

- Productivity
- Tasks
- Projects
- Task Management

#### Properties

- [Documentation](https://developer.todoist.com/api/v1/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/openapi/todoist-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/openapi/todoist-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/json-schema/todoist-task-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/rules/todoist-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/vocabulary/todoist-vocabulary.yml)
- [Postman Collection](collections/todoist.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/todoist.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Todoist REST API v2

The Todoist REST API v2 is the legacy recommended API for external integrations, providing access to tasks, projects, sections, labels, comments, and filters. Uses Bearer token authentication with OAuth 2.0 support.

- **Human URL:** [https://developer.todoist.com/rest/v2/](https://developer.todoist.com/rest/v2/)
- **Base URL:** `https://api.todoist.com/rest/v2`

#### Tags

- Productivity
- Tasks
- REST

#### Properties

- [Documentation](https://developer.todoist.com/rest/v2/)
- [Postman Collection](collections/todoist.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/todoist.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Todoist Sync API v9

The Todoist Sync API is designed for clients maintaining a local representation of user data, allowing incremental synchronization of projects, tasks, labels, filters, and reminders. Supports batch commands for efficient updates.

- **Human URL:** [https://developer.todoist.com/sync/v9/](https://developer.todoist.com/sync/v9/)
- **Base URL:** `https://api.todoist.com/sync/v9`

#### Tags

- Sync
- Productivity
- Tasks

#### Properties

- [Documentation](https://developer.todoist.com/sync/v9/)
- [Reference](https://developer.todoist.com/sync/v9/)
- [Postman Collection](collections/todoist.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/todoist.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/doist)
- [Website](https://todoist.com/)
- [Developer  Portal](https://developer.todoist.com/)
- [Documentation](https://developer.todoist.com/api/v1/)
- [Sign Up](https://todoist.com/users/showregister)
- [Login](https://todoist.com/auth/login)
- [Authentication](https://developer.todoist.com/guides/#oauth)
- [Webhooks](https://developer.todoist.com/api/v1/#webhooks)
- [S D Ks](https://developer.todoist.com/guides/#sdks)
- [Python  S D K](https://github.com/Doist/todoist-api-python)
- [Type Script  S D K](https://github.com/Doist/todoist-sdk-typescript)
- [M C P  Server](https://github.com/doist/todoist-ai)
- [GitHub Organization](https://github.com/Doist)
- [Blog](https://doist.com/blog/)
- [Pricing](https://todoist.com/pricing)
- [Terms of Service](https://doist.com/terms-of-service)
- [Privacy Policy](https://doist.com/privacy-policy)
- [Integrations](https://www.todoist.com/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
