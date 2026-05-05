# AGENTS Instructions

Scope: repository root and all subdirectories.

## Purpose
This repository is a **governance registry** for external AI talent candidates in the RTS ecosystem.
It is not an execution runtime.

## Guardrails
- Keep `README.md` additive and non-destructive.
- Treat all external repositories and artifacts as **candidates**, not authorities.
- Do not commit API keys, secrets, or executable integration code.
- Do not embed upstream manifests (skill/MCP/Hermes/Signal Feed/Trust Record) directly; store only references and governance metadata.

## Registry mode
Maintain records for:
- intake
- scoring
- promotion
- routing
- retirement

Do not add workflows that publish/install/mutate external systems by default.
