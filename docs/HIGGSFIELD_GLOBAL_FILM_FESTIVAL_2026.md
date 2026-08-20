# Higgsfield Global Film Festival 2026 — rules and PNyX compliance overlay

**Rules effective:** 2026-08-10  
**Repository review date:** 2026-08-20  
**Submission deadline:** 2026-09-03, 11:59 PM PT

## Authority and scope

This file is an operational mirror of the official **Higgsfield Global Film Festival — Official Rules** supplied from the dedicated Cinema Studio festival project on 2026-08-20.

The official Higgsfield rules remain authoritative. If this file conflicts with the live Festival Rules in Cinema Studio, stop and use the live official rules. Do not infer eligibility from older AAIFF documentation.

This is a **festival-specific overlay**. It does not rewrite the creative canon, historical approvals, or the separate AAIFF 2026 submission rules.

## Mandatory robot bootstrap

Before any task that may affect a Higgsfield Global Film Festival submission, every model or agent MUST:

1. read this file;
2. read the live production frontier in Issue #36 and its latest comments;
3. read `.joey/V2_9_SOURCE_LOCKS.md` and `docs/HIGGSFIELD_SUPERCOMPUTER_EDIT_HANDOFF.md`;
4. distinguish the Higgsfield Festival rules from `docs/AAIFF_2026.md`;
5. treat unresolved eligibility questions below as blockers, not as permission to proceed;
6. never submit, publish, regenerate, replace, or migrate assets merely to satisfy a rule without explicit human approval.

## Hard eligibility rules

### Entry and timing

- Participant must be a registered Higgsfield user in good standing and at least 18 years old.
- Teams may contain up to four eligible participants, with one Team Leader.
- AI video and image generations for the Entry must be created during the Generation Window: 2026-08-10 through 2026-09-03 11:59 PM PT.
- AI-generated audio may have been created before the Generation Window.
- Minimum final runtime is **3:00**. A maximum of 5:00 is recommended but not mandatory.
- Final delivery must be MP4 or MOV, 16:9 or 21:9, up to 4K.
- Any spoken language is allowed, but non-English speech requires English subtitles or English voice-over.

### Dedicated Cinema Studio festival project

- Each Entry has exactly one dedicated Cinema Studio festival project.
- **All AI-generated video and images used by the Entry must be generated inside that dedicated festival project on higgsfield.ai.**
- Generating AI video or images on another AI platform or third-party AI tool is prohibited.
- Traditional non-AI editing, compositing, grading, titles, masks, deterministic graphics, 3D and animation are allowed, provided they do not generate new AI imagery.
- All assets and generations used by the final film must remain in the festival project so Higgsfield can audit generation history.
- The final footage must match the project generation history.

### Audio

- **Every audio element must be AI-generated.** This includes dialogue, voice, lipsync, music, ambience, room tone and sound design.
- Human-recorded voice-over, live vocals, recorded acoustic instruments, human-composed music, licensed stock music and other non-AI audio are prohibited.
- AI audio may be generated outside Higgsfield and may predate the Generation Window.
- Every audio file used in the Entry must be uploaded into the festival project.
- The production must retain enough provenance to identify the AI tool used to create every audio element.

### Prohibited content

The Entry must not contain:

- protected third-party IP, characters, franchises, brands, logos, music or other protected content without authorization;
- pornographic or explicitly sexual content;
- violence against real individuals;
- political statements, endorsements, propaganda or misinformation;
- religious statements, proselytizing or disparagement;
- illegal, defamatory or rights-violating content;
- content prohibited by Higgsfield usage restrictions;
- the likeness of any identifiable real person;
- a cloned, imitated or otherwise reproduced voice of any identifiable real person.

The real-person rule applies even with consent and includes the creator, team members, family, friends, public figures, celebrities and historical figures. Festival characters and voices must be fully fictional.

Fictional AI-generated children may appear only under the restrictions in the official rules. Real identifiable children and their voices are prohibited.

### Minimal Viable Submission

Before the deadline the Entry must include:

1. the final video with the official Higgsfield watermark and packshot;
2. a valid public social-media post containing the final film with watermark and packshot intact.

The public post must be on Instagram, YouTube, X or Reddit, published from a public account, viewable without login/follow approval, and remain publicly available through the end of the Festival except for involuntary platform removal.

### Public audit and retention

- After the submission deadline, eligible submission projects become publicly viewable, including the final film, prompts, generation history and project assets.
- Higgsfield may request prompts, generation history, project files and external-audio provenance before or after judging.
- Retain requested source and provenance information for at least **24 months** after submission.

## PNyX repository compliance review — 2026-08-20

The current repository was designed around an AAIFF cut and does **not yet prove Higgsfield Festival eligibility**. The following gates apply.

