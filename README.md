# brapi (brapi)

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

brapi.dev is a Brazilian financial data REST API aggregating public market data from B3 (stock exchange), CVM (securities commission), and Banco Central (central bank). It provides real-time and historical stock quotes, fundamentals, dividends, cryptocurrency prices in BRL, foreign exchange rates, and economic indicators such as IPCA, IGPM, and SELIC. With over 20,000 active developers, brapi.dev offers tiered subscription plans from free to Pro, with up to 500,000 requests per month and data updated every 5 minutes.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/brapi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/brapi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Finance
- Brazilian Financial Data
- Stock Market
- Investments
- Economic Indicators
- Cryptocurrency

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-19

## APIs

### brapi Quotes API

Retrieve real-time and historical OHLCV (Open, High, Low, Close, Volume) quote data for securities listed on the B3 Brazilian stock exchange. Supports bulk asset requests and returns standardized JSON without web scraping.

- **Human URL:** [https://brapi.dev/docs](https://brapi.dev/docs)

#### Tags

- Stock Quotes
- B3
- Real-Time Data
- Historical Data

#### Properties

- [Documentation](https://brapi.dev/docs)
- [OpenAPI](openapi/brapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/brapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### brapi Fundamentals API

Access structured financial statement data for Brazilian listed companies including balance sheets (BP), income statements (DRE), cash flow (DFC), and value added statements (DVA). Historical data available from 2009.

- **Human URL:** [https://brapi.dev/docs](https://brapi.dev/docs)

#### Tags

- Fundamentals
- Balance Sheet
- Income Statement
- Financial Statements

#### Properties

- [Documentation](https://brapi.dev/docs)
- [Postman Collection](collections/brapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### brapi Dividends API

Retrieve complete dividend and earnings distribution history for B3-listed securities, enabling portfolio yield analysis and income tracking.

- **Human URL:** [https://brapi.dev/docs](https://brapi.dev/docs)

#### Tags

- Dividends
- Distributions
- Corporate Actions

#### Properties

- [Documentation](https://brapi.dev/docs)
- [Postman Collection](collections/brapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### brapi Cryptocurrency API

Access cryptocurrency prices denominated in Brazilian Reals (BRL), supporting investment analysis and portfolio management for Brazilian digital asset investors.

- **Human URL:** [https://brapi.dev/docs](https://brapi.dev/docs)

#### Tags

- Cryptocurrency
- BRL
- Digital Assets

#### Properties

- [Documentation](https://brapi.dev/docs)
- [Postman Collection](collections/brapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### brapi Exchange Rates API

Retrieve Brazilian Real (BRL) exchange rates against major global currencies, sourced from Banco Central do Brasil data.

- **Human URL:** [https://brapi.dev/docs](https://brapi.dev/docs)

#### Tags

- Foreign Exchange
- Currency
- BRL

#### Properties

- [Documentation](https://brapi.dev/docs)
- [Postman Collection](collections/brapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### brapi Economic Indicators API

Access Brazilian macroeconomic indicators including IPCA (consumer price index), IGPM (market general price index), INPC, and SELIC interest rate data published by Banco Central do Brasil.

- **Human URL:** [https://brapi.dev/docs](https://brapi.dev/docs)

#### Tags

- Inflation
- Interest Rates
- Economic Data
- SELIC

#### Properties

- [Documentation](https://brapi.dev/docs)
- [Postman Collection](collections/brapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/brapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/brapi-dev)
- [Website](https://brapi.dev)
- [Documentation](https://brapi.dev/docs)
- [Pricing](https://brapi.dev/pricing)
- [Authentication](https://brapi.dev/docs)
- [Sign Up](https://brapi.dev/register)
- [L L Ms Txt](https://brapi.dev/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
