# Todoist GraphQL

## Description

Todoist does not expose a native public GraphQL API. The platform is served
through two REST-style interfaces — the REST API v2
(https://developer.todoist.com/rest/v2/) and the unified API v1 / Sync API v9
(https://developer.todoist.com/api/v1/) — both accessed over HTTPS with Bearer
token or OAuth 2.0 authentication.

## Schema Type

**Conceptual / Derived** — The GraphQL schema in `todoist-schema.graphql` is a
comprehensive data-model translation derived from the Todoist REST and Sync API
documentation. It is not served at a live GraphQL endpoint but is provided for
tooling, catalog enrichment, code generation, and schema-comparison purposes.

## Native GraphQL Endpoint

None. No public GraphQL endpoint exists as of June 2026.

## Official API Documentation

- Unified API v1: https://developer.todoist.com/api/v1/
- REST API v2 (legacy): https://developer.todoist.com/rest/v2/
- Sync API v9: https://developer.todoist.com/sync/v9/
- GitHub Organization: https://github.com/Doist

## Core Resource Types Covered

Task, Project, Section, Label, Comment, Collaborator, Filter, Note, Reminder,
Attachment, User, Subscription, Karma, Stats, Activity, Event, Archive, DueDate,
Duration, ItemOrder, ProjectOrder, Priority, Color, ViewStyle, TeamMember,
Workspace
