# SECURITY_REVIEW

## Scope
Security review for candidate external AI talent entries.

## Minimum checks
- License and provenance visibility.
- Maintenance activity recency.
- Dependency and supply-chain warning signals.
- Data handling expectations (PII/secrets exposure risk).
- Permission model (read-only vs mutating actions).

## Explicit prohibitions for this pre-test skeleton
- No API key storage.
- No executable installation scripts.
- No auto-publish/auto-mutate workflows for external systems.

## Recording format
Document outcomes in scorecards and promotion log with:
- `confirmed_facts`
- `assumptions`
- `unverified`
- `risks`
