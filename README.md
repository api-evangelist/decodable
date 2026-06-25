# Decodable (decodable)

Decodable is a fully managed stream-processing platform built on Apache Flink and Debezium. It lets teams build real-time data pipelines by connecting sources and sinks, transforming data with SQL or custom Flink jobs, and managing connections, streams, pipelines, and secrets through a REST API, a CLI, and declarative YAML.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/decodable/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/decodable/refs/heads/main/apis.yml)

## Tags

- Stream Processing
- Apache Flink
- Debezium
- Real Time Data
- Data Pipelines
- CDC

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Decodable Connections API

Manage connections that move data between Decodable streams and external source/sink systems (Kafka, Postgres CDC, S3, REST, and more), including create, list, get, update, delete, activate, and deactivate.

- **Human URL:** [https://docs.decodable.co/api/the-decodable-apis.html](https://docs.decodable.co/api/the-decodable-apis.html)
- **Base URL:** `https://<account>.api.decodable.co/v1alpha2`

#### Tags

- Connections
- Connectors
- Sources
- Sinks

#### Properties

- [Documentation](https://docs.decodable.co/connect.html)
- [API Reference](https://docs.decodable.co/api/the-decodable-apis.html)
- [OpenAPI](openapi/decodable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/decodable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/decodable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Decodable Streams API

Create and manage streams - the typed, schema-bearing channels that carry records between connections and pipelines - and request preview tokens to sample live stream data.

- **Human URL:** [https://docs.decodable.co/api/the-decodable-apis.html](https://docs.decodable.co/api/the-decodable-apis.html)
- **Base URL:** `https://<account>.api.decodable.co/v1alpha2`

#### Tags

- Streams
- Schemas
- Real Time Data

#### Properties

- [Documentation](https://docs.decodable.co/streams.html)
- [API Reference](https://docs.decodable.co/api/the-decodable-apis.html)
- [OpenAPI](openapi/decodable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/decodable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/decodable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Decodable Pipelines API

Create and manage pipelines that transform stream data using Decodable SQL or custom Apache Flink jobs, including activate, deactivate, and task-size/count execution control.

- **Human URL:** [https://docs.decodable.co/api/the-decodable-apis.html](https://docs.decodable.co/api/the-decodable-apis.html)
- **Base URL:** `https://<account>.api.decodable.co/v1alpha2`

#### Tags

- Pipelines
- SQL
- Apache Flink
- Transformations

#### Properties

- [Documentation](https://docs.decodable.co/pipelines.html)
- [API Reference](https://docs.decodable.co/api/the-decodable-apis.html)
- [OpenAPI](openapi/decodable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/decodable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/decodable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Decodable Secrets API

Securely store and manage the sensitive credentials (passwords, keys, tokens) that connections reference when authenticating to external systems.

- **Human URL:** [https://docs.decodable.co/api/the-decodable-apis.html](https://docs.decodable.co/api/the-decodable-apis.html)
- **Base URL:** `https://<account>.api.decodable.co/v1alpha2`

#### Tags

- Secrets
- Credentials
- Security

#### Properties

- [Documentation](https://docs.decodable.co/secrets.html)
- [API Reference](https://docs.decodable.co/api/the-decodable-apis.html)
- [OpenAPI](openapi/decodable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/decodable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/decodable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Decodable Resources API

Account-level and cross-cutting control-plane endpoints, including retrieving account details (and the data-plane hostname) and the declarative apply model that manages connections, streams, pipelines, and secrets as versioned YAML resources.

- **Human URL:** [https://docs.decodable.co/api/the-decodable-apis.html](https://docs.decodable.co/api/the-decodable-apis.html)
- **Base URL:** `https://<account>.api.decodable.co/v1alpha2`

#### Tags

- Resources
- Accounts
- Declarative

#### Properties

- [Documentation](https://docs.decodable.co/declarative/overview.html)
- [API Reference](https://docs.decodable.co/api/the-decodable-apis.html)
- [OpenAPI](openapi/decodable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/decodable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/decodable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/decodableco)
- [LinkedIn](https://www.linkedin.com/company/decodable)
- [Website](https://www.decodable.co)
- [Documentation](https://docs.decodable.co)
- [Plans](plans/decodable-plans-pricing.yml)
- [Rate Limits](rate-limits/decodable-rate-limits.yml)
- [Fin Ops](finops/decodable-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
