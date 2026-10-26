# Apache Software Foundation (apache-software-foundation)

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

APIs for the Apache Software Foundation (ASF), a nonprofit organization that supports the development of open-source software projects under the Apache License, providing governance, legal protection, and infrastructure for over 350 projects. The ASF exposes public APIs for project discovery, committee governance data, member information, and organizational structure through its Projects API and Whimsy Public Data API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-software-foundation/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-software-foundation/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- ASF
- Open Source
- Governance
- Projects
- Apache

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Apache Software Foundation Projects API

The Apache Software Foundation Projects API provides read-only access to JSON data about ASF projects, committees, releases, and podlings. The data is served as static JSON files from projects.apache.org and includes comprehensive information about the foundation's structure, project metadata, committee membership, release histories, and incubating podlings.

- **Human URL:** [https://projects.apache.org/](https://projects.apache.org/)

#### Tags

- Committees
- Open Source
- Projects
- Releases
- Podlings

#### Properties

- [Documentation](https://projects.apache.org/)
- [OpenAPI](openapi/apache-software-foundation-projects-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-software-foundation-projects-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-software-foundation-projects-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/apache-software-foundation-project-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/apache-software-foundation-committee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/apache-software-foundation-podling-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Apache Software Foundation Whimsy Public Data API

The Apache Whimsy Public Data API provides access to publicly available information about the Apache Software Foundation's organizational structure. It exposes data about committees, members, committers, and ICLA (Individual Contributor License Agreement) information. The data is maintained by the ASF Secretary and Whimsy tooling.

- **Human URL:** [https://whimsy.apache.org/public/](https://whimsy.apache.org/public/)

#### Tags

- Governance
- Members
- Open Source
- Committees

#### Properties

- [Documentation](https://whimsy.apache.org/public/)
- [OpenAPI](openapi/apache-software-foundation-whimsy-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-software-foundation-whimsy-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-software-foundation-whimsy-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/the-apache-software-foundation)
- [Portal](https://www.apache.org/)
- [Blog](https://blogs.apache.org/)
- [Documentation](https://www.apache.org/foundation/)
- [GitHub Organization](https://github.com/apache)
- [Spectral Rules](rules/apache-software-foundation-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-software-foundation-vocabulary.yaml)
- [Terms of Service](https://www.apache.org/licenses/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
