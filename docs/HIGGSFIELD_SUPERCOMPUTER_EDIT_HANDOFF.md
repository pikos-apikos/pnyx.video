# Higgsfield Supercomputer Edit Handoff — Candidate v2.4

## Objective

Create one new rough-cut Candidate of **«ΠΝΥΞ: Η Παιδική Χαρά»** from the existing Higgsfield and GitHub production record.

The output is a review Candidate. It is not a final master and it does not become canonical without Yiannis's explicit approval.

## Authority order

Read these sources before editing:

1. [Issue #36 — edit frontier](https://github.com/pikos-apikos/pnyx.video/issues/36), including its latest comments.
2. [Asset manifest](../assets/manifest.yaml). Use manifest v25 or later.
3. [Issue #37 — post-session provenance audit](https://github.com/pikos-apikos/pnyx.video/issues/37).
4. [Issue #7 — approved 4:30 story spine](https://github.com/pikos-apikos/pnyx.video/issues/7).
5. [Visual and Sound Bible](../canon/VISUAL_SOUND_BIBLE.md).
6. [Disclosure Contract](../provenance/AI_DISCLOSURE.md).

When two sources differ, the latest explicit human decision in Issue #36 controls.

## Scope of this pass

This pass is an edit and deterministic-compositing pass.

- Do not generate new footage.
- Do not create replacement characters, voices, dialogue, interfaces, documents, music, or story beats.
- Do not upscale yet.
- Do not perform final color or audio mastering yet.
- Do not promote a Candidate asset.
- Do not reuse any Rejected, Superseded, Invalid, blocked, or technically failed asset.
- Do not use unapproved Candidate B-roll to reach a target duration.
- If approved material cannot reach 4:30 without repetition or padding, produce the strongest coherent shorter cut and report the exact duration shortfall.

## Required narrative order

Preserve this civic loop:

1. Eleni receives the accident report and states the unresolved problem.
2. Myrto makes the access requirement concrete.
3. Anna's clarification separates the observed problem from Eleni's first proposed solution.
4. Evidence work exposes access, drainage, cost, and uncertainty.
5. Eleni receives confirmation that the dossier is open.
6. Thanasis makes the cost to older residents visible.
7. Public briefing and consultation modify the plan.
8. The amended proposal is approved while Thanasis's dissent remains public.
9. Construction meets reality; weak material is rejected and accountability remains visible.
10. The playground opens without ceremony; the record carries the learning forward.

Do not turn the film into a technical PNyX explainer.

## Mandatory replacement shots

Use these approved takes in place of the blocked beta material:

| Function | Approved Higgsfield ID | Required use |
|---|---|---|
| Eleni opening: parent report, pause, response | `b86170f5-2de3-4038-8072-a6452991c8bf` | Replace `bade1bbd…`, `c2c17ffb…`, and `18b7a08f…`. Preserve its native Greek audio. |
| Café clarification: Anna asks, Eleni replies | `b6617847-e663-4538-98e8-3b2ca5384f0c` | Replace `9acabcbf…` and every rejected coordinator reverse angle. Preserve its native Greek audio. |
| Myrto interview and wet-playground consequence | `fa7d131d-c964-4afb-857e-b4d33528dff1` | Preserve the intentional cut at approximately 6.33 seconds. Preserve its native Greek audio. |

## Approved moving-image sources

Use the following sources when the corresponding beat is required:

| Beat | Approved Higgsfield ID |
|---|---|
| Gate entry / Take B | Exact take UUID remains pending. Resolve it from Higgsfield history and Issue #8. Do not invent an ID or substitute another take. |
| Evidence room | `d4fff9fe-e12c-4299-9bbb-8a88c8621d68` |
| Anna prints dossier | `e7c733a6-9f24-4184-84c2-ea6c11638304` |
| Eleni receives dossier-open notification | `8b32c5e0-307a-42d1-a594-af9625fbfdbc` |
| Thanasis human-cost beat | `bd5b052f-fa59-4392-9003-3ac8221c67db` |
| Public consultation | `15940a3a-0f92-41c8-8e5c-0059e7562308` |
| Amended proposal decision | `d17054a7-3257-42f3-b676-d4c42cb0aab8` |
| Rain blocks access | `d7bc4cb6-ea2e-48e4-af51-a991ebbeb771` |
| Weak material rejected | `3726b60c-f0a5-49b3-bea5-baa9018f768a` |
| Deadline accountability | `8f326641-7fd5-48f7-ae7b-f5abce997140` |
| Myrto enters completed playground | `09596bc2-5f1f-461f-abdf-694beb2bd8ae` |
| Post-rain accountability | `bec2e4f1-a384-4572-941c-d8afc7385b1e` |
| Six-month public-memory ending | `9ea93421-b936-4543-86b4-a09891ac9909` |

Use the repository manifest and issues to verify status before using every source. If a listed source is unavailable, report it as missing. Do not replace it automatically.

## Prohibited sources

At minimum, exclude:

- `bade1bbd-8bf8-4993-89c9-1ec1afea4ce7`
- `9acabcbf-b95b-46d1-8e61-a7c62d80db3d`
- `18b7a08f-ea77-4614-b695-da3fba1950d7`
- `c2c17ffb-3d01-4427-9400-ba6c18978c06`
- `d9987d66-8ddc-46e8-82b6-72ebe68a26f1`
- `80312fb1-96fe-42ca-b69d-ef79184d1267`
- `a6906941-0177-4546-9558-ce285150ce63`
- `5e45dbe7-93cb-4d36-8979-8ad81744077d`
- every Greek TTS asset listed as Rejected in Issue #37
- the public-memory photo insert `8f8c8b9c-66cc-4fca-a9fb-77d7bb63fa5c`
- the next-neighbourhood coda `43f4a3c7-dfdc-4576-8cfe-113b9b6564d3`

Treat all other post-frontier videos in Issue #37 as unapproved Candidates. Do not include them in this pass.

## Dialogue and subtitles

Preserve native Greek audio from the three approved dialogue takes. Do not replace it with TTS.

Embed concise English subtitles for the spoken lines:

- Off-screen parent: “A child fell again where the surface has lifted.”
- Eleni: “I don't know exactly what needs to be done. I know it can't stay like this.”
- Anna: “What exactly is the problem?”
- Eleni: “A new playground.”
- Myrto: “To be able to get in after the rain.”

Do not add narration or additional dialogue. Preserve silence after difficult statements.

## Deterministic interface compositing

Do not ask a generative model to recreate Greek text.

- Composite the approved dossier interface `b8c562bf-07ca-4217-8f89-23449d0d4a43` into the Anna dossier scene where required.
- Composite the approved notification interface `82589152-e17d-4b96-af37-32652bbf760b` into the Eleni notification scene.
- Preserve the exact approved Greek copy recorded in Issue #12.
- Keep interfaces quiet, legible, and physically attached to the existing screens.
- Do not add floating UI, holograms, voice-command interaction, or new data.

## Image and sound treatment

Follow the Visual and Sound Bible:

- 24 fps.
- Observational documentary rhythm.
- Fine 35mm grain and restrained halation.
- Natural Greek daylight and open shadow detail.
- No glossy advertising grade.
- Diegetic sound leads.
- No inspirational piano.
- No new score in this pass unless an already approved music asset exists.
- Preserve the original room tone around native dialogue.
- Use clean transitions and restrained cuts. Do not use promotional transitions or fast techno montage.

## Ending

End the narrative with approved public-memory take `9ea93421-b936-4543-86b4-a09891ac9909`.

Do not place unapproved Candidate footage after it.

Add an end card that reproduces the required disclosure from `provenance/AI_DISCLOSURE.md` exactly:

> Η ταινία είναι έργο speculative documentary. Οι χαρακτήρες και τα γεγονότα είναι μυθοπλαστικές συνθέσεις. Απεικονίζει μία πιθανή δημόσια πραγματικότητα και όχι υπαρκτή διοικητική διαδικασία ή καταγεγραμμένο γεγονός.

Do not invent contributor names or production claims. Use only verified repository provenance.

## Review export

Create:

1. `PNYX_v2.4_supercomputer_candidate.mp4`
   - H.264
   - 1280×720
   - 24 fps
   - AAC stereo, 48 kHz
   - no final upscale
2. `PNYX_v2.4_edit_report.md`
   - exact source IDs in timeline order;
   - source in/out timecodes;
   - final duration;
   - every deterministic composite;
   - subtitle text and timing;
   - missing approved assets;
   - duration shortfall from 4:30;
   - any deviation from this handoff.
3. `PNYX_v2.4_checksums.txt`
   - SHA-256 for every delivered file.

## Human gate

Stop after producing the Candidate and report.

Do not:

- declare the cut final;
- approve the edit;
- upscale it;
- publish it;
- submit it to AAIFF;
- alter the repository;
- generate replacement footage.

Yiannis retains the decisions about edit order, trims, pacing, sound, subtitles, disclosure presentation, and the final master.
