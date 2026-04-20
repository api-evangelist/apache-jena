# Apache Jena (apache-jena)
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
