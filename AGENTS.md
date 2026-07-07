# AGENTS Instructions

Scope: repository root and all subdirectories.

## Required reading

Before editing, read:

1. `README.md`
2. `docs/STATUS.md`
3. `docs/NEXT.md`

## Purpose

This repository is a **frozen governance registry skeleton** for external AI talent candidates in the RTS ecosystem.

In this repository, "talent" means external AI-related candidates such as repositories, skills, MCP servers, agent profiles, or related artifacts.

It does not mean a human applicant database.

It is not an execution runtime.

It is not a recruiting CRM.

It is not a personal-data registry.

## Guardrails

- Keep `README.md` additive and non-destructive.
- Treat all external repositories and artifacts as **candidates**, not authorities.
- Do not commit API keys, secrets, credentials, private links, or executable integration code.
- Do not add human personal data.
- Do not add recruiting CRM behavior.
- Do not add scraping or surveillance workflows.
- Do not embed upstream manifests (skill/MCP/Hermes/Signal Feed/Trust Record) directly; store only references and governance metadata.
- Do not add workflows that publish, install, or mutate external systems by default.
- Do not promote candidates automatically.

## Registry mode

Maintain records only when there is a concrete governance review purpose:

- intake
- scoring
- promotion
- routing
- retirement

## Freeze boundary

Treat the next pass as freeze review and registry inventory, not expansion.

If an item contains human personal data, private links, executable integration code, authority claims, or external mutation behavior, mark it as `RISKY` and do not expand it.

If this repository is not needed for current work, leave it frozen.

## Validation

For documentation-only changes, report changed files and confirm that no human personal data, executable integration code, secrets, upstream manifest bodies, runtime behavior, recruiting CRM behavior, scraping workflow, or external system mutation was added.
