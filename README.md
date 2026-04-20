# Apache Software Foundation (apache-software-foundation)
APIs for the Apache Software Foundation (ASF), a nonprofit organization that supports the development of open-source software projects under the Apache License, providing governance, legal protection, and infrastructure for over 350 projects. The ASF exposes public APIs for project discovery, committee governance data, member information, and organizational structure through its Projects API and Whimsy Public Data API.

**URL:** [https://www.apache.org/](https://www.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - ASF, Open Source, Governance, Projects, Apache

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### Apache Software Foundation Projects API
The Apache Software Foundation Projects API provides read-only access to JSON data about ASF projects, committees, releases, and podlings. The data is served as static JSON files from projects.apache.org and includes comprehensive information about the foundation's structure, project metadata, committee membership, release histories, and incubating podlings.

**Human URL:** [https://projects.apache.org/](https://projects.apache.org/)

#### Tags:

 - Committees, Open Source, Projects, Releases, Podlings

#### Properties

- [Documentation](https://projects.apache.org/)
- [OpenAPI](openapi/apache-software-foundation-projects-api-openapi.yml)
- [JSONSchema](json-schema/apache-software-foundation-project-schema.json)
- [JSONSchema](json-schema/apache-software-foundation-committee-schema.json)
- [JSONSchema](json-schema/apache-software-foundation-podling-schema.json)

### Apache Software Foundation Whimsy Public Data API
The Apache Whimsy Public Data API provides access to publicly available information about the Apache Software Foundation's organizational structure. It exposes data about committees, members, committers, and ICLA information.

**Human URL:** [https://whimsy.apache.org/public/](https://whimsy.apache.org/public/)

#### Tags:

 - Governance, Members, Open Source, Committees

#### Properties

- [Documentation](https://whimsy.apache.org/public/)
- [OpenAPI](openapi/apache-software-foundation-whimsy-api-openapi.yml)

## Common Properties

- [Portal](https://www.apache.org/)
- [Blog](https://blogs.apache.org/)
- [Documentation](https://www.apache.org/foundation/)
- [GitHubOrganization](https://github.com/apache)
- [SpectralRules](rules/apache-software-foundation-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-software-foundation-vocabulary.yaml)
- [TermsOfService](https://www.apache.org/licenses/)

## Features

| Name | Description |
|------|-------------|
| Project Directory | Comprehensive directory of all 350+ ASF top-level projects with metadata. |
| Committee Data | Project Management Committee membership, chair, and governance information. |
| Podling Tracking | Apache Incubator podling status, mentors, and graduation tracking. |
| Release History | Release version and date history for all ASF projects. |
| Whimsy Member Data | Public member, committer, and ICLA data from the ASF Whimsy system. |

## Use Cases

| Name | Description |
|------|-------------|
| Apache Project Discovery | Discover and explore all Apache Software Foundation projects programmatically. |
| Governance Transparency | Access committee membership and governance data for ASF organizational research. |
| Release Monitoring | Track release histories and versions across all ASF projects. |
| Incubator Tracking | Monitor Apache Incubator podlings and their progression to top-level projects. |

## Integrations

| Name | Description |
|------|-------------|
| Apache GitHub Organization | All ASF project repositories hosted under the apache GitHub organization. |
| ASF JIRA | Issue tracking at issues.apache.org for all ASF project bug reports and features. |
| Apache Confluence | Wiki documentation at cwiki.apache.org for ASF project and foundation docs. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Software Foundation Projects API](openapi/apache-software-foundation-projects-api-openapi.yml)
- [Apache Software Foundation Whimsy Public Data API](openapi/apache-software-foundation-whimsy-api-openapi.yml)

### JSON Schema

- [Project Schema](json-schema/apache-software-foundation-project-schema.json)
- [Committee Schema](json-schema/apache-software-foundation-committee-schema.json)
- [Podling Schema](json-schema/apache-software-foundation-podling-schema.json)

### JSON Structure

- [Project Structure](json-structure/apache-software-foundation-project-structure.json)
- [Committee Structure](json-structure/apache-software-foundation-committee-structure.json)
- [Podling Structure](json-structure/apache-software-foundation-podling-structure.json)

### JSON-LD

- [ASF Context](json-ld/apache-software-foundation-asf-context.jsonld)

### Examples

- [Project Example](examples/apache-software-foundation-project-example.json)
- [Committee Example](examples/apache-software-foundation-committee-example.json)
- [Podling Example](examples/apache-software-foundation-podling-example.json)

## Vocabulary

- [Apache Software Foundation Vocabulary](vocabulary/apache-software-foundation-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 1 action, and cross-references across operational (OpenAPI) dimensions

## Rules

- [Apache Software Foundation Spectral Rules](rules/apache-software-foundation-spectral-rules.yml) — 15 rules across 7 categories enforcing Apache Software Foundation API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
