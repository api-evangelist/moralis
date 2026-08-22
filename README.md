# Moralis (moralis)

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

Moralis is a Web3 data platform offering REST-based Data APIs for EVM and Solana chains, real-time Streams (webhooks), Datashare exports, and an enterprise Data Indexer. Supports 30+ chains for wallets, analytics, automation, and data pipelines.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/moralis/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/moralis/refs/heads/main/apis.yml)

## Tags

- Web3
- Blockchain
- Data API
- Streams
- Indexing

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Moralis EVM API

REST API for EVM chain data (NFTs, tokens, balances, transactions, blocks, resolve domain) across Ethereum, Polygon, Arbitrum, Optimism, Base, Avalanche, BNB, etc.

- **Human URL:** [https://docs.moralis.com/web3-data-api/evm](https://docs.moralis.com/web3-data-api/evm)
- **Base URL:** `https://deep-index.moralis.io/api/v2.2`

#### Tags

- REST
- EVM

#### Properties

- [Documentation](https://docs.moralis.com/web3-data-api/evm)
- [OpenAPI](openapi/moralis-evm-api-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/moralis-evm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moralis-evm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moralis Solana API

REST API for Solana on-chain data (accounts, NFTs, tokens, transactions).

- **Human URL:** [https://docs.moralis.com/web3-data-api/solana](https://docs.moralis.com/web3-data-api/solana)
- **Base URL:** `https://solana-gateway.moralis.io`

#### Tags

- REST
- Solana

#### Properties

- [Documentation](https://docs.moralis.com/web3-data-api/solana)
- [Postman Collection](collections/moralis-evm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moralis-evm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moralis Streams API

REST API for managing real-time blockchain event streams delivered via webhooks.

- **Human URL:** [https://docs.moralis.com/streams-api](https://docs.moralis.com/streams-api)
- **Base URL:** `https://api.moralis-streams.com`

#### Tags

- REST
- Streams
- Webhooks

#### Properties

- [Documentation](https://docs.moralis.com/streams-api)
- [Postman Collection](collections/moralis-evm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moralis-evm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moralis Auth API

REST API for Sign-In with Ethereum / Solana challenge generation and verification.

- **Human URL:** [https://docs.moralis.com/authentication-api](https://docs.moralis.com/authentication-api)
- **Base URL:** `https://authapi.moralis.io`

#### Tags

- REST
- Auth

#### Properties

- [Documentation](https://docs.moralis.com/authentication-api)
- [Postman Collection](collections/moralis-evm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moralis-evm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Moralis Datashare

Bulk historical and ongoing blockchain dataset exports (Parquet/CSV via S3 / Snowflake share).

- **Human URL:** [https://moralis.com/datashare](https://moralis.com/datashare)
- **Base URL:** `n/a (export)`

#### Tags

- Bulk
- Export

#### Properties

- [Documentation](https://moralis.com/datashare)
- [Postman Collection](collections/moralis-evm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moralis-evm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/MoralisWeb3)
- [LinkedIn](https://www.linkedin.com/company/moralisweb3)
- [Website](https://moralis.com/)
- [Plans](plans/moralis-plans-pricing.yml)
- [Rate Limits](rate-limits/moralis-rate-limits.yml)
- [Fin Ops](finops/moralis-finops.yml)
- [L L Ms Txt](https://docs.moralis.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
