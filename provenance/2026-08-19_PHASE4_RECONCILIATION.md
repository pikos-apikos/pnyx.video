# Phase 4 reconciliation — 2026-08-19

## Purpose

Record the deterministic recovery of three human-confirmed PNyX Phase 4 beats that existed in Higgsfield/edit history but were omitted from the repository source locks and therefore disappeared from the v2.6 Supercomputer handoff.

This file is a provenance repair. It does not promote unrelated August 16 generations.

## Root cause

The v2.5 human review identified old overlay-looking footage in the **first two shots** of Phase 4 and requested those shots be corrected.

The subsequent v2.6 handoff converted that local correction into an `exact order` containing only:

1. `e0b9d85a-3f0f-4bfb-9d51-ab18187d4b4f`
2. `d4fff9fe-e12c-4299-9bbb-8a88c8621d68`
3. `d99323a3-56c4-41a9-ac75-2ba437046201`

That unintentionally treated the corrected opening as the complete Phase 4 sequence and truncated three later recipient beats.

The missing beats had also never been deterministically backfilled into the GitHub manifest/handoff. Their production state existed only in Higgsfield/edit history, so the Supercomputer had no repository source lock requiring their preservation.

## Human-confirmed restored beats

### Eleni — break-room update

- Higgsfield video: `c6cd0e00-6bad-4fa8-96e6-f1128e455e28`
- Model: Gemini Omni Flash (`gemini_omni`)
- Duration: 8 s
- Format: 1280×720, 16:9
- Source plate: `2118ebfa-16fe-4a4e-b700-bf8a243e7158`
- Additional reference: `82589152-e17d-4b96-af37-32652bbf760b`
- Exact Greek speech: «Ξεκίνησε»
- Edit role: Phase 4 recipient beat after the technical/evidence sequence.
- Supersedes for this beat: silent `aa1f944d-ed8e-4390-a6ca-55ce1f1c13a6`.

### Thanasis — receives public briefing

- Higgsfield video: `114f44f7-4626-4369-8627-2a3ce6cc6c97`
- Model: Gemini Omni Flash (`gemini_omni`)
- Duration: 6 s
- Format: 1280×720, 16:9
- Source plate: `afb18356-d12b-4595-8439-314b1ea178c1`
- Audio: silent
- Edit role: Phase 4 recipient beat; Thanasis receives the printed public briefing, reads the first page briefly and moves away carrying it.
- Supersedes for this beat: older `39bf970f-aa27-4d2d-b165-1f6005e09149`.

### Myrto — access route recognized

- Higgsfield video: `ac4a9414-da71-4abc-ad56-b9297fd568d9`
- Model: Gemini Omni Flash (`gemini_omni`)
- Duration: 6 s
- Format: 1280×720, 16:9
- Source plate: `b9f0806c-4739-4f29-ac5f-458e1654913a`
- Additional reference media: `6f4db435-1f66-448d-9d92-027ef715c9ad`
- Exact Greek speech: «Με σκέφτηκαν»
- Edit role: Phase 4 recipient beat; Myrto traces the access route and recognizes that her requirement has been considered.
- Supersedes for this beat: silent `d48db3f1-7de9-45c6-8804-04040cf9ebf4`.

## Correct Phase 4 source lock

The complete Phase 4 sequence is:

1. `e0b9d85a-3f0f-4bfb-9d51-ab18187d4b4f`
2. `d4fff9fe-e12c-4299-9bbb-8a88c8621d68`
3. `d99323a3-56c4-41a9-ac75-2ba437046201`
4. `c6cd0e00-6bad-4fa8-96e6-f1128e455e28`
5. `114f44f7-4626-4369-8627-2a3ce6cc6c97`
6. `ac4a9414-da71-4abc-ad56-b9297fd568d9`

The correction of an earlier shot in a phase must never implicitly delete later approved timeline beats.

## Prelude timing amendment recorded in the same repair session

Human decision on 2026-08-19:

- Approved introduction: `9caf49b2-3e6c-4393-b78e-ec5ba97d5afd`.
- Playback speed: **0.6×**.
- Reason: large English text blocks switch too quickly for comfortable reading, especially for non-native English viewers; there is effectively no meaningful motion that needs real-time preservation.
- Preserve visual content exactly and keep the prelude silent.
- This timing amendment supersedes the earlier `unchanged` constraint and any working `0.85×` suggestion.

## Audit boundary

Other August 16 Higgsfield generations were reviewed only for reconciliation. No unrelated Candidate is promoted by this repair without explicit human approval evidence.

`DECISION OWNER: HUMAN`.