# StyxNet

**Secure Deep Web Intelligence Engine**  
Built by the **WinterGate Intelligence Collective**

StyxNet is a passive multi-surface OSINT collection, correlation, validation, and evidence-preservation platform. It brings surface-web search, deep-web discovery, onion routing, identity correlation, target observation, and page-level linkage validation into one intelligence system.

**Capability score: 91/100 — Tier S-**  
**Power score: 94/100 · Intel capability: 89/100**

---

## At a glance

| | |
|---|---|
| **Name** | StyxNet |
| **Type** | Passive multi-surface OSINT intelligence platform |
| **Operator** | WinterGate Intelligence Collective |
| **Primary use** | Lawful research, defensive intelligence, platform safety, threat analysis |
| **Validation** | Ominis-OSINT page-level linkage checks, relevance checks, confirmed-only active intel |
| **Data hygiene** | Quarantine retention, 3-day cleanup, audit logs |
| **Capability tier** | S- |
| **Overall score** | 91/100 |
| **Public documentation** | This repository |

---

## What StyxNet is

Most OSINT tools operate in one lane: search aggregation, username lookup, onion indexing, or identity graphing. StyxNet combines those lanes into a single operating system for intelligence collection.

StyxNet is built around four ideas:

1. **Collect broadly** — surface, deep, and onion sources.
2. **Correlate carefully** — usernames, identities, targets, observations, and ledger claims.
3. **Validate deeply** — read the page, not just the status code.
4. **Preserve responsibly** — evidence, audit trails, quarantine, and retention controls.

---

## Core capabilities

- Multi-engine surface, deep, and onion search
- Tor routing, proxy rotation, and fallback lanes
- Automated engine discovery and network growth
- Username hunts and identity correlation
- Target tracking, observations, and ledger claims
- Evidence archives with exportable reports
- Ominis-OSINT page-level linkage validation
- Confirmed-only active intelligence
- Relevance validation for content findings
- Three-day quarantine retention and cleanup
- Admin controls, audit logs, rate limits, and health monitoring

See [`docs/CAPABILITIES.md`](docs/CAPABILITIES.md) for the full capability profile.

---

## Validation depth

StyxNet does not treat HTTP 200 as proof. Profile-like results are read and checked for evidence such as:

- Page metadata and canonical URL
- Redirects
- Structured data and embedded JSON
- JSON-LD and microdata
- Author metadata and author links
- JavaScript state
- Entity/user activity linked to the handle

Results are classified as **Confirmed**, **Linkage-confirmed**, or **Unverified**. Confirmed results are prioritized; weak profile-like results are demoted. Ordinary articles are not falsely labelled.

Content findings receive a separate relevance pass so site-wide boilerplate does not create false marketplace or phishing findings.

See [`docs/VALIDATION.md`](docs/VALIDATION.md) for details.

---

## Capability score

StyxNet is scored across eight dimensions:

| Dimension | Score |
|---|---:|
| Collection breadth | 96 |
| Data scale | 88 |
| Validation depth | 93 |
| Automation | 90 |
| Identity/targeting | 89 |
| Resilience | 86 |
| Admin/operations | 92 |
| Data hygiene | 94 |

**Overall: 91/100 — Tier S-**  
**Power: 94/100**  
**Intel capability: 89/100**

The full model is in [`scoring/SCORING.md`](scoring/SCORING.md).

---

## Legal and responsible use

StyxNet is a **legal, passive OSINT platform** designed for lawful research, defensive intelligence, platform safety, and threat analysis.

- StyxNet reads public pages. It does not access private systems, bypass authentication, supply stolen credentials, or provide exploitation instructions.
- Public-source OSINT is generally lawful, and StyxNet is built for that use. As with any OSINT work, comply with applicable law, platform terms, and privacy obligations.
- Do not use StyxNet for harassment, doxxing, stalking, unauthorised access, or targeting private individuals.
- Operators are responsible for applicable law, platform terms, and ethical handling of public data.
- Confirmation means evidence linkage, not legal ownership or universal truth.

Read [`docs/LEGAL.md`](docs/LEGAL.md) and [`docs/RESPONSIBLE_USE.md`](docs/RESPONSIBLE_USE.md) before operating or citing results.

---

## Who it is for

- Defenders and security researchers
- Platform trust and safety teams
- Threat-intelligence analysts
- Journalists and investigators working with public evidence
- Organisations documenting abuse, extremism, or coordinated harassment

StyxNet is not a target list, a hacking tool, or a service for contacting or exposing private individuals.

---

## Repository map

| Path | Contents |
|---|---|
| [`docs/OVERVIEW.md`](docs/OVERVIEW.md) | What StyxNet is and how it is positioned |
| [`docs/CAPABILITIES.md`](docs/CAPABILITIES.md) | Collection, correlation, validation, operations |
| [`docs/VALIDATION.md`](docs/VALIDATION.md) | Validation signals, confidence, relevance |
| [`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md) | High-level architecture and design goals |
| [`docs/OPERATIONS.md`](docs/OPERATIONS.md) | Safe operational model and retention |
| [`docs/LEGAL.md`](docs/LEGAL.md) | Legal bounds and use restrictions |
| [`docs/RESPONSIBLE_USE.md`](docs/RESPONSIBLE_USE.md) | Ethics, privacy, and disclosure |
| [`docs/FAQ.md`](docs/FAQ.md) | Common questions |
| [`scoring/SCORING.md`](scoring/SCORING.md) | Full capability scoring model |
| [`scoring/scorecard.json`](scoring/scorecard.json) | Machine-readable scorecard |
| [`SECURITY.md`](SECURITY.md) | Responsible disclosure |
| [`CHANGELOG.md`](CHANGELOG.md) | Public documentation changes |

---

## Limitations

StyxNet is powerful, not omniscient.

- Coverage depends on public source availability, Tor/proxy health, platform blocking, and gated content.
- Identity confirmation is evidence-based and can have false negatives.
- Private, closed, or heavily restricted material is generally out of reach.
- Speed and coverage vary heavily by target and network conditions.

---

## Links

- Platform: https://wintergate.org/styxnet/
- Organisation: https://github.com/WinterGate-IC
- Collective: https://wintergate.org

---

© 2026 WinterGate Intelligence Collective. Public documentation and capability scoring.
