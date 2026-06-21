# Blockchair (blockchair)

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
