# pnyx.video

> **A documentary from a reality that could exist.**

`pnyx.video` is the public production workspace for cinematic stories set inside the possible civic reality of [PNyX](https://github.com/pikos-apikos/pnyx).

The first film is **«ΠΝΥΞ: Η Παιδική Χαρά»**: a speculative observational documentary about an ordinary Greek neighbourhood trying to repair a neglected playground without making anyone invisible.

PNyX is not explained as a technical platform. It is revealed through what people do: they listen, disagree, decide, execute, return and remember what actually happened.

## Current status

**Pre-production under a real deadline.** The current external target is an AAIFF 2026 submission by **15 August 2026**. The original treatment targets 11–13 minutes; the exact festival-cut runtime will be locked explicitly rather than silently shortened for the contest.

- [Read the Greek treatment](canon/TREATMENT_GR.md)
- [Read the visual and sound bible](canon/VISUAL_SOUND_BIBLE.md)
- [See the character text locks](canon/CHARACTER_TEXT_LOCKS.md)
- [AAIFF 2026 production constraints](docs/AAIFF_2026.md)
- [Follow the canonical production map](https://github.com/pikos-apikos/pnyx.video/issues/1)
- [See the current frontier](https://github.com/pikos-apikos/pnyx.video/issues/2)

Character source selections are currently being normalized and checked against text canon before any further generation continues. No finished film is being claimed here yet. Prompts and plans are not treated as completed cinematic assets.

## Joey Workflow — Cinematic Wayfinder

This production combines:

- **Wayfinder** for persistent planning: one destination, a shared issue map, named tickets, dependencies, a visible frontier and deliberate fog of war;
- **Joey's cinematic workflow** for production order: story bible → character lock → face lock → outfit → character sheet → props → environments → scene plates → video → audio and edit.

Only explicitly approved, internally consistent assets may become references for downstream work. A human selection is preserved even when it conflicts with earlier canon, but that conflict must be resolved before reuse. Rejected, superseded and invalid outputs remain traceable but never re-enter canon.

- [Workflow guide](docs/WORKFLOW.md)
- [Installable skill](skills/joey-workflow/SKILL.md)
- [References and attribution](skills/joey-workflow/REFERENCES.md)
- [Portable production-map mirror](.joey/PRODUCTION_MAP.md)

## Repository structure

- `canon/` — approved story, character and audiovisual rules
- `assets/` — asset manifest plus approved, candidate, conflicted and invalid production material
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
