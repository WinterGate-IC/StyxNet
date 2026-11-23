# Architecture

This is a high-level public description. Sensitive implementation detail and credentials are not published.

## Layers

1. **Collection layer** — engines, onion discovery, proxy/Tor transport.
2. **Correlation layer** — usernames, identities, targets, observations.
3. **Validation layer** — page inspection, linkage scoring, relevance checks.
4. **Evidence layer** — archives, ledger claims, audit logs.
5. **Operations layer** — admin controls, rate limits, retention, health.

## Design goals

- Bounded concurrency
- Graceful fallback
- Evidence preservation
- Confirmed-only active intelligence
- Safe and auditable operation

## Not published

- Credentials, tokens, or keys
- Bypass or exploit techniques
- Private targeting details
- Sensitive operational configuration
