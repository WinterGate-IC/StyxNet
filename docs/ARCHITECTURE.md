# Architecture

This is a high-level public description of the platform design.

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

## Scope

This document describes the platform's design, defensive purpose, and operating model. It is documentation, not an operational manual.
