# Todoist

Todoist is a productivity platform providing task management APIs for developers. The Todoist API v1 unifies the Sync and REST APIs into a single interface, offering programmatic access to tasks, projects, sections, labels, reminders, comments, workspaces, and webhooks. SDKs are available in Python and TypeScript.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/todoist/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

 - Productivity, Tasks, To-Do, Task Management, Collaboration

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-03

## APIs

### Todoist API

The Todoist API v1 provides programmatic access to tasks, projects, sections, labels, reminders, comments, workspaces, and sync. Supports OAuth 2.0 and personal API tokens.

**Human URL:** [https://developer.todoist.com/api/v1/](https://developer.todoist.com/api/v1/)

#### Tags

 - Productivity, Tasks, Projects, Task Management

#### Properties

- [Documentation](https://developer.todoist.com/api/v1/)
- [OpenAPI](openapi/todoist-openapi.yml)
- [JSON Schema](json-schema/todoist-task-schema.json)
- [Naftiko Capabilities](capabilities/task-management.yaml)
- [Spectral Rules](rules/todoist-rules.yml)
- [Vocabulary](vocabulary/todoist-vocabulary.yml)

### Todoist REST API v2

Legacy REST API for tasks, projects, sections, labels, comments, and filters.

**Human URL:** [https://developer.todoist.com/rest/v2/](https://developer.todoist.com/rest/v2/)

### Todoist Sync API v9

Incremental sync API for local clients maintaining full Todoist data replicas.

**Human URL:** [https://developer.todoist.com/sync/v9/](https://developer.todoist.com/sync/v9/)

## Artifacts

### OpenAPI Specifications

- [openapi/todoist-openapi.yml](openapi/todoist-openapi.yml) — Tasks, projects, sections, labels, comments, reminders, workspaces, sync

### Spectral Rules

- [rules/todoist-rules.yml](rules/todoist-rules.yml) — Governance ruleset enforcing Todoist API conventions

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [task-management.yaml](capabilities/task-management.yaml) | Full task, project, label, and workspace lifecycle (9 MCP tools) |

**Shared:** [capabilities/shared/todoist-api.yaml](capabilities/shared/todoist-api.yaml)

### JSON Schema

- [json-schema/todoist-task-schema.json](json-schema/todoist-task-schema.json) — Task entity
- [json-schema/todoist-project-schema.json](json-schema/todoist-project-schema.json) — Project entity

### JSON Structure

- [json-structure/todoist-task-structure.json](json-structure/todoist-task-structure.json)

### JSON-LD

- [json-ld/todoist-context.jsonld](json-ld/todoist-context.jsonld)

### Examples

- [examples/todoist-list-tasks-example.json](examples/todoist-list-tasks-example.json)
- [examples/todoist-create-task-example.json](examples/todoist-create-task-example.json)
- [examples/todoist-create-project-example.json](examples/todoist-create-project-example.json)

### Vocabulary

- [vocabulary/todoist-vocabulary.yml](vocabulary/todoist-vocabulary.yml)

## Common Properties

- [Website](https://todoist.com/)
- [Developer Portal](https://developer.todoist.com/)
- [Documentation](https://developer.todoist.com/api/v1/)
- [Sign Up](https://todoist.com/users/showregister)
- [Login](https://todoist.com/auth/login)
- [Authentication](https://developer.todoist.com/guides/#oauth)
- [Webhooks](https://developer.todoist.com/api/v1/#webhooks)
- [Python SDK](https://github.com/Doist/todoist-api-python)
- [TypeScript SDK](https://github.com/Doist/todoist-sdk-typescript)
- [MCP Server](https://github.com/doist/todoist-ai)
- [GitHub Organization](https://github.com/Doist)
- [CLI](https://github.com/Doist/todoist-cli)
- [Pricing](https://todoist.com/pricing)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