| ID | Severity | Status | Finding / required action |
|---|---|---|---|
| HGF-001 | BLOCKER | unresolved | The repository records Higgsfield UUIDs, but it does not prove that every AI image/video used by v2.9 was generated inside the new dedicated Cinema Studio festival project. Obtain written Higgsfield clarification on whether existing Higgsfield generations can be migrated/associated with the festival project or whether they must be regenerated there. Do not assume that copying/uploading an asset satisfies the generation-location rule. |
| HGF-002 | BLOCKER | unresolved | Section 5 prohibits "political statements". The PNyX film explicitly depicts civic deliberation, public decisions, voting, mandates and public accountability. Obtain written Higgsfield confirmation that this fictional, non-partisan civic story is eligible before submission. Do not autonomously rewrite the film to evade the question. |
| HGF-003 | HIGH | proof required | `provenance/AI_DISCLOSURE.md` currently permits licensed performer/reference material and consent-based voice handling in the general project. The Higgsfield Festival is stricter: no identifiable real likeness or voice is allowed even with consent. Verify that every final character, reference image and voice is fully fictional and does not reproduce an identifiable real person. |
| HGF-004 | HIGH | proof required | All final audio must be AI-generated. Current approved dialogue includes Higgsfield/Gemini Omni Flash native generated audio, but the repository also contains general sound guidance mentioning field-recorded material and older ambience candidates. Build a final audio provenance manifest and exclude any human-recorded, stock, licensed or field-recorded audio. |
| HGF-005 | HIGH | pending finalization | The current v2.9 handoff is a review export and does not include the mandatory official Higgsfield watermark and packshot. Add them only at the approved final-submission stage. |
| HGF-006 | HIGH | pending submission | A public social-media post is mandatory. Create it only after final human approval and keep it public through the Festival. |
| HGF-007 | MEDIUM | active check | All Greek dialogue requires English subtitles. The handoff already specifies several subtitles, including the Phase 7 correction, but the final export requires a complete dialogue-by-dialogue subtitle audit. |
| HGF-008 | PASS | current candidates | Current reviewed cuts exceed the 3:00 minimum runtime. Runtime must be rechecked on the final export. |
| HGF-009 | PASS | current candidate format | Current review export is 16:9 MP4/H.264 at 1280x720. The Higgsfield rules allow 16:9 or 21:9 MP4/MOV up to 4K; they do not impose the AAIFF 1080p minimum. |
| HGF-010 | HIGH | proof required | All used assets must remain inside the dedicated festival project and must support an audit. Produce a deterministic final source map from every frame/audio source to its festival-project generation or external-AI-audio provenance. |
| HGF-011 | MEDIUM | final QC | Run a frame-by-frame third-party IP/logo/brand sweep before submission. PNyX-owned marks are not the same issue as unlicensed third-party protected content. |
| HGF-012 | INFO | accepted consequence | Submission makes the project, prompts, history and assets public after the deadline. Do not place secrets, credentials, private personal data or material that cannot be made public inside the festival project. |

## Repository-specific conflict notes

### `docs/AAIFF_2026.md`

This remains valid only for the separate Astana AI Film Festival target. Its deadline, upload method, 1080p expectation and hashtag requirements do not define Higgsfield Festival eligibility.

### `canon/VISUAL_SOUND_BIBLE.md`

The general sound bible allows an optional score built from field-recorded mechanical and human sounds. That option is **not eligible for the Higgsfield Festival unless the final audio itself is AI-generated in compliance with the official rules**. For the Higgsfield submission, the festival audio rule overrides this optional general-production direction.

### `provenance/AI_DISCLOSURE.md`

The general project contract allows consent/licensing for real-person references and synthetic voice authorization. That is insufficient for this Festival. For a Higgsfield Festival Entry, no identifiable real-person likeness or reproduced voice may appear even with consent.

### `docs/HIGGSFIELD_SUPERCOMPUTER_EDIT_HANDOFF.md`

The current handoff is an edit-only v2.9 Candidate contract. It is not submission authorization. Its existing native Greek audio may be used for the Festival only after the final audio provenance audit proves that each retained audio element is AI-generated and otherwise eligible.

## Questions that require written Higgsfield clarification

### Q1 — Existing Higgsfield generations

Can AI image/video generations created on Higgsfield during the Generation Window, but before or outside the dedicated Cinema Studio festival project, be moved or associated with that festival project and remain eligible? Or must every AI image/video appearing in the final Entry be regenerated from inside the dedicated festival project?

### Q2 — Civic subject matter and "political statements"

Is a fictional, non-partisan short film about ordinary residents using a fictional civic process to discuss a neighborhood playground eligible under the prohibition on "political statements" when it contains no political parties, politicians, election campaigning, endorsement, current political event, or partisan advocacy?

Until these two questions are resolved, the film may continue as a production/review Candidate, but **Festival submission eligibility remains unresolved**.

## Final Higgsfield submission gate

No model or agent may mark the film "Higgsfield Festival ready" unless all of the following are true:

- HGF-001 and HGF-002 have written resolution;
- every final image/video source is auditable to the dedicated festival project;
- every final audio element has AI-generation provenance and is uploaded into the project;
- no identifiable real-person likeness or reproduced real-person voice is present;
- no prohibited content or unlicensed protected third-party IP is present;
- all Greek dialogue has English subtitles;
- runtime is at least 3:00;
- output is MP4/MOV in 16:9 or 21:9;
- official watermark and packshot are present;
- the mandatory public social post is live and valid;
- the final asset/source map and 24-month audit-retention package are complete;
- Yiannis has explicitly approved the final cut and submission.
