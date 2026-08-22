# Apache Jena (apache-jena)

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

Apache Jena is a Java framework for building Semantic Web and Linked Data applications. It provides APIs for RDF, SPARQL, OWL, and a triplestore database (TDB2) along with the Fuseki SPARQL server with a REST API for querying and managing RDF datasets.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-jena/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Java, Linked Data, OWL, Ontology, Open Source, RDF, Semantic Web, SPARQL

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Jena Fuseki SPARQL API
Jena Fuseki provides a SPARQL server with REST API endpoints for SPARQL 1.1 Query, SPARQL 1.1 Update, and the SPARQL Graph Store HTTP Protocol.

**Human URL:** [https://jena.apache.org/documentation/fuseki2/](https://jena.apache.org/documentation/fuseki2/)

#### Tags:

 - Fuseki, RDF, REST, SPARQL

#### Properties

- [Documentation](https://jena.apache.org/documentation/fuseki2/)
- [OpenAPI](openapi/apache-jena-fuseki-sparql-api.yaml)

### Apache Jena Java API
The Jena Java API provides programmatic access to RDF model creation, SPARQL query execution, OWL reasoning, and TDB2 triplestore management.

**Human URL:** [https://jena.apache.org/documentation/](https://jena.apache.org/documentation/)

#### Tags:

 - Java, OWL, RDF, SDK

#### Properties

- [Documentation](https://jena.apache.org/documentation/)
- [GettingStarted](https://jena.apache.org/tutorials/)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/jena)
- [Documentation](https://jena.apache.org/documentation/)
- [GettingStarted](https://jena.apache.org/tutorials/)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)
- [Versioning](https://jena.apache.org/about_jena/releases.html)
- [SpectralRules](rules/apache-jena-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-jena-vocabulary.yaml)
- [NaftikoCapability](capabilities/sparql-data-management.yaml)

## Features

| Name | Description |
|------|-------------|
| SPARQL Query and Update | Full SPARQL 1.1 query and update protocol support via Fuseki REST API. |
| RDF Model API | Java API for creating, reading, and manipulating RDF graphs. |
| OWL Reasoning | OWL and RDFS inference via Jena's rule-based and OWL reasoners. |
| TDB2 Triplestore | Native high-performance RDF triplestore for persistent graph storage. |
| Graph Store Protocol | SPARQL Graph Store HTTP Protocol for named graph management. |
| Multiple RDF Formats | Support for Turtle, JSON-LD, N-Triples, RDF/XML, and TriG serialization. |
| Ontology API | High-level API for working with OWL and RDFS ontologies. |

## Use Cases

| Name | Description |
|------|-------------|
| Knowledge Graph Management | Build and query knowledge graphs using RDF and SPARQL. |
| Linked Data Publishing | Publish Linked Data endpoints with Fuseki SPARQL server. |
| Semantic Search | Enable semantic search over structured RDF datasets. |
| Data Integration | Integrate heterogeneous data sources using RDF as a common data model. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Solr | Integrate full-text search with SPARQL queries via Solr text index. |
| Elasticsearch | Full-text search integration for Fuseki text search capabilities. |
| Spring Framework | Spring integration for Jena RDF operations in enterprise Java apps. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Jena Fuseki SPARQL API](openapi/apache-jena-fuseki-sparql-api.yaml)

### JSON Schema

6 schema files extracted from the Fuseki SPARQL API OpenAPI specification.

### JSON Structure

6 JSON Structure files converted from JSON Schema files.

### JSON-LD

- [Apache Jena Fuseki SPARQL API Context](json-ld/apache-jena-fuseki-sparql-api-context.jsonld)

### Examples

6 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Jena Fuseki SPARQL API](capabilities/shared/fuseki-sparql-api.yaml) — 4 operations for SPARQL queries and dataset management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Jena SPARQL Data Management](capabilities/sparql-data-management.yaml) | Apache Jena Fuseki SPARQL API | 5 | Data Engineer, Knowledge Graph Architect |

## Vocabulary

- [Apache Jena Vocabulary](vocabulary/apache-jena-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 7 actions, 1 workflow, and 2 personas

## Rules

- [Apache Jena Spectral Rules](rules/apache-jena-spectral-rules.yml) — 15 rules across 8 categories enforcing Apache Jena Fuseki API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
