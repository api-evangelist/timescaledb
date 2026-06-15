# TimescaleDB / Tiger Data (timescaledb)

TimescaleDB (now part of Tiger Data) is a PostgreSQL-native time-series database featuring hypertables, columnstore (Hypercore), continuous aggregates, retention policies and hyperfunctions. The managed Tiger Cloud platform exposes a public REST API for managing projects, services, VPCs, peering and read replicas, while the database itself is consumed via standard PostgreSQL wire protocol.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/timescaledb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/timescaledb/refs/heads/main/apis.yml)

## Tags

- Database
- Time-Series
- PostgreSQL
- Open Source
- Cloud
- Hypertables
- Continuous Aggregates
- Tiger Cloud

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### Tiger Cloud REST API

Public REST API for the Tiger Cloud control plane — manage projects, services (PostgreSQL/TimescaleDB instances), VPCs, peering, read replicas and analytics events. Authenticated with public/private API key pairs.

- **Human URL:** [https://www.tigerdata.com/docs/reference/tiger-cloud-rest](https://www.tigerdata.com/docs/reference/tiger-cloud-rest)
- **Base URL:** `https://console.cloud.tigerdata.com/public/api/v1`

#### Tags

- REST
- Control Plane
- Services
- VPC
- Replicas

#### Properties

- [Documentation](https://www.tigerdata.com/docs/reference/tiger-cloud-rest)
- [OpenAPI](openapi/timescaledb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/timescaledb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/timescaledb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Open A P I Source](https://raw.githubusercontent.com/timescale/tiger-cli/main/openapi.yaml)
- [SDK](https://github.com/timescale/tiger-cli)

### TimescaleDB PostgreSQL Wire Interface

The database itself is accessed via the PostgreSQL wire protocol (port 5432), with TimescaleDB SQL functions for hypertable management, compression, continuous aggregates and hyperfunctions. Not a REST API.

- **Human URL:** [https://www.tigerdata.com/docs/api/latest](https://www.tigerdata.com/docs/api/latest)
- **Base URL:** `postgres://<host>:5432/<db>`

#### Tags

- PostgreSQL
- SQL
- Wire Protocol

#### Properties

- [Documentation](https://www.tigerdata.com/docs/api/latest)
- [Source Code](https://github.com/timescale/timescaledb)
- [Postman Collection](collections/timescaledb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/timescaledb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/timescaledb)
- [Website](https://www.tigerdata.com/)
- [Legacy Website](https://www.timescale.com/)
- [Documentation](https://www.tigerdata.com/docs)
- [Pricing](https://www.tigerdata.com/pricing)
- [Git Hub](https://github.com/timescale)
- [Console](https://console.cloud.timescale.com/)
- [Plans](plans/timescaledb-plans-pricing.yml)
- [Rate Limits](rate-limits/timescaledb-rate-limits.yml)
- [Fin Ops](finops/timescaledb-finops.yml)
- [Integrations](https://www.tigerdata.com/partners)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
