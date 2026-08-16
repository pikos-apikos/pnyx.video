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
5. [Approved English Phase Intertitles](./PHASE_INTERTITLES_EN.md).
6. [Visual and Sound Bible](../canon/VISUAL_SOUND_BIBLE.md).
7. [Disclosure Contract](../provenance/AI_DISCLOSURE.md).

When two sources differ, the latest explicit human decision in Issue #36 controls.

## Scope of this pass

This pass is an edit and deterministic-compositing pass.

- Do not generate new narrative footage. The only newly created moving-image elements authorized in this pass are the deterministic phase intertitle cards defined in `PHASE_INTERTITLES_EN.md`.
- Do not create replacement characters, voices, dialogue, interfaces, documents, music, or story beats.
- Do not upscale yet.
- Do not perform final color or audio mastering yet.
- Do not promote a Candidate asset.
- Do not reuse any Rejected, Superseded, Invalid, blocked, or technically failed asset.
- Do not use unapproved Candidate B-roll to reach a target duration.
- If approved material cannot reach 4:30 without repetition or padding, produce the strongest coherent shorter cut and report the exact duration shortfall.

## Required narrative order

Before the civic loop begins, use approved introduction video `9caf49b2-3e6c-4393-b78e-ec5ba97d5afd` as a silent prelude. Remove its source audio completely for the full clip. Do not use its audio as room tone, a transition, or an underlay. This prelude does not replace the Eleni opening.

Preserve this civic loop and its causal order:

1. Use the existing approved Prologue introduction unchanged.
2. Eleni receives the accident report and states the unresolved problem.
3. Insert Phase 1 intertitle.
4. Anna's clarification separates the observed problem from Eleni's first proposed solution. The intertitle's question of who is affected then leads to Myrto, who makes the direct access failure concrete.
5. Insert Phase 2 intertitle.
6. Evidence work exposes access, drainage, cost, uncertainty, and the less obvious loss of shared open space.
7. Insert Phase 3 intertitle, then Thanasis gives that secondary loss a voice.
8. Insert Phase 4 intertitle, then deliver the layered public briefing and dossier access.
9. Insert Phase 5 intertitle, then public consultation modifies the plan. Include approved dialogue take `9bd30c09-d258-44d5-84e6-e311221acd07` only from its start through the exact out-point `00:08.662`; exclude all later audio and video.
10. Insert Phase 6 intertitle, then show the decision outcome while preserving Thanasis's dissent. Departure render `03876795-fd20-4ae5-b94c-d4c8fa25024c` is a Candidate under review. Do not include it or a substitute unless Yiannis explicitly approves it.
11. Insert Phase 7 intertitle, then show construction meeting reality, rejected weak material, and visible accountability.
12. Insert Phase 8 intertitle, then open the playground without ceremony while preserving disagreement and defects.
13. Insert Phase 9 intertitle, then show the six-month public account and reusable public memory.
14. Insert the approved Epilogue intertitle. Do not add unapproved next-neighborhood footage.
15. Continue to the approved final statement and disclosure cards required by the canon and disclosure contract.

Do not present PNyx as magically discovering Myrto or Thanasis. The edit must show the causal path from clarification to direct impact, then from consequences analysis to indirect loss.

Do not turn the film into a technical PNyX explainer.

## Mandatory introduction

| Function | Approved Higgsfield ID | Required use |
|---|---|---|
| Silent prelude | `9caf49b2-3e6c-4393-b78e-ec5ba97d5afd` | First image of the film. Remove the source audio completely for the full clip. Then continue to the approved Eleni opening. |

## Mandatory phase intertitles

Use the exact approved copy in [`PHASE_INTERTITLES_EN.md`](./PHASE_INTERTITLES_EN.md).

- Preserve the approved Prologue video unchanged; do not create a second Prologue card.
- Create one 5–6 second card for each phase from 1 through 9 and one for the Epilogue.
- Use a static black background and white text.
- Composite text deterministically; do not use a generative model to render, translate, rewrite, or repair it.
- Preserve wording, capitalization and punctuation exactly. Adjust only line wrapping for legibility.
- Do not infer authorization for narration, dialogue, music, sound design, or new story footage from the text approvals.

