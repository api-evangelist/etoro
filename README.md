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

eToro is a leading social trading and multi-asset investment platform enabling individuals to trade and invest in stocks, cryptocurrencies, ETFs, commodities, currencies, and indices. The eToro Public API (available via the eToro Builders program) exposes REST endpoints and WebSocket streams for trading execution, real-time market data, portfolio and account management, watchlists, social feed interactions, price alerts, and AI-managed agent portfolios. Authentication uses API key headers (x-api-key and x-user-key) obtained from the eToro API Portal. The API is currently in early access and free for eligible verified eToro account holders.

**Areas:** Social Trading · Copy Trading · Investing · Market Data · Portfolio Management · Fintech · Trading · Stocks · Cryptocurrency · ETFs

## eToro on APIs.io

Everything profiled for eToro is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/etoro/](https://apis.io/providers/etoro/)** — or go straight to one of the APIs or properties below.

### APIs (29)

- [eToro Trading API](https://apis.io/apis/etoro/trading-api/) — Provides REST endpoints for executing and managing trades on eToro for both real and demo (paper trading) accounts. Supports creating market and limit…
- [eToro Market Data API](https://apis.io/apis/etoro/market-data-api/) — Provides REST and WebSocket access to real-time and historical market data for all asset classes available on eToro including stocks, cryptocurrencies,…
- [eToro Portfolio and Account API](https://apis.io/apis/etoro/portfolio-account-api/) — Provides REST endpoints for accessing account-level financial data including aggregated balances across all account types, cash account details, and…
- [eToro Social and Discovery API](https://apis.io/apis/etoro/social-discovery-api/) — Provides REST endpoints for accessing eToro's social trading layer. Supports reading and writing to personalized, news, and instrument-specific feeds,…
- [eToro Watchlists API](https://apis.io/apis/etoro/watchlists-api/) — Provides REST endpoints for programmatically creating, retrieving, and managing custom instrument watchlists on eToro. Supports adding and removing…
- [eToro Price Alerts API](https://apis.io/apis/etoro/price-alerts-api/) — Provides REST endpoints for creating, listing, and deleting price threshold alerts on eToro instruments. Enables programmatic configuration of price…
- [eToro Agent Portfolios API](https://apis.io/apis/etoro/agent-portfolios-api/) — Provides v2 REST endpoints for creating and managing AI-managed agent portfolios on eToro. Supports portfolio creation with named scopes, retrieval of all…
- [eToro Agent Portfolios API](https://apis.io/apis/etoro/etoro-agent-portfolios-api/) — The Agent Portfolios API from eToro — 8 operation(s) for agent portfolios.
- [eToro Asset Explorer API](https://apis.io/apis/etoro/etoro-asset-explorer-api/) — The Asset Explorer API from eToro — 3 operation(s) for asset explorer.
- [eToro Attachments API](https://apis.io/apis/etoro/etoro-attachments-api/) — The Attachments API from eToro — 1 operation(s) for attachments.
- [eToro Balances API](https://apis.io/apis/etoro/etoro-balances-api/) — The Balances API from eToro — 6 operation(s) for balances.
- [eToro Cash Accounts API](https://apis.io/apis/etoro/etoro-cash-accounts-api/) — The Cash Accounts API from eToro — 5 operation(s) for cash accounts.
- [eToro Clubs API](https://apis.io/apis/etoro/etoro-clubs-api/) — The Clubs API from eToro — 1 operation(s) for clubs.
- [eToro Comments and Replies API](https://apis.io/apis/etoro/etoro-comments-and-replies-api/) — The Comments and Replies API from eToro — 4 operation(s) for comments and replies.
- [eToro Comments API](https://apis.io/apis/etoro/etoro-comments-api/) — The Comments API from eToro — 1 operation(s) for comments.
- [eToro Deprecated API](https://apis.io/apis/etoro/etoro-deprecated-api/) — The Deprecated API from eToro — 14 operation(s) for deprecated.
- [eToro Feeds API](https://apis.io/apis/etoro/etoro-feeds-api/) — The Feeds API from eToro — 10 operation(s) for feeds.
- [eToro Identity API](https://apis.io/apis/etoro/etoro-identity-api/) — The Identity API from eToro — 1 operation(s) for identity.
- [eToro Likes API](https://apis.io/apis/etoro/etoro-likes-api/) — The Likes API from eToro — 3 operation(s) for likes.
- [eToro Market Data API](https://apis.io/apis/etoro/etoro-market-data-api/) — The Market Data API from eToro — 8 operation(s) for market data.
- [eToro Notifications API](https://apis.io/apis/etoro/etoro-notifications-api/) — The Notifications API from eToro — 1 operation(s) for notifications.
- [eToro PI Data API](https://apis.io/apis/etoro/etoro-pi-data-api/) — The PI Data API from eToro — 1 operation(s) for pi data.
- [eToro Posts API](https://apis.io/apis/etoro/etoro-posts-api/) — The Posts API from eToro — 9 operation(s) for posts.
- [eToro Price Alerts API](https://apis.io/apis/etoro/etoro-price-alerts-api/) — The Price Alerts API from eToro — 2 operation(s) for price alerts.
- [eToro Trading - Demo API](https://apis.io/apis/etoro/etoro-trading-demo-api/) — The Trading - Demo API from eToro — 18 operation(s) for trading - demo.
- [eToro Trading - Real API](https://apis.io/apis/etoro/etoro-trading-real-api/) — The Trading - Real API from eToro — 18 operation(s) for trading - real.
- [eToro Users Info API](https://apis.io/apis/etoro/etoro-users-info-api/) — The Users Info API from eToro — 6 operation(s) for users info.
- [eToro Users Stats API](https://apis.io/apis/etoro/etoro-users-stats-api/) — The Users Stats API from eToro — 4 operation(s) for users stats.
- [eToro Watchlists API](https://apis.io/apis/etoro/etoro-watchlists-api/) — The Watchlists API from eToro — 12 operation(s) for watchlists.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [mcp](https://apis.io/servers/etoro/mcp/)
- [mcp](https://apis.io/servers/etoro/mcp-2/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Etoro Agentic Access](https://apis.io/agentic-access/etoro/etoro-agentic-access/)

#### JSON Schema (161)

The data models the API reads and writes.

- [AccountBalanceData](https://apis.io/schemas/etoro/AccountBalanceData/)
- [AccountType](https://apis.io/schemas/etoro/AccountType/)
- [AgentPortfolioItem](https://apis.io/schemas/etoro/AgentPortfolioItem/)
- [AgentPortfolioUserTokenItem](https://apis.io/schemas/etoro/AgentPortfolioUserTokenItem/)
- [AggregatedPortfolioAccountTotals](https://apis.io/schemas/etoro/AggregatedPortfolioAccountTotals/)
- [AggregatedPortfolioInstrumentAggregate](https://apis.io/schemas/etoro/AggregatedPortfolioInstrumentAggregate/)
- [AggregatedPortfolioMirrorAggregate](https://apis.io/schemas/etoro/AggregatedPortfolioMirrorAggregate/)
- [AggregatedPortfolioMirrorTotals](https://apis.io/schemas/etoro/AggregatedPortfolioMirrorTotals/)
- [AggregatedPortfolioResponse](https://apis.io/schemas/etoro/AggregatedPortfolioResponse/)
- [AssetsHistoryAsset](https://apis.io/schemas/etoro/AssetsHistoryAsset/)
- [AssetsHistoryEntry](https://apis.io/schemas/etoro/AssetsHistoryEntry/)
- [AssetsHistoryResponse](https://apis.io/schemas/etoro/AssetsHistoryResponse/)
- [Attachment](https://apis.io/schemas/etoro/Attachment/)
- [Attachments](https://apis.io/schemas/etoro/Attachments/)
- [Avatar](https://apis.io/schemas/etoro/Avatar/)
- [BalancesErrorResponse](https://apis.io/schemas/etoro/BalancesErrorResponse/)
- [BankAccount](https://apis.io/schemas/etoro/BankAccount/)
- [BankAccountIdentifier](https://apis.io/schemas/etoro/BankAccountIdentifier/)
- [BankIdentifierEntry](https://apis.io/schemas/etoro/BankIdentifierEntry/)
- [BankTransferDetails](https://apis.io/schemas/etoro/BankTransferDetails/)
- [BusinessErrorResponse](https://apis.io/schemas/etoro/BusinessErrorResponse/)
- [Card](https://apis.io/schemas/etoro/Card/)
- [CardTransactionDetails](https://apis.io/schemas/etoro/CardTransactionDetails/)
- [CashAccount](https://apis.io/schemas/etoro/CashAccount/)
- [CashAccountContactInfo](https://apis.io/schemas/etoro/CashAccountContactInfo/)
- …and 136 more published on APIs.io

#### Examples (166)

Example requests and responses.

- [Cancelcloseorder Response 200](https://apis.io/examples/etoro/cancelCloseOrder-response-200/)
- [Cancelcloseorderdemo Response 200](https://apis.io/examples/etoro/cancelCloseOrderDemo-response-200/)
- [Canceldemoorder Response 200](https://apis.io/examples/etoro/cancelDemoOrder-response-200/)
- [Cancellimitorder Response 200](https://apis.io/examples/etoro/cancelLimitOrder-response-200/)
- [Cancellimitorderdemo Response 200](https://apis.io/examples/etoro/cancelLimitOrderDemo-response-200/)
- [Cancelopenmarketorder Response 200](https://apis.io/examples/etoro/cancelOpenMarketOrder-response-200/)
- [Cancelopenmarketorderdemo Response 200](https://apis.io/examples/etoro/cancelOpenMarketOrderDemo-response-200/)
- [Cancelrealorder Response 200](https://apis.io/examples/etoro/cancelRealOrder-response-200/)
- [Closepositionbymarketrate Response 200](https://apis.io/examples/etoro/closePositionByMarketRate-response-200/)
- [Closepositionbymarketratedemo Response 200](https://apis.io/examples/etoro/closePositionByMarketRateDemo-response-200/)
- [Createacommentonapost Request](https://apis.io/examples/etoro/createACommentOnAPost-request/)
- [Createapricealert Request](https://apis.io/examples/etoro/createAPriceAlert-request/)
- [Createapricealert Response 201](https://apis.io/examples/etoro/createAPriceAlert-response-201/)
- [Createapricealert Response 400](https://apis.io/examples/etoro/createAPriceAlert-response-400/)
- [Createapricealert Response 401](https://apis.io/examples/etoro/createAPriceAlert-response-401/)
- [Createapricealert Response 403](https://apis.io/examples/etoro/createAPriceAlert-response-403/)
- [Createapricealert Response 404](https://apis.io/examples/etoro/createAPriceAlert-response-404/)
- [Createapricealert Response 422](https://apis.io/examples/etoro/createAPriceAlert-response-422/)
- [Createapricealert Response 429](https://apis.io/examples/etoro/createAPriceAlert-response-429/)
- [Createapricealert Response 500](https://apis.io/examples/etoro/createAPriceAlert-response-500/)
- [Createareply Request](https://apis.io/examples/etoro/createAReply-request/)
- [Createagentportfolio Response 400](https://apis.io/examples/etoro/createAgentPortfolio-response-400/)
- [Createagentportfolio Response 401](https://apis.io/examples/etoro/createAgentPortfolio-response-401/)
- [Createagentportfolio Response 429](https://apis.io/examples/etoro/createAgentPortfolio-response-429/)
- [Createagentportfolio Response 500](https://apis.io/examples/etoro/createAgentPortfolio-response-500/)
- …and 141 more published on APIs.io

#### Collections (22)

Postman and Open Collection request collections.

- [Deprecated eToro Public API operations Agent Portfolios API](https://apis.io/collections/etoro/open-etoro-agent-portfolios-api/)
- [Deprecated eToro Public API operations Agent Portfolios Asset Explorer API](https://apis.io/collections/etoro/open-etoro-asset-explorer-api/)
- [Deprecated eToro Public API operations Agent Portfolios Attachments API](https://apis.io/collections/etoro/open-etoro-attachments-api/)
- [Deprecated eToro Public API operations Agent Portfolios Balances API](https://apis.io/collections/etoro/open-etoro-balances-api/)
- [Deprecated eToro Public API operations Agent Portfolios Cash Accounts API](https://apis.io/collections/etoro/open-etoro-cash-accounts-api/)
- [Deprecated eToro Public API operations Agent Portfolios Clubs API](https://apis.io/collections/etoro/open-etoro-clubs-api/)
- [Deprecated eToro Public API operations Agent Portfolios Comments and Replies API](https://apis.io/collections/etoro/open-etoro-comments-and-replies-api/)
- [Deprecated eToro Public API operations Agent Portfolios Comments API](https://apis.io/collections/etoro/open-etoro-comments-api/)
- [eToro Public API operations Agent Portfolios Deprecated API](https://apis.io/collections/etoro/open-etoro-deprecated-api/)
- [Deprecated eToro Public API operations Agent Portfolios Feeds API](https://apis.io/collections/etoro/open-etoro-feeds-api/)
- [Deprecated eToro Public API operations Agent Portfolios Identity API](https://apis.io/collections/etoro/open-etoro-identity-api/)
- [Deprecated eToro Public API operations Agent Portfolios Likes API](https://apis.io/collections/etoro/open-etoro-likes-api/)
- [Deprecated eToro Public API operations Agent Portfolios Market Data API](https://apis.io/collections/etoro/open-etoro-market-data-api/)
- [Deprecated eToro Public API operations Agent Portfolios Notifications API](https://apis.io/collections/etoro/open-etoro-notifications-api/)
- [Deprecated eToro Public API operations Agent Portfolios PI Data API](https://apis.io/collections/etoro/open-etoro-pi-data-api/)
- [Deprecated eToro Public API operations Agent Portfolios Posts API](https://apis.io/collections/etoro/open-etoro-posts-api/)
- [Deprecated eToro Public API operations Agent Portfolios Price Alerts API](https://apis.io/collections/etoro/open-etoro-price-alerts-api/)
- [Deprecated eToro Public API operations Agent Portfolios Trading - Demo API](https://apis.io/collections/etoro/open-etoro-trading-demo-api/)
- [Deprecated eToro Public API operations Agent Portfolios Trading - Real API](https://apis.io/collections/etoro/open-etoro-trading-real-api/)
- [Deprecated eToro Public API operations Agent Portfolios Users Info API](https://apis.io/collections/etoro/open-etoro-users-info-api/)
- [Deprecated eToro Public API operations Agent Portfolios Users Stats API](https://apis.io/collections/etoro/open-etoro-users-stats-api/)
- [Deprecated eToro Public API operations Agent Portfolios Watchlists API](https://apis.io/collections/etoro/open-etoro-watchlists-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [eToro — jsonschema rules](https://apis.io/rules/etoro/etoro-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Etoro Domain Security](https://apis.io/security/etoro/etoro-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Plans](https://apis.io/plans/etoro/plans/)

#### Rate limits (1)

Published request limits.

- [Rate Limits](https://apis.io/rate-limits/etoro/rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Finops](https://apis.io/finops/etoro/finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.etoro.com/)
- [Documentation](https://api-portal.etoro.com/)
- [Getting started](https://builders.etoro.com/learn/getting-started-with-etoro-api-v2)
- [Blog](https://www.etoro.com/blog/feed/)

## API Evangelist rating

**Kin Score 27.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 47.1 |
| Contract governance | 23.5 |
| Operational transparency | 0.0 |
| Developer ergonomics | 33.3 |
| Access clarity | 5.3 |

**Agent readiness 31.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | platform (partial credit) |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 15.7** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/etoro/](https://apis.io/providers/etoro/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for eToro: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/etoro/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
