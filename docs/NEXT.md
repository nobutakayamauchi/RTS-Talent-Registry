# RTS-Talent-Registry Next Actions

The next goal is freeze review, not expansion.

## Next Tasks

1. Confirm whether existing registry records are still useful.
2. Classify each registry item as ready, draft, stale, duplicate, risky, move, or archive.
3. Confirm that no human personal data is present.
4. Confirm that no secrets, credentials, private links, or executable integration code are present.
5. Confirm that external candidates are described as candidates, not authorities.
6. Confirm that upstream manifests are referenced only and not embedded directly.
7. Decide whether the repository should remain frozen, be archived, or receive a narrow governance-review update.

## Suggested Follow-up Files

```text
docs/inventory/registry_inventory.md
docs/governance/privacy_boundary.md
docs/governance/external_candidate_contract.md
```

## Inventory Categories

Use these labels during the next pass:

- READY: safe as governance metadata
- DRAFT: useful but incomplete
- STALE: likely outdated or superseded
- DUPLICATE: overlaps another registry record
- RISKY: personal data, authority claim, runtime behavior, or external mutation risk needs review
- MOVE: belongs in another repository
- ARCHIVE: preserve for history only

## Registry Review Checklist

Each registry item should explicitly describe:

- name
- path
- candidate type
- public source or reference
- governance purpose
- status label
- authority boundary
- privacy risk
- runtime or mutation risk
- next smallest safe action

If an item contains human personal data, private links, executable integration code, authority claims, or external mutation behavior, mark it as `RISKY` and do not expand it until reviewed.

## Do Not Do Yet

Do not:

- add human personal data
- add recruiting CRM behavior
- add scraping or surveillance workflows
- add executable integration code
- add API keys, tokens, secrets, credentials, or private links
- embed upstream manifests directly
- promote candidates automatically
- publish, install, or mutate external systems
- rewrite all registry records at once

## Next Recommended Task

Create `docs/inventory/registry_inventory.md` only if this repository is intentionally reviewed again.

That file should list each known registry record with:

1. name
2. path
3. candidate type
4. status label
5. public source or reference
6. privacy risk
7. authority risk
8. runtime or mutation risk
9. next smallest safe action
