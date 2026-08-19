# PNyX v2.9 edit reconciliation — 2026-08-20

## Purpose

Record the human reconstruction that corrects the Phase 2 / Phase 4 mapping error carried into v2.8 and source-lock the newly approved Phase 6 decision footage.

This file exists because the previous workflow allowed partial correction notes to replace a complete timeline map. That caused approved footage to be reassigned between phases and later made the Supercomputer execute a structurally wrong sequence correctly.

## Root cause

Yiannis's earlier explicit sequence placed:

### 2 — THE ROOM OF CONSEQUENCES

`e0b9d85a-3f0f-4bfb-9d51-ab18187d4b4f`
→ `d4fff9fe-e12c-4299-9bbb-8a88c8621d68`
→ `d99323a3-56c4-41a9-ac75-2ba437046201`

and separately:

### 4 — THE PUBLIC BRIEFING

`c6cd0e00-6bad-4fa8-96e6-f1128e455e28`
→ `114f44f7-4626-4369-8627-2a3ce6cc6c97`
→ `ac4a9414-da71-4abc-ad56-b9297fd568d9`

A later v2.5 correction note listed the first trio as Phase 4. PR #51 then restored the three missing recipient beats by appending them, producing an incorrect six-shot Phase 4. The subsequent Supercomputer prompt reinforced that drift by replacing Phase 2 with a still-evidence workaround.

No human creative decision authorized that six-shot merger.

## Corrected human source placement

### Phase 2 — THE ROOM OF CONSEQUENCES

1. `e0b9d85a-3f0f-4bfb-9d51-ab18187d4b4f` — Print from PNyx.
2. `d4fff9fe-e12c-4299-9bbb-8a88c8621d68` — Review / evidence-room work.
3. `d99323a3-56c4-41a9-ac75-2ba437046201` — Plan / route detail.

These sources are restored to Phase 2. The improvised still-evidence montage is not the canonical replacement.

### Phase 4 — THE PUBLIC BRIEFING

1. `c6cd0e00-6bad-4fa8-96e6-f1128e455e28` — Eleni / «Ξεκίνησε».
2. `114f44f7-4626-4369-8627-2a3ce6cc6c97` — Thanasis @ KEP / printed briefing.
3. `ac4a9414-da71-4abc-ad56-b9297fd568d9` — Myrto / «Με σκέφτηκαν».

These are the three recipient beats. They are not shots 4–6 of a six-shot phase.

## Phase 6 redesign — human decision

The static amended-proposal hold is no longer the preferred visual solution for **6 — THE DECISION**.

Narrative principle retained from the treatment:

> Η απόφαση εμφανίζεται μέσα από πρόσωπα και σιωπές, όχι μέσα από πανηγυρικό γράφημα.
>
> Η τροποποιημένη πρόταση εγκρίνεται. Ο Θανάσης ψηφίζει κατά. Η θέση του παραμένει στο δημόσιο αρχείο μαζί με το επιχείρημά του.
>
> Η κάμερα τον ακολουθεί ως το σπίτι. Δεν του ζητά να δηλώσει ότι «η δημοκρατία λειτούργησε».

The practical implementation was simplified into ordinary channels already established in the film:

- Eleni receives the result digitally.
- Thanasis receives/reads the result through the KEP/public-service route.
- Thanasis returns to the familiar low concrete wall.

Myrto is not required in Phase 6.

### Approved Joey image plates

- Eleni / result: `c8d2b6c4-11e8-49a9-9542-bb32399754b0`.
- Thanasis @ KEP: `f7884b5d-3b96-4a36-8f5d-760bfe7d8d18`.
- Thanasis @ low wall: `bdf80b02-1841-4fab-adeb-6c59a5a3af6f`.

### Approved Phase 6 video takes

- Eleni / result: `69e0ada1-ae60-450d-b353-ff3dd1929d9c`.
- Thanasis @ KEP: `3eb34af9-6daf-42aa-8255-46746ab91dc0`.
- Thanasis @ low wall: `4ceef784-7f86-4cd7-b54a-76f04e3323a9`.

Canonical Phase 6 order:

`69e0ada1…` → `3eb34af9…` → `4ceef784…`

The older still `fc781492-37cc-4814-9429-793f4dfae6f5` may remain historical/approved source material, but it is not the preferred main Phase 6 body in v2.9.

The abandoned departure/farewell sequence remains excluded.

## Prelude timing amendment

Approved introduction:

`9caf49b2-3e6c-4393-b78e-ec5ba97d5afd`

Playback is **0.6×**. The source has large text blocks and little meaningful motion; the timing change exists for comfortable reading by non-native English viewers.

After the prelude preserve:

`c3b63365-e577-4590-a554-dccd18afadbc` — Eleni silent on the bus.

## Phase 5 preserved correction

The later public-consultation correction remains authoritative:

`9bd30c09-d258-44d5-84e6-e311221acd07` through exact `00:08.662`
→ `d09e75e3-c251-4bed-9117-83628bb6f5e5`.

All footage and applause after 08.662 remain prohibited.

Earlier development-state `c2787450-2f88-4b86-a0b1-a6dd5074818f` and `e57fc675-f5ef-4290-b336-e746ee826d72` are not restored by this reconciliation.

## Phases 7–9 preserved state

Phase 7:

`d7bc4cb6-ea2e-48e4-af51-a991ebbeb771`
→ `324b5b27-02ed-464e-b8b0-7849d86ac3c7`
→ `2d46cc51-a100-48d1-9894-7208827186a9`.

Phase 8 ending:

`09596bc2-5f1f-461f-abdf-694beb2bd8ae`
→ `197bcd61-eb5a-499f-be15-2dc4c72e51d3`.

Phase 9:

`9ea93421-b936-4543-86b4-a09891ac9909`
→ exact existing intermediate new-protagonists clip, UUID still to be deterministically recovered
→ `43f4a3c7-dfdc-4576-8cfe-113b9b6564d3`.

Do not guess the unresolved intermediate UUID.

## Workflow rule added by this incident

Every Supercomputer edit handoff must report and preserve the **complete candidate timeline**, not only changed shots.

A correction list is not a source map.

Future reconciliation must distinguish:

1. source approval;
2. source supersession;
3. source placement in the timeline;
4. local edit corrections.

Changing one does not implicitly change the others.
