# Validation

StyxNet uses page-level evidence rather than HTTP status alone.

## Linkage signals

- Page metadata and canonical URL
- Redirects
- Structured data and embedded JSON
- JSON-LD and microdata
- Author metadata and author links
- JavaScript state
- Entity/user activity linked to the handle

## Result states

- **Confirmed** — strong page-level linkage
- **Linkage-confirmed** — strong trace with limited corroboration
- **Unverified** — weak, missing, or rejected evidence

Confirmed results are prioritised. Unverified profile-like results are demoted. Ordinary articles are not falsely labelled.

## Content findings

Marketplace, phishing, and similar content findings receive a separate relevance pass. A finding is kept only when its own visible page evidence supports the classification, not site-wide boilerplate.

## Retention

Unverified, junk, legacy, and irrelevant records move to quarantine. Quarantined intelligence is retained for review for three days and then permanently deleted.

## What confirmation means

Confirmation means evidence linkage. It does not mean legal ownership, absolute identity, or universal truth.
