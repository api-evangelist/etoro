# eToro

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

eToro is a leading social trading and multi-asset investment platform enabling individuals to trade and invest in stocks, cryptocurrencies, ETFs, commodities, currencies, and indices. The eToro Public API (available via the eToro Builders program) exposes REST endpoints and WebSocket streams for trading execution, real-time market data, portfolio and account management, watchlists, social feed interactions, price alerts, and AI-managed agent portfolios.

**Developer Portal:** https://builders.etoro.com/  
**API Documentation:** https://api-portal.etoro.com/  
**Base URL:** https://public-api.etoro.com/api/v1  
**WebSocket:** wss://ws.etoro.com/ws  

## APIs

- **Trading API** — Order placement, cancellation, and position management for real and demo accounts
- **Market Data API** — Instrument discovery, real-time rates, OHLCV candles, and WebSocket price streaming
- **Portfolio and Account API** — Account balances, cash accounts, and transaction history
- **Social and Discovery API** — Social feeds, user portfolio analytics, Pro Investor data
- **Watchlists API** — Create and manage custom instrument watchlists
- **Price Alerts API** — Threshold-based price notification management
- **Agent Portfolios API** — AI-managed portfolio creation with delegated user tokens (v2)

## Authentication

All requests require API key headers obtained from the eToro API Portal (Settings → Trading → API Key Management):

- `x-api-key` — Primary API credential
- `x-user-key` — User-specific key
- `x-request-id` — Unique UUID per request for tracing

A fully verified eToro account is required to receive API credentials.

## Rate Limits

- **Read (GET):** 60 requests/minute per user key
- **Write (POST/PUT/DELETE):** 20 requests/minute per user key
- Rate limits are enforced over a rolling 1-minute window
- HTTP 429 responses include `Retry-After`, `X-RateLimit-Limit`, `X-RateLimit-Remaining`, and `X-RateLimit-Reset` headers

## Pricing

API access is free for verified eToro account holders enrolled in the Builders early access program. No API subscription fees or per-call charges apply. Standard eToro trading fees (spreads, overnight rollover fees, withdrawal fees) apply to trades placed via the API. See https://www.etoro.com/trading/fees/ for full fee disclosures.
