# PNyX AI Worklog

Purpose: preserve a concise public operational record of AI-assisted repository work so future agents/models can understand what changed, why it changed, which human decisions controlled the change, and what remained unresolved.

This is **not** a private reasoning or chain-of-thought log. It records only auditable actions, decisions, source mappings, discovered workflow failures, and unresolved items that are useful for continuity.

## Logging rule

Whenever an AI-assisted PR is opened for this repository, add an entry containing:

- date and PR/branch;
- human decision or request that triggered the work;
- files changed;
- canonical source/timeline changes;
- important supersessions/exclusions;
- root cause if the PR repairs a workflow/documentation failure;
- unresolved identifiers or human gates;
- whether the PR changes narrative canon, source placement, or only documentation/tooling.

The human remains the decision owner. A worklog entry documents a decision; it does not create approval by itself.

---

## 2026-08-20 — v2.9 edit reconciliation

**Branch:** `agent/v2.9-edit-reconciliation`

### Human trigger

Yiannis reconstructed an earlier explicit edit proposal and identified that the v2.8 cut had the wrong content in **2 — THE ROOM OF CONSEQUENCES**. He also approved a new three-shot human-centered treatment for **6 — THE DECISION** and instructed that repository state be corrected before sending another Supercomputer/Kimi K3 prompt.

### Root cause found

The earlier human sequence separated:

- Phase 2: `e0b9d85a… → d4fff9fe… → d99323a3…`
- Phase 4: `c6cd0e00… → 114f44f7… → ac4a9414…`

A later partial correction note incorrectly described the Phase 2 trio as Phase 4. A subsequent reconciliation restored three missing Phase 4 recipient beats by appending them, accidentally creating a six-shot Phase 4. Later Supercomputer instructions then reinforced that mapping and replaced Phase 2 with a still-evidence workaround.

The Supercomputer therefore executed a wrong source map correctly. The failure was in repository memory/source placement, not in rendering.

### v2.9 source-placement correction

**Phase 2 — THE ROOM OF CONSEQUENCES**

1. `e0b9d85a-3f0f-4bfb-9d51-ab18187d4b4f`
2. `d4fff9fe-e12c-4299-9bbb-8a88c8621d68`
3. `d99323a3-56c4-41a9-ac75-2ba437046201`

**Phase 4 — THE PUBLIC BRIEFING**

1. `c6cd0e00-6bad-4fa8-96e6-f1128e455e28`
2. `114f44f7-4626-4369-8627-2a3ce6cc6c97`
3. `ac4a9414-da71-4abc-ad56-b9297fd568d9`

The earlier six-shot Phase 4 is explicitly treated as documentation drift, not human canon.

### Phase 6 redesign

Narrative principle retained:

> Η απόφαση εμφανίζεται μέσα από πρόσωπα και σιωπές, όχι μέσα από πανηγυρικό γράφημα.

The static proposal plate is no longer the preferred main decision treatment. Human-approved Joey/Higgsfield sources now define the phase:

**Approved image plates**

- Eleni/result: `c8d2b6c4-11e8-49a9-9542-bb32399754b0`
- Thanasis @ KEP: `f7884b5d-3b96-4a36-8f5d-760bfe7d8d18`
- Thanasis @ low wall: `bdf80b02-1841-4fab-adeb-6c59a5a3af6f`

**Approved video takes**

1. Eleni/result: `69e0ada1-ae60-450d-b353-ff3dd1929d9c`
2. Thanasis/result @ KEP: `3eb34af9-6daf-42aa-8255-46746ab91dc0`
3. Thanasis/return to low wall: `4ceef784-7f86-4cd7-b54a-76f04e3323a9`

The abandoned departure/farewell sequence remains excluded.

### Other locked decisions carried into v2.9

- Prelude `9caf49b2…` plays at `0.6×` for non-native-English reading comfort.
- Preserve `c3b63365…` Eleni silent on the bus after the prelude.
- Phase 5 remains `9bd30c09…` through exact `00:08.662` → `d09e75e3…`; all later applause is prohibited.
- Phase 7 remains `d7bc4cb6… → 324b5b27… → 2d46cc51…`.
- Phase 8 remains `09596bc2… → 197bcd61…`.
- Phase 9 remains `9ea93421… → [existing intermediate new-protagonists clip, UUID unresolved] → 43f4a3c7…`.

### Files changed in this PR

- `docs/HIGGSFIELD_SUPERCOMPUTER_EDIT_HANDOFF.md`
- `.joey/V2_9_SOURCE_LOCKS.md`
- `provenance/2026-08-20_V2_9_EDIT_RECONCILIATION.md`
- `.joey/AI_WORKLOG.md`

### Workflow rules learned

A correction list is not a source map.

Every future Supercomputer edit report/handoff should include the **complete timeline**, so approved beats cannot silently disappear or migrate between phases.

**Specialist-skill loading is a precondition, not an optional cleanup step.** Before authoring a production prompt, an agent must read `skills/manifest.yaml`, follow its declared load order, and load the named specialist for the requested stage. Joey owns production order/state/provenance; the specialist owns prompt grammar. For video, the manifest currently names `cinema-director` (legacy name `cinema-worldbuilder-pro-2.0`). If the specialist skill is unavailable in the current harness/repository, the agent must state that limitation and avoid claiming that the prompt follows the specialist grammar.

This guardrail was added after the assistant began preparing a v2.9 Supercomputer prompt before loading the declared video specialist. Yiannis caught the mistake. Future agents should not rely on conversational familiarity with the project as a substitute for loading the declared skill chain.

### Unresolved

- Exact UUID of the intermediate new-protagonists clip moved from Phase 8 to Phase 9 remains unresolved and must never be guessed.
- Gate-entry Take B UUID remains separately unresolved in existing repository state.
- `cinema-director` is declared by `skills/manifest.yaml` as the video specialist, but its `SKILL.md` was not present in the repository and was not available as an installed plugin in the current harness during this session.

### Human gate

This PR prepares the v2.9 source-of-truth. It does not approve a final cut or authorize publication/upscale/festival submission.
