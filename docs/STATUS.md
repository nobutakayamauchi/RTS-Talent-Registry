# RTS-Talent-Registry Status

Status: FREEZE / GOVERNANCE-REGISTRY / REVIEW BEFORE USE

RTS-Talent-Registry is a governance registry skeleton for external AI talent candidates in the RTS ecosystem.

In this repository, "talent" means external AI-related candidates such as repositories, skills, MCP servers, agent profiles, or related artifacts.

It does not mean a human applicant database.

It is not RTS core.

It is not RTS-AGE.

It is not an execution runtime.

It is not a recruiting CRM.

It is not a personal-data registry.

It is not a source of authority for upstream projects.

## Current Position

This repository should remain frozen unless there is a concrete governance review task.

The current skeleton may be useful as a reference for intake, scoring, promotion, routing, and retirement of external AI-related candidates.

However, it should not become active operational infrastructure by default.

Allowed by default:

- clarify governance boundaries
- document registry review rules
- improve safety and privacy notes
- record references to external candidates when public-safe and reviewed
- classify existing registry records as draft, stale, risky, or archive candidates
- preserve the repository as a governance skeleton

Prohibited by default:

- adding personal data about humans
- adding recruiting CRM behavior
- adding scraping or surveillance workflows
- adding executable integration code
- adding publishing, installing, or mutation workflows for external systems
- adding API keys, secrets, credentials, or private links
- embedding upstream manifests directly
- treating external candidates as authorities without review
- promoting candidates automatically
- turning this repository into RTS core, RTS-AGE, or runtime infrastructure

## Boundary

RTS defines canonical protocol and reconstructability rules.

RTS-AGE may prepare implementation artifacts.

RTS-Skills, RTS-MCP-Packs, RTS-Hermes-Drive, and related component repositories hold their own component definitions.

RTS-Talent-Registry should only hold reviewed governance metadata about external AI-related candidates.

It should not absorb upstream manifests, runtime behavior, or operational control of external systems.

## Freeze Definition

This repository is considered safely frozen when:

1. Its governance-registry role is explicit.
2. Human personal data is excluded.
3. External candidates are treated as candidates, not authorities.
4. Runtime, publishing, installation, and mutation behavior are prohibited by default.
5. Future edits require a concrete governance review purpose.

## Current Decision

Keep this repository frozen.

Treat it as a governance registry skeleton and archive-adjacent reference.

Do not expand it into live talent operations, recruiting, scraping, runtime execution, or external system mutation without a separate decision record.
