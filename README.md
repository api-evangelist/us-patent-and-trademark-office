# US Patent and Trademark Office

The US Patent and Trademark Office (USPTO) is responsible for granting patents and registering trademarks to protect intellectual property in the United States. The USPTO examines patent applications to determine if an invention is new, non-obvious, and useful, and grants patents to those that meet the criteria. They also register trademarks, which are words, phrases, symbols, or designs that distinguish goods or services of one entity from another.

The USPTO Open Data Portal (ODP) provides free programmatic access to patent applications, PTAB trial proceedings, petition decisions, trademark status, and bulk datasets.

**Developer Portal:** https://data.uspto.gov/apis/getting-started  
**APIs.yml:** https://raw.githubusercontent.com/api-evangelist/us-patent-and-trademark-office/refs/heads/main/apis.yml

---

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Federal Government, Patents, Trademarks, Intellectual Property, Open Data

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-03

---

## APIs

### USPTO Open Data Portal API
Search and retrieve USPTO patent applications, PTAB trial proceedings, petition decisions, and bulk datasets.

- **Base URL:** `https://api.uspto.gov`
- **Auth:** API Key (`X-API-KEY` header)
- **OpenAPI:** [openapi/uspto-open-data-portal-openapi.yml](openapi/uspto-open-data-portal-openapi.yml)
- **Documentation:** https://data.uspto.gov/apis/getting-started

Key endpoints:
- `GET/POST /api/v1/patent/applications/search` — Search patent applications
- `GET /api/v1/patent/applications/{applicationNumberText}` — Get patent application details
- `GET /api/v1/patent/trials/proceedings/search` — Search PTAB proceedings
- `GET /api/v1/petition/decisions/search` — Search petition decisions
- `GET /api/v1/datasets/products/search` — Browse bulk datasets

### USPTO Trademark Status and Document Retrieval (TSDR) API
Access trademark case status, prosecution documents, and images.

- **Base URL:** `https://tsdrapi.uspto.gov`
- **Auth:** API Key (`USPTO-API-KEY` header)
- **OpenAPI:** [openapi/uspto-tsdr-openapi.yml](openapi/uspto-tsdr-openapi.yml)
- **Documentation:** https://developer.uspto.gov/api-catalog/tsdr-data-api

Key endpoints:
- `GET /ts/cd/caseMultiStatus/{type}` — Get trademark case status
- `GET /ts/cd/casedocs/{caseid}/info` — List trademark case documents

---

## Artifacts

| Type | Files |
|------|-------|
| OpenAPI Specs | [openapi/](openapi/) — 2 specs |
| Examples | [examples/](examples/) — 3 examples |
| Spectral Rules | [rules/uspto-rules.yml](rules/uspto-rules.yml) |
| Naftiko Capabilities | [capabilities/](capabilities/) — 1 workflow + 2 shared |
| JSON Schema | [json-schema/](json-schema/) — 2 schemas |
| JSON Structure | [json-structure/](json-structure/) — 1 structure |
| JSON-LD | [json-ld/](json-ld/) — 1 context |
| Vocabulary | [vocabulary/](vocabulary/) — 1 vocabulary |

---

## Capabilities

### Shared Definitions
- [capabilities/shared/open-data-portal.yaml](capabilities/shared/open-data-portal.yaml) — USPTO ODP API (7 operations)
- [capabilities/shared/tsdr.yaml](capabilities/shared/tsdr.yaml) — USPTO TSDR API (2 operations)

### Workflow Capabilities
- [capabilities/intellectual-property-research.yaml](capabilities/intellectual-property-research.yaml) — Unified IP research (10 MCP tools)
  - Patent application search and retrieval
  - PTAB trial proceedings and decisions
  - Trademark case status and documents
  - Bulk dataset access

---

## Use Cases

- **Patent Research** — Search prior art, track pending applications, monitor competitor filings
- **Trademark Availability** — Check if a trademark is available before filing
- **PTAB Monitoring** — Track inter partes review and post-grant review proceedings
- **IP Portfolio Management** — Monitor a portfolio of patents and trademarks
- **Legal and Compliance Research** — Research patent validity and trademark ownership
- **Economic and Academic Research** — Download bulk patent datasets for analysis

---

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
