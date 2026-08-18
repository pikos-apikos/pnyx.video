# Production Map — Η Παιδική Χαρά

> Portable low-resolution mirror. The authoritative live map is [GitHub Issue #1](https://github.com/pikos-apikos/pnyx.video/issues/1).

## Destination

Deliver a submission-ready **4:30 festival cut** of **«ΠΝΥΞ: Η Παιδική Χαρά»** for AAIFF 2026 by the internal deadline of **29 August 2026**, ahead of the official **31 August 2026** close.

The original 11–13 minute treatment remains the canonical full version.

## Required bootstrap

1. Read Issue #1.
2. Follow and read its current-frontier issue, including comments.
3. Read linked decision and asset-audit issues.
4. Load `skills/manifest.yaml`.
5. Apply Controlled Cinematic English before Joey specialist handoffs.

GitHub issue decisions override this mirror when they differ.

## Canon sources

- `canon/TREATMENT_GR.md`
- `canon/VISUAL_SOUND_BIBLE.md`
- `canon/CHARACTER_TEXT_LOCKS.md`
- `provenance/AI_DISCLOSURE.md`
- `skills/controlled-cinematic-english/SKILL.md`
- `skills/controlled-cinematic-english/PNYX_ADAPTER.md`
- `skills/joey-workflow/SKILL.md`
- `assets/manifest.yaml`
- `.joey/APPROVALS.md`
- `docs/PHASE_INTERTITLES_EN.md`

## Production truth

- GitHub Issues are authoritative for the live frontier and human decisions.
- Higgsfield job IDs identify source generations.
- Presence in an edit does not promote a Candidate.
- Human approval is required for every creative promotion.
- Rejected, Superseded and Invalid assets never return as references.
- Repository files mirror issue decisions and must report drift rather than infer state.

## Current frontier

### Issue #36 — Assemble the 4:30 AAIFF festival cut

- Stage: edit
- Status: in progress
- Registered rough cut: `PNYX_v2.3_final.mp4`, Candidate — revision required
- Exact post-session asset provenance: Issue #37
- Current task: produce Supercomputer rough-cut Candidate v2.4 from `docs/HIGGSFIELD_SUPERCOMPUTER_EDIT_HANDOFF.md`; no final promotion without Yiannis's review
- Approved silent prelude: `9caf49b2-3e6c-4393-b78e-ec5ba97d5afd`; place it first and remove its source audio for the full clip
- Approved phase intertitles: exact English copy and sequencing contract in `docs/PHASE_INTERTITLES_EN.md`; preserve the existing Prologue and add cards for phases 1–9 plus the Epilogue
- Approved public-consultation dialogue take: `9bd30c09-d258-44d5-84e6-e311221acd07`; exact edit out-point `00:08.662`; discard and never reuse the unrelated applause after the cut
- Approved interpretive bridge: `d09e75e3-c251-4bed-9117-83628bb6f5e5`; place its complete silent hands-on-wall shot immediately after the public-consultation cut at `00:08.662` and before **6 — THE DECISION**. Preserve emotional ambiguity; add no narration or music.
- Phase 6 departure scene: removed from the film after seven generation attempts. No departure footage or farewell dialogue enters the final edit.
- Approved Phase 7 execution sequence: `d7bc4cb6-ea2e-48e4-af51-a991ebbeb771` → spoken Anna accountability `324b5b27-02ed-464e-b8b0-7849d86ac3c7` → natural-rain material detail `2d46cc51-a100-48d1-9894-7208827186a9`.
- Supersession lock: silent Anna take `8f326641-7fd5-48f7-ae7b-f5abce997140` and earlier rain detail `2c6420fe-5eec-4a15-a9d6-7d25b0ec4236` must not enter the final edit.
- Immediate creative frontier: assemble the next rough-cut Candidate with the approved hands-on-wall bridge, revised Phase 6 intertitle and locked Phase 7 execution sequence.

## Supercomputer edit handoff

- Contract: `docs/HIGGSFIELD_SUPERCOMPUTER_EDIT_HANDOFF.md`
- Output: one review Candidate plus edit report and checksums
- Asset rule: Approved sources only; no Candidate padding; prohibited assets never return
- Human gate: Yiannis approves or revises the Candidate before finishing, upscale or export

## Binding corrections

- Eleni intake take `bade1bbd-8bf8-4993-89c9-1ec1afea4ce7` remains blocked. Its approved replacement is merged Gemini Omni Flash take `b86170f5-2de3-4038-8072-a6452991c8bf`.
- Separate listening take `c2c17ffb-3d01-4427-9400-ba6c18978c06` and reply take `18b7a08f-ea77-4614-b695-da3fba1950d7` are Superseded by the merged opening.
- Agent alternative `d9987d66-8ddc-46e8-82b6-72ebe68a26f1` is Rejected; reuse prohibited.
- Café clarification take `9acabcbf-b95b-46d1-8e61-a7c62d80db3d` remains blocked. Its approved replacement is Gemini Omni Flash take `b6617847-e663-4538-98e8-3b2ca5384f0c`, using approved plate `326c5496-c63d-4d13-9e0c-779301b29160`.
- Later coordinator variants are Rejected.
- Myrto plate `3d69fd91-b9bb-4ddc-9dd2-1a8bf3550156` and video `fa7d131d-c964-4afb-857e-b4d33528dff1` are Approved. The cut to the wet playground at approximately `6.33s` is intentional.
- The detached Greek TTS batch in Issue #37 remains Rejected. For any new human-approved Greek dialogue with visible lipsync, use Gemini Omni Flash native audio inside the same video generation.
- Exact PNyX interfaces must be composited deterministically. Generated Greek interface text remains prohibited.
- Issue #3 is Resolved and closed. Issue #2 remains open only for non-blocking legacy/canonical binary provenance maintenance.
- Silent introduction `9caf49b2-3e6c-4393-b78e-ec5ba97d5afd` is Approved. Place it before the Eleni opening with its source audio completely removed; it does not supersede the Eleni take.
- English intertitles for phases 1–9 and the Epilogue are Approved exactly as recorded in `docs/PHASE_INTERTITLES_EN.md`. Render them deterministically as 5–6 second black cards with white text; do not replace the approved Prologue.
- Phase 6 intertitle copy was revised and explicitly re-approved on 2026-08-17. The repository text in `docs/PHASE_INTERTITLES_EN.md` is authoritative.
- Public-consultation dialogue take `9bd30c09-d258-44d5-84e6-e311221acd07` is Approved with a mandatory exact cut at `00:08.662`; all later audio and video, including applause, is excluded.
- Hands-on-wall take `d09e75e3-c251-4bed-9117-83628bb6f5e5` is Approved as the interpretive bridge between the public consultation and **6 — THE DECISION**.
- The entire Phase 6 departure sequence was removed after seven generation attempts. The repository retains only the aggregate production result; individual rejected takes remain in Higgsfield and are not listed here.
- Phase 7 is locked in this order: wet paused site `d7bc4cb6-ea2e-48e4-af51-a991ebbeb771`, Anna's spoken accountability `324b5b27-02ed-464e-b8b0-7849d86ac3c7`, then rain-material detail `2d46cc51-a100-48d1-9894-7208827186a9`. The spoken take supersedes `8f326641-7fd5-48f7-ae7b-f5abce997140`; the rain remake supersedes `2c6420fe-5eec-4a15-a9d6-7d25b0ec4236`.
- Narrative correction: the clarification establishes who is affected before Myrto appears; Myrto shows the direct access failure; consequences analysis then reveals the shared-open-space loss; Thanasis gives that indirect loss a voice.
- The approved public-memory take remains the narrative ending until Yiannis approves a different ending.

## Asset map

- Approved moving-image canon and decisions: Issue #1
- Festival-cut scope: Issue #7
- Edit frontier and beta review: Issue #36
- Post-session Higgsfield image/video map: Issue #37

## Out of scope

- Turning the film into a technical PNyX explainer.
- Presenting synthetic footage as evidence of a real event.
- Promoting a Candidate without explicit human approval.
- Reusing rejected, superseded or invalid outputs.
