# Phase 6 — Decision Departure Prompt

Authority: Yiannis's explicit approvals and correction on 2026-08-17.

## Current status

- Stage: video
- Prompt revision: **V2 Approved**
- Render state: **Candidate — human review required**
- Current Candidate: `930d22c6-261d-4696-804e-cca53d78ed25`
- Candidate URL: https://d8j0ntlcm91z4.cloudfront.net/user_3HbuSFrdCd0fV7j1hf3vlHB7UpQ/hf_20260816_215407_930d22c6-261d-4696-804e-cca53d78ed25.mp4
- Decision owner: Yiannis
- Model: Gemini Omni Flash
- Duration: 10 seconds
- Output target: 16:9, 720p
- Native audio and visible lipsync are generated together.
- The Candidate cannot enter the canonical edit without Yiannis's explicit approval.

## Canonical visual reference

User-supplied image `Screenshot 2026-08-17 at 00.46.49.png`, uploaded to Higgsfield as media `39fd39f2-602f-4d3e-8c0a-cf302a31b0b7`.

Higgsfield adapted the requested `start_image` role to Gemini Omni Flash `image_references`. The image guides visual continuity but is not a pixel-identical hard first-frame lock.

## Approved V2 prompt

Use the supplied courtyard image as the visual continuity reference for one continuous ten-second restrained observational-documentary take.

ACTION MUST BEGIN IMMEDIATELY. From the first visible moment, residents are already standing up, turning, moving chairs aside, and walking away. Do not begin with a still tableau, a pause, waiting, listening, or a new speech at the microphone.

EXIT DIRECTION LOCK: every person moves consistently toward SCREEN-LEFT and leaves through the left side of the image. No person exits toward screen-right, toward the camera, or deeper into the center. Thanasis, Eleni, Myrto in her wheelchair, and all surrounding residents share the same screen-left departure direction. People may leave at slightly different speeds, but the whole crowd flow is clearly leftward from the beginning to the end.

The camera remains completely locked in the supplied position and framing. Keep focus and depth of field unchanged. No pan, tilt, zoom, reframing, camera movement, focus pull, or cut.

Speaker identity lock:
- THANASIS is the elderly white-haired man with the white moustache, checked short-sleeve shirt, dark trousers, and watch, near the center of the supplied image.
- ELENI is the standing woman beside the table and microphone in the left-center.
- MYRTO is the young woman in the wheelchair at the right foreground.
- OTHER RESIDENTS are the surrounding neighbors.

All speech is natural Greek. Do not translate. Everyone speaks while already moving screen-left. No one stops, turns back, approaches another person, shakes hands, embraces, gathers around the table, or creates a farewell ceremony.

Dialogue order:

1. While already walking screen-left with the departing group, THANASIS says once:
“Καλή επιτυχία στο έργο. Καλή σας νύχτα!”

Thanasis speaks gently, humbly, sincerely, and respectfully. No sarcasm, bitterness, resentment, triumph, or theatrical emphasis. He does not approach Eleni. The camera does not isolate him.

2. Several different departing RESIDENTS — beyond Thanasis, Eleni, and Myrto — answer naturally from different positions while continuing to move screen-left. At least four distinct ordinary residents say:
“Καληνύχτα.”
“Καληνύχτα.”
“Καληνύχτα.”
“Καληνύχτα.”

These replies occur at slightly different moments, with light natural overlap. They must sound like several individual neighbors, not one speaker and not a coordinated chorus.

3. ELENI replies last while she also turns and walks screen-left:
“Σας ευχαριστούμε, καλό βράδυ.”

Only the assigned speakers move their mouths during their lines. Myrto does not speak; she moves her wheelchair smoothly toward screen-left with the group. After Eleni's line, everyone continues exiting screen-left without stopping.

Sound consists only of the exact dialogue, multiple natural voices saying “Καληνύχτα,” footsteps, wheelchair movement, and quiet chair movement in restrained courtyard ambience. No applause, cheering, laughter, music, narration, announcements, or extra phrases.

Preserve every character’s face, age, body, clothing, wheelchair, chair geometry, table, microphone, courtyard architecture, evening light, and spatial continuity from the supplied image.

## Acceptance gate

The Candidate is reviewable only if:

- visible human movement begins immediately;
- every person moves toward screen-left;
- nobody approaches Eleni, stops for a handshake, or creates a farewell ceremony;
- the camera position, framing and focus remain fixed;
- Thanasis speaks while departing;
- several residents beyond the protagonists say «Καληνύχτα»;
- Eleni replies last;
- Myrto moves screen-left with the group and does not speak;
- there is no applause, cheering, music, narration or extra dialogue;
- identities, clothing, wheelchair and scene geometry remain stable.

## Render history

### V1 — Rejected

- Job: `03876795-fd20-4ae5-b94c-d4c8fa25024c`
- Rejected by Yiannis on 2026-08-17.
- Rejection reasons: movement did not begin immediately; residents did not share a clear screen-left exit direction; Thanasis and Eleni performed an unrequested handshake; too few non-protagonist residents said «Καληνύχτα».
- Reuse: prohibited.

### V2 — Candidate

- Job: `930d22c6-261d-4696-804e-cca53d78ed25`
- Technical: 10.005 seconds, 1280×720, 24 fps, H.264, AAC stereo 48 kHz.
- Size: 2,504,183 bytes.
- SHA-256: `15899a46fd99122a8c628a6f1b04d73c93a42912eb938ce588977c13ce9a0cc9`.
- Preliminary visual check: movement begins immediately; the crowd, including Myrto, flows screen-left; no handshake is visible; the camera and composition remain stable in sampled frames.
- Audio activity continues to approximately 8.57 seconds.
- Human review required: exact Greek words, number of distinct residents saying «Καληνύχτα», speaker attribution, vocal tone, lipsync, and full continuity.
