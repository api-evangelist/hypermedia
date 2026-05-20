# Hypermedia (hypermedia)
An index and topic collection covering hypermedia-driven APIs, HATEOAS, and the formats, link relations, and specifications that make APIs discoverable and self-describing. Hypermedia APIs use links, link relations, and embedded controls inside their responses so that clients can navigate an API graph at runtime rather than relying on hard-coded URI structures. This collection covers hypermedia formats including HAL, JSON:API, Siren, Collection+JSON, JSON-LD, Hydra, ALPS, UBER, Mason, and Verbose; the standards bodies that define web linking (IETF, W3C) including RFC 5988/8288 Web Linking and RFC 9264 api-catalog; provider APIs that demonstrably ship HATEOAS responses; and the spec libraries and frameworks that implement hypermedia patterns.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Hypermedia, HATEOAS, HAL, JSON:API, Link Headers, Link Relations, Siren, Collection+JSON, Linked Data, JSON-LD, Hydra, ALPS

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - HAL Resource Schema](https://raw.githubusercontent.com/api-evangelist/hypermedia/refs/heads/main/json-schema/hypermedia-hal-resource-schema.json)
- [JSONSchema - Link Relation Schema](https://raw.githubusercontent.com/api-evangelist/hypermedia/refs/heads/main/json-schema/hypermedia-link-relation-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/hypermedia/refs/heads/main/json-ld/hypermedia-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/hypermedia/refs/heads/main/vocabulary/hypermedia-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| HATEOAS Navigation | Hypermedia APIs include in-response links and link relations so clients can discover available state transitions at runtime rather than hard-coding URI templates against documentation. |
| Standardized Hypermedia Formats | Established formats such as HAL, JSON:API, Siren, Collection+JSON, Hydra, ALPS, UBER, Mason, and Verbose provide structured ways to embed links, actions, and metadata inside API responses. |
| Web Linking via Link Headers | RFC 5988 and RFC 8288 define the HTTP Link header and the Web Linking model, including the IANA Link Relations registry that gives shared meaning to rel values across APIs. |
| Linked Data and Semantic Hypermedia | JSON-LD, Hydra, schema.org, and the broader RDF stack extend hypermedia with shared vocabularies, enabling semantic interoperability between APIs, search engines, and knowledge graphs. |
| Self-Describing API Catalogs | RFC 9264 api-catalog, APIs.json, and similar discovery documents act as hypermedia entry points that link a host to its APIs, OpenAPI specs, terms of service, and policies. |
| Hypermedia Frameworks and Libraries | Frameworks like Spring HATEOAS, Spring Data REST, and Apicurio provide implementation support for emitting HAL, HAL-FORMS, JSON:API, and Collection+JSON responses from server code. |

## Use Cases

| Name | Description |
|------|-------------|
| Evolvable Long-Lived APIs | HATEOAS-based APIs allow servers to evolve URI structures and add new affordances while clients continue to navigate by link relations rather than hard-coded paths. |
| Domain-Driven Project Management APIs | OpenProject exposes work packages, projects, users, and attachments through a HAL+JSON hypermedia API where every resource embeds links to related resources and available actions. |
| Standardized CRUD via JSON:API | Patreon, MBTA, Teamtailor, and Drupal expose their resources via JSON:API, providing a consistent specification for fetching, including related resources, filtering, sorting, and pagination. |
| Semantic Search and Structured Data | Schema.org and JSON-LD allow APIs and websites to publish machine-readable Linked Data that search engines, agents, and aggregators can consume without bespoke parsers. |
| API Discovery and Catalogs | APIs.json and RFC 9264 api-catalog documents act as hypermedia entry points that let crawlers, tooling, and AI agents discover an organization's APIs, specifications, and policies. |
| Hypermedia-Driven Web Apps | Approaches like htmx, hyperview, and Hypermedia Systems return HTML fragments and hypermedia controls directly to the client, treating HTML itself as the hypermedia format. |

## Integrations

| Name | Description |
|------|-------------|
| HAL (Hypertext Application Language) | A minimal hypermedia format for JSON and XML that embeds _links and _embedded resources, widely used by APIs such as OpenProject, Reverb, and Spring Data REST. |
| JSON:API | A specification for building APIs in JSON that standardizes resource objects, relationships, includes, filtering, sorting, and pagination, used by Patreon, MBTA, Teamtailor, and Drupal. |
| Siren | A hypermedia specification for representing entities, their classes, properties, actions, and links, designed for rich, action-oriented hypermedia clients. |
| Collection+JSON | A JSON-based hypermedia format from Mike Amundsen for representing collections of items with queries and templates for write operations. |
| JSON-LD and Hydra | JSON-LD provides a JSON syntax for Linked Data; Hydra extends it with a vocabulary for describing hypermedia-driven Web APIs including operations, classes, and supported properties. |
| ALPS (Application-Level Profile Semantics) | A profile description format for documenting semantic descriptors and state transitions independent of any single media type. |
| Web Linking (RFC 5988 / RFC 8288) | IETF specifications defining the HTTP Link header and a model for typed web links, along with the IANA Link Relations registry shared across hypermedia formats. |
| Spring HATEOAS | A library for building hypermedia-driven REST APIs in Spring, supporting HAL, HAL-FORMS, Collection+JSON, and UBER, with first-class integration into Spring Data REST. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [HAL Resource Schema](json-schema/hypermedia-hal-resource-schema.json)
- [Link Relation Schema](json-schema/hypermedia-link-relation-schema.json)

### JSON Structure

- [HAL Resource Structure](json-structure/hypermedia-hal-resource-structure.json)
- [Link Relation Structure](json-structure/hypermedia-link-relation-structure.json)

### JSON-LD

- [Hypermedia Context](json-ld/hypermedia-context.jsonld)

## Vocabulary

- [Hypermedia Vocabulary](vocabulary/hypermedia-vocabulary.yaml) — Unified taxonomy mapping hypermedia formats, link relations, resources, actions, workflows, and personas across HATEOAS APIs and hypermedia frameworks

## Network

This index references the following hypermedia, HATEOAS, and link-relation repositories:

- [Apicurio](https://github.com/api-evangelist/apicurio)
- [APIs.json](https://github.com/api-evangelist/apis-json)
- [Design Patterns](https://github.com/api-evangelist/design-patterns)
- [Drupal](https://github.com/api-evangelist/drupal)
- [MBTA](https://github.com/api-evangelist/mbta)
- [OpenProject](https://github.com/api-evangelist/openproject)
- [Patreon](https://github.com/api-evangelist/patreon)
- [RDF](https://github.com/api-evangelist/rdf)
- [REST](https://github.com/api-evangelist/rest)
- [RESTful](https://github.com/api-evangelist/restful)
- [RESTful APIs](https://github.com/api-evangelist/restful-apis)
- [RESTful Services](https://github.com/api-evangelist/restful-services)
- [Reverb](https://github.com/api-evangelist/reverb)
- [Schema.org](https://github.com/api-evangelist/schema-org)
- [SPARQL](https://github.com/api-evangelist/sparql)
- [Spring Boot](https://github.com/api-evangelist/spring-boot)
- [Spring Boot 3](https://github.com/api-evangelist/spring-boot-3)
- [Spring Data](https://github.com/api-evangelist/spring-data)
- [Spring Framework](https://github.com/api-evangelist/spring)
- [Teamtailor](https://github.com/api-evangelist/teamtailor)
- [Technology Standards](https://github.com/api-evangelist/technology-standards)
- [W3C](https://github.com/api-evangelist/w3c)
- [Web Standards](https://github.com/api-evangelist/web-standards)
- [Wikidata](https://github.com/api-evangelist/wikidata)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
