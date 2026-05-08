# TimescaleDB / Tiger Data (timescaledb)

TimescaleDB is a PostgreSQL-native time-series database (now Tiger Data). It adds hypertables, Hypercore columnstore, continuous aggregates, retention policies and hyperfunctions to PostgreSQL. The managed cloud platform is Tiger Cloud (formerly Timescale Cloud), which exposes a public REST API for control-plane operations.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **Tiger Cloud REST API** — `https://console.cloud.tigerdata.com/public/api/v1` — manage projects, services, VPCs, peering, replicas, analytics. API-key auth. [OpenAPI](openapi/timescaledb-openapi.yml).
- **TimescaleDB PostgreSQL Wire** — port `5432` — query the database itself via standard PostgreSQL protocol; [SQL function reference](https://www.tigerdata.com/docs/api/latest).

## OpenAPI (fetched 2026-05-08)
`openapi/timescaledb-openapi.yml` — Tiger Cloud API v1.0.0 (OpenAPI 3.0.3), upstream <https://github.com/timescale/tiger-cli/blob/main/openapi.yaml>.

## Tags
Database, Time-Series, PostgreSQL, Open Source, Cloud, Hypertables, Continuous Aggregates, Tiger Cloud

## Common Properties
- [Website](https://www.tigerdata.com/) (legacy: <https://www.timescale.com/>)
- [Documentation](https://www.tigerdata.com/docs)
- [Pricing](https://www.tigerdata.com/pricing)
- [Console](https://console.cloud.timescale.com/)
- [GitHub](https://github.com/timescale)
- [Plans](plans/timescaledb-plans-pricing.yml) — reconciled
- [Rate Limits](rate-limits/timescaledb-rate-limits.yml) — partially reconciled (resource caps; numeric REST limits not published)
- [FinOps](finops/timescaledb-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
- **Community / Self-Hosted** — Apache 2.0 / TSL, free.
- **Tiger Cloud Free Trial** — 30 days Performance, no card.
- **Performance** — from $30/mo; up to 8 vCPU / 32 GB / 5K IOPS.
- **Scale** — from $36/mo; up to 32 vCPU / 128 GB / 40K IOPS.
- **Enterprise** — custom; up to 64 vCPU / 256 GB / 80K IOPS.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
