# Phase 6 — Decision Departure

Authority: Yiannis's explicit approvals and corrections on 2026-08-17.

## Current status

- Stage: video / audio / edit
- Approved story action: the decision has been made; residents leave quietly; the camera position, framing and focus remain fixed.
- Approved exit direction: every resident leaves through screen-left.
- Approved Eleni action: Eleni stays at the table, gathers the existing papers into a neat stack, and leaves screen-left last after every other resident is gone.
- Approved dialogue:
  - Thanasis: «Καλή επιτυχία στο έργο. Καλή σας νύχτα!»
  - Several different residents: «Καληνύχτα.»
  - Eleni, last: «Σας ευχαριστούμε, καλό βράδυ.»
- Performance lock: Thanasis is gentle, humble, sincere and respectful toward his neighbors.
- Camera lock: fixed camera, fixed framing, fixed focus; no reframing or camera move.
- Valid rendered Candidate: **none**.
- Current frontier: review the first prompt of a proposed two-plate Higgsfield workflow. No new generation is authorized until Yiannis approves each prompt.
- Decision owner: Yiannis.

## Canonical visual reference

User-supplied image `Screenshot 2026-08-17 at 00.46.49.png`, uploaded to Higgsfield as media `39fd39f2-602f-4d3e-8c0a-cf302a31b0b7`.

Dimensions: 2048×1140.  
SHA-256: `4654c3125730e2bf3ccb95f5191c2e995c90903197f5bf9a8fcfc06a75be9b9c`.

Gemini Omni Flash adapted the requested image/start-image role to `image_references`, so the reference was not a pixel-identical hard first-frame lock.

## Acceptance gate

A Phase 6 departure Candidate is reviewable only if:

- visible movement begins immediately;
- every resident moves toward and exits through screen-left;
- nobody walks into the wall, exits right, approaches Eleni, stops for a handshake, or forms a farewell group;
- no character is duplicated, merged, replaced, or materially changed;
- Thanasis appears only once;
- Myrto moves screen-left with the departing residents and does not speak;
- Eleni remains continuously identifiable in the same dark navy top and dark trousers;
- Eleni remains at the table, gathers only the existing papers, and does not depart early;
- every other resident is completely outside the frame before Eleni begins her exit;
- Eleni carries the paper stack and exits screen-left as the last person;
- the camera position, framing and focus remain fixed;
- the exact approved Greek dialogue is preserved with several distinct resident voices;
- there is no applause, cheering, music, narration or extra dialogue.

## Revised production strategy — awaiting prompt approval

The one-pass Gemini Omni approach is rejected for this crowd choreography. The proposed recovery separates the work into:

1. **Departure plate:** residents leave screen-left while Eleni stays at the table.
2. **Eleni plate:** the courtyard is already empty; Eleni finishes gathering the papers, gives the last reply, and exits screen-left.
3. **Controlled audio pass:** assemble the approved Greek dialogue separately so the motion generation is not also responsible for five or more synchronized voices.

The two visual plates must use the same locked composition and be joined with a concealed cut motivated by leftward foreground movement. This strategy is a proposal, not approved canon.

## Render history

### V1 — Rejected

- Job: `03876795-fd20-4ae5-b94c-d4c8fa25024c`
- Reason: delayed movement; inconsistent exit direction; unrequested handshake; insufficient non-protagonist «Καληνύχτα» replies.
- Reuse: prohibited.

### V2 — Rejected

- Job: `930d22c6-261d-4696-804e-cca53d78ed25`
- Technical: 10.005 s, 1280×720, 24 fps, H.264, AAC stereo 48 kHz.
- Size: 2,504,183 bytes.
- SHA-256: `15899a46fd99122a8c628a6f1b04d73c93a42912eb938ce588977c13ce9a0cc9`.
- Reason: the later-approved action was missing; Eleni did not remain to gather the papers and leave last.
- Reuse: prohibited.

### V3 — Rejected

- Job: `739b6033-376b-468a-a97f-137884b5da65`
- Technical: 10.005 s, 1280×720, 24 fps, H.264, AAC stereo 48 kHz.
- Size: 2,495,309 bytes.
- SHA-256: `ddd8f4f947f3f42344ba9917c0aede264b0fe770fd5f48c751b20a890e6ab513`.
- Reason: Eleni gathered papers but began leaving while several residents were still visible behind her; she was not last.
- Reuse: prohibited.

### V4 — Rejected

- Job: `f7133cce-95b6-4509-b3b0-954794c228a0`
- Technical: 10.005 s, 1280×720, 24 fps, H.264, AAC stereo 48 kHz.
- Size: 2,358,898 bytes.
- SHA-256: `564648b5e020cf5e8ddafe07fe34e4e6cc681f2b9670e7bf895d903a3deeaaca`.
- Reason: after approximately 7 seconds, Eleni's dark clothing and identity drifted into a different light-clothed woman; the required character continuity failed.
- Reuse: prohibited.

### V5 — Rejected

- Job: `f63e21aa-24b7-4b9b-8acb-d9c9bc639eea`
- Technical: 10.005 s, 1280×720, 24 fps, H.264, AAC stereo 48 kHz.
- Size: 2,388,071 bytes.
- SHA-256: `312d5f40f2af8f907eca6c7e2df52a423bbea0b4cfddc7c785a9c2a34dd700ef`.
- Reason: residents did not consistently move screen-left; Thanasis was duplicated; people crossed into the wall; one resident remained seated at the right through the end, so Eleni was not last.
- Reuse: prohibited.
