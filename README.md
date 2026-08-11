# pnyx.video

> **A documentary from a reality that could exist.**

`pnyx.video` is the public production workspace for cinematic stories set inside the possible civic reality of [PNyX](https://github.com/pikos-apikos/pnyx).

The first film is **«ΠΝΥΞ: Η Παιδική Χαρά»**: a speculative observational documentary about an ordinary Greek neighbourhood trying to repair a neglected playground without making anyone invisible.

PNyX is not explained as a technical platform. It is revealed through what people do: they listen, disagree, decide, execute, return and remember what actually happened.

## Current status

**Production in progress under a real deadline.** AAIFF 2026 submissions close on **31 August 2026**. The internal safe-submission target is **29 August**, leaving two contingency days.

Yiannis approved a coherent **4:30 festival cut**. The original 11–13 minute treatment remains the canonical full version; it has not been silently replaced.

- [Read the Greek treatment](canon/TREATMENT_GR.md)
- [Read the visual and sound bible](canon/VISUAL_SOUND_BIBLE.md)
- [See the character text locks](canon/CHARACTER_TEXT_LOCKS.md)
- [AAIFF 2026 production constraints](docs/AAIFF_2026.md)
- [Follow the authoritative production map](https://github.com/pikos-apikos/pnyx.video/issues/1)
- [Review the current frontier](https://github.com/pikos-apikos/pnyx.video/issues/18)

Seven moving-image beats are currently approved through `07_THANASIS_HUMAN_COST`. The approved public-consultation scene plate is complete. The current human frontier is the retry take in [Issue #18](https://github.com/pikos-apikos/pnyx.video/issues/18), Higgsfield `215185dd-23f6-4762-a590-83be9599067b`; it remains a **Candidate**, not canon.

## Canonical visual assets

Approved still references are stored in the repository with dimensions and SHA-256 provenance in [`assets/manifest.yaml`](assets/manifest.yaml).

| Asset | Repository file | Higgsfield job |
|---|---|---|
| `02_GATE_ENTRY` plate B | [`plate-b.png`](assets/scenes/02-gate-entry/plate-b.png) | `b622e62a-6f2c-41d9-be30-3c54ea14d6f8` |
| PNyX dossier interface | [`v1.png`](assets/interfaces/pnyx-dossier/v1.png) | `b8c562bf-07ca-4217-8f89-23449d0d4a43` |
| Anna prints dossier plate | [`plate-b.png`](assets/scenes/05-anna-prints-dossier/plate-b.png) | `e6a118cf-947d-4e66-bbcd-53bc391ff377` |
| Eleni notification interface | [`v1.png`](assets/interfaces/eleni-notification/v1.png) | `82589152-e17d-4b96-af37-32652bbf760b` |
| Eleni clean motion plate | [`clean-motion-plate.png`](assets/scenes/06-eleni-notification/clean-motion-plate.png) | `c03bfaa1-02a4-4708-a551-3b6cbe9fef7f` |
| Thanasis character sheet | [`character-sheet.png`](assets/characters/thanasis/character-sheet.png) | `e43d88e4-0938-42ba-914a-c2b076f1aa20` |
| Thanasis low-wall plate B | [`plate-b.png`](assets/scenes/07-thanasis-human-cost/plate-b.png) | `97e4a7bf-e917-4ba0-b943-c49aa8e830ed` |
| Public-deliberation courtyard B | [`courtyard-b.png`](assets/environments/public-deliberation/courtyard-b.png) | `f13ab72d-94dc-4332-9b99-c55800759f14` |
| Public-consultation plate B | [`plate-b.png`](assets/scenes/08-public-consultation/plate-b.png) | `ee8ecaa1-3261-413c-b868-e850aae0116d` |

Video masters remain in Higgsfield and are registered by exact job ID in the manifest and approval log. They are not duplicated as heavy binaries in GitHub.

## Joey Workflow — Cinematic Wayfinder

This production combines:

- **Wayfinder** for persistent planning: one destination, a shared issue map, named tickets, dependencies, a visible frontier and deliberate fog of war;
- **Joey's cinematic workflow** for production order: story bible → character lock → face lock → outfit → character sheet → props → environments → scene plates → video → audio and edit.

Only explicitly approved, internally consistent assets may become references for downstream work. A human selection is preserved even when it conflicts with earlier canon, but that conflict must be resolved before reuse. Rejected, superseded and invalid outputs remain traceable but never re-enter canon.

- [Workflow guide](docs/WORKFLOW.md)
- [Installable skill](skills/joey-workflow/SKILL.md)
- [References and attribution](skills/joey-workflow/REFERENCES.md)
- [Portable production-map mirror](.joey/PRODUCTION_MAP.md)
- [Human approval log](.joey/APPROVALS.md)

## Repository structure

- `canon/` — approved story, character and audiovisual rules
- `assets/` — manifest plus imported canonical stills, candidates and failure history
- `provenance/` — AI disclosure, source and release-integrity rules
- `skills/joey-workflow/` — the project-pinned orchestration skill
- `.joey/` — portable mirror of production state; GitHub Issues remain authoritative

## Synthetic-media disclosure

This is **speculative documentary**, not archival reporting.

The characters and events are fictional composites. The film depicts a possible public reality, not an existing municipal process or a recorded historical event. Generated footage must never be presented as evidence that the depicted people, vote, project or institution actually existed.

See the full [provenance and disclosure contract](provenance/AI_DISCLOSURE.md).

## Public review

Focused review is welcome where it targets a specific artifact, assumption, continuity rule, provenance claim or workflow decision. The production map deliberately avoids open-ended generation: one clear frontier item is handled at a time.

See [CONTRIBUTING.md](CONTRIBUTING.md) before opening an issue or submitting material.

## Licensing

No project-wide reuse license has been declared yet. Public visibility should not be interpreted as permission to reuse production assets. Upstream projects and referenced materials retain their own licenses and terms.

