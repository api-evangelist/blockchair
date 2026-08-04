# Blockchair (blockchair)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Blockchair is a multi-blockchain explorer and data API providing unified access to on-chain data across 40+ blockchains (Bitcoin, Ethereum, Litecoin, Dogecoin, Ripple, Stellar, Monero, Cardano, and more). The REST API at api.blockchair.com exposes per-chain dashboards (address, transaction, block), raw node data, network stats, a SQL-like database query interface over outputs and other tables, and transaction broadcasting, authenticated with a simple key query parameter.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/blockchair/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/blockchair/refs/heads/main/apis.yml)

## Tags

- Blockchain
- Cryptocurrency
- Explorer
- Bitcoin
- Ethereum
- On-Chain Data

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Blockchair Address Dashboards API

Per-chain address dashboards returning balance, transaction list, and aggregated stats for a single address, a set of up to 100 addresses, or an extended public key (xpub/ypub/zpub) across Bitcoin-like and Ethereum-like chains.

- **Human URL:** [https://blockchair.com/api/docs](https://blockchair.com/api/docs)
- **Base URL:** `https://api.blockchair.com`

#### Tags

- Address
- Dashboards
- Balance

#### Properties

- [Documentation](https://blockchair.com/api/docs)
- [API Reference](https://github.com/Blockchair/Blockchair.Support/blob/master/API_DOCUMENTATION_EN.md)
- [OpenAPI](openapi/blockchair-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blockchair.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchair.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockchair Transaction Dashboards API

Transaction dashboards returning a parsed view of one transaction or a set of transactions by hash, including inputs, outputs, fees, and confirmation data, across supported chains.

- **Human URL:** [https://blockchair.com/api/docs](https://blockchair.com/api/docs)
- **Base URL:** `https://api.blockchair.com`

#### Tags

- Transaction
- Dashboards

#### Properties

- [Documentation](https://blockchair.com/api/docs)
- [API Reference](https://github.com/Blockchair/Blockchair.Support/blob/master/API_DOCUMENTATION_EN.md)
- [OpenAPI](openapi/blockchair-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blockchair.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchair.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockchair Block Dashboards API

Block dashboards returning a parsed view of one block or a set of blocks by height or hash, including header fields, transaction references, and block statistics, across supported chains.

- **Human URL:** [https://blockchair.com/api/docs](https://blockchair.com/api/docs)
- **Base URL:** `https://api.blockchair.com`

#### Tags

- Block
- Dashboards

#### Properties

- [Documentation](https://blockchair.com/api/docs)
- [API Reference](https://github.com/Blockchair/Blockchair.Support/blob/master/API_DOCUMENTATION_EN.md)
- [OpenAPI](openapi/blockchair-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blockchair.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchair.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockchair Raw Data API

Raw node-level data for blocks and transactions (and ledgers, accounts, and operations on non-UTXO chains) as returned by the underlying blockchain node, for clients that need the unprocessed payload.

- **Human URL:** [https://blockchair.com/api/docs](https://blockchair.com/api/docs)
- **Base URL:** `https://api.blockchair.com`

#### Tags

- Raw Data
- Node

#### Properties

- [Documentation](https://blockchair.com/api/docs)
- [API Reference](https://github.com/Blockchair/Blockchair.Support/blob/master/API_DOCUMENTATION_EN.md)
- [OpenAPI](openapi/blockchair-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blockchair.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchair.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockchair Stats API

Network statistics endpoints returning overall blockchain metrics (blocks, transactions, market data, difficulty, mempool) for a single chain, all chains at once, or cross-chain tokens such as USDT and USDC.

- **Human URL:** [https://blockchair.com/api/docs](https://blockchair.com/api/docs)
- **Base URL:** `https://api.blockchair.com`

#### Tags

- Stats
- Statistics
- Network

#### Properties

- [Documentation](https://blockchair.com/api/docs)
- [API Reference](https://github.com/Blockchair/Blockchair.Support/blob/master/API_DOCUMENTATION_EN.md)
- [OpenAPI](openapi/blockchair-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blockchair.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchair.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockchair Outputs Database API

SQL-like database query interface over the outputs table (and blocks, transactions, and addresses) on Bitcoin-like chains, supporting filtering by column, sorting, aggregation, offset, and limit for analytical queries.

- **Human URL:** [https://blockchair.com/api/docs](https://blockchair.com/api/docs)
- **Base URL:** `https://api.blockchair.com`

#### Tags

- Outputs
- Database
- Query

#### Properties

- [Documentation](https://blockchair.com/api/docs)
- [API Reference](https://github.com/Blockchair/Blockchair.Support/blob/master/API_DOCUMENTATION_EN.md)
- [OpenAPI](openapi/blockchair-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blockchair.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchair.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Blockchair Broadcast API

Transaction broadcasting endpoint that relays a signed, raw transaction to the network of the selected chain via an HTTP POST.

- **Human URL:** [https://blockchair.com/api/docs](https://blockchair.com/api/docs)
- **Base URL:** `https://api.blockchair.com`

#### Tags

- Broadcast
- Push
- Transaction

#### Properties

- [Documentation](https://blockchair.com/api/docs)
- [API Reference](https://github.com/Blockchair/Blockchair.Support/blob/master/API_DOCUMENTATION_EN.md)
- [OpenAPI](openapi/blockchair-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blockchair.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blockchair.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Blockchair)
- [LinkedIn](https://www.linkedin.com/company/blockchair)
- [Website](https://blockchair.com)
- [Documentation](https://blockchair.com/api/docs)
- [Plans](plans/blockchair-plans-pricing.yml)
- [Rate Limits](rate-limits/blockchair-rate-limits.yml)
- [Fin Ops](finops/blockchair-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