## Mandatory replacement shots

Use these approved takes in place of the blocked beta material:

| Function | Approved Higgsfield ID | Required use |
|---|---|---|
| Eleni opening: parent report, pause, response | `b86170f5-2de3-4038-8072-a6452991c8bf` | Replace `bade1bbd…`, `c2c17ffb…`, and `18b7a08f…`. Preserve its native Greek audio. |
| Café clarification: Anna asks, Eleni replies | `b6617847-e663-4538-98e8-3b2ca5384f0c` | Replace `9acabcbf…` and every rejected coordinator reverse angle. Preserve its native Greek audio. |
| Myrto interview and wet-playground consequence | `fa7d131d-c964-4afb-857e-b4d33528dff1` | Preserve the intentional cut at approximately 6.33 seconds. Preserve its native Greek audio. |
| Public-consultation dialogue exchange | `9bd30c09-d258-44d5-84e6-e311221acd07` | Use only through exact out-point `00:08.662`. Preserve native Greek audio before the cut. Exclude and never reuse the unrelated applause after the cut. |

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
- every detached Greek TTS asset listed as Rejected in Issue #37; this prohibition applies to that batch, not to Gemini Omni Flash native-audio video generation
- the public-memory photo insert `8f8c8b9c-66cc-4fca-a9fb-77d7bb63fa5c`
- the next-neighbourhood coda `43f4a3c7-dfdc-4576-8cfe-113b9b6564d3`

Treat all other post-frontier videos in Issue #37 as unapproved Candidates. Do not include them in this pass.

## Greek speech-generation rule

For any new spoken-Greek shot that Yiannis explicitly authorizes:

- use **Gemini Omni Flash**;
- generate the Greek voice and visible lipsync together as native audio inside the same video render;
- do not generate a detached TTS file and apply post-hoc lipsync;
- do not reuse the rejected detached Greek TTS batch from Issue #37.

This rule defines the approved method. It does not authorize new footage or new dialogue in this edit pass.

## Dialogue and subtitles

Preserve native Greek audio from the approved dialogue takes. Do not replace these approved native-audio tracks. For `9bd30c09-d258-44d5-84e6-e311221acd07`, preserve audio only through `00:08.662` and exclude everything after that point.

Embed concise English subtitles for the spoken lines:

- Off-screen parent: “A child fell again where the surface has lifted.”
- Eleni: “I don't know exactly what needs to be done. I know it can't stay like this.”
- Anna: “What exactly is the problem?”
- Eleni: “A new playground.”
- Myrto: “To be able to get in after the rain.”
- Thanasis: “Do not close the entire space at once.”
- Eleni: “But then it will take longer.”
- Myrto: “And where will the young children play?”

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
- Exception: the approved introduction `9caf49b2-3e6c-4393-b78e-ec5ba97d5afd` must remain completely silent; remove its entire source track.
- No inspirational piano.
- No new score in this pass unless an already approved music asset exists.
- Preserve the original room tone around native dialogue.
- Use clean transitions and restrained cuts. Do not use promotional transitions or fast techno montage.

## Ending

Use approved public-memory take `9ea93421-b936-4543-86b4-a09891ac9909` for Phase 9.

After it, insert the approved **EPILOGUE — THE NEXT NEIGHBORHOOD** intertitle from `PHASE_INTERTITLES_EN.md`. Do not place unapproved next-neighborhood Candidate footage after the card; in particular, `43f4a3c7-dfdc-4576-8cfe-113b9b6564d3` remains prohibited.

Then add the approved final statement and an end card that reproduces the required disclosure from `provenance/AI_DISCLOSURE.md` exactly:

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
   - confirm that the introduction source audio was removed for the full clip;
   - source in/out timecodes;
   - final duration;
   - every deterministic composite, including exact intertitle in/out timecodes;
   - confirmation that every intertitle matches `PHASE_INTERTITLES_EN.md` exactly;
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
