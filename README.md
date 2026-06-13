# eToro

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
