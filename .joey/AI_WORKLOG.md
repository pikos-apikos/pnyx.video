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

**PR:** #52  
**Branch:** `agent/v2.9-edit-reconciliation`

### Human trigger

Yiannis revisited the v2.8 cut, identified that **2 — THE ROOM OF CONSEQUENCES** no longer matched the intended narrative separation, approved a new human-centered Phase 6 treatment, and required repository state to be corrected before another Supercomputer/Kimi K3 pass.

### Decision-history correction after review

The first version of PR #52 described the six-shot Phase 4 as unauthorized documentation drift. That was inaccurate.

The actual history is:

1. An earlier Yiannis sequence separated Phase 2 and Phase 4 into two three-shot groups.
2. Later, Issue #36 and merged PR #51 explicitly authorized a six-shot Phase 4.
3. The later v2.8 directive explicitly directed a separate still-evidence treatment for Phase 2 while retaining the moving evidence material in Phase 4.
4. On 2026-08-20 Yiannis revisited the cut and changed the edit again, restoring the earlier Phase 2 / Phase 4 separation for v2.9.

Therefore v2.9 is a **newer human revision that supersedes an earlier human-approved arrangement**. The Supercomputer did not invent the v2.8 structure; it followed the then-current instructions.

### Current v2.9 Phase 2 / Phase 4 placement

**Phase 2 — THE ROOM OF CONSEQUENCES**

1. `e0b9d85a-3f0f-4bfb-9d51-ab18187d4b4f`
2. `d4fff9fe-e12c-4299-9bbb-8a88c8621d68`
3. `d99323a3-56c4-41a9-ac75-2ba437046201`

**Phase 4 — THE PUBLIC BRIEFING**

1. `c6cd0e00-6bad-4fa8-96e6-f1128e455e28`
2. `114f44f7-4626-4369-8627-2a3ce6cc6c97`
3. `ac4a9414-da71-4abc-ad56-b9297fd568d9`

### Phase 6 redesign

Narrative principle:

> Η απόφαση εμφανίζεται μέσα από πρόσωπα και σιωπές, όχι μέσα από πανηγυρικό γράφημα.

Human-selected image plates:

- Eleni/result: `c8d2b6c4-11e8-49a9-9542-bb32399754b0`
- Thanasis @ KEP: `f7884b5d-3b96-4a36-8f5d-760bfe7d8d18`
- Thanasis @ low wall: `bdf80b02-1841-4fab-adeb-6c59a5a3af6f`

Human-selected video takes:

1. Eleni/result: `69e0ada1-ae60-450d-b353-ff3dd1929d9c`
2. Thanasis/result @ KEP: `3eb34af9-6daf-42aa-8255-46746ab91dc0`
3. Thanasis/return to low wall: `4ceef784-7f86-4cd7-b54a-76f04e3323a9`

The static `fc781492-37cc-4814-9429-793f4dfae6f5` remains historical approved material but is demoted from the preferred v2.9 Phase 6 treatment. The abandoned departure/farewell sequence remains excluded.

### PR #52 review blockers and resolution

A later review of PR #52 identified four blockers.

1. **Dropped approved Phase 9 beat:** restored `bec2e4f1-a384-4572-941c-d8afc7385b1e`, the approved post-rain accountability shot.
2. **Stale unresolved intermediate:** resolved. `9ea93421-b936-4543-86b4-a09891ac9909` is itself the approved public-memory / new-protagonists bridge with the two unnamed adults. There is no second unknown intermediate UUID.
3. **Bus approval:** review correctly identified that `c3b63365-e577-4590-a554-dccd18afadbc` was still only Issue #37 Candidate material at that moment. Yiannis then explicitly promoted it on 2026-08-20 with “εγκρίνω το c3b63365”. It is now Approved for v2.9 edit use.
4. **Provenance accuracy:** corrected. The six-shot Phase 4 and v2.8 Phase 2 treatment were explicitly human-authorized before being superseded by the current v2.9 revision.

Current opening source lock:

`9caf49b2-3e6c-4393-b78e-ec5ba97d5afd` at `0.6×`, silent
→ `c3b63365-e577-4590-a554-dccd18afadbc`
→ Phase 1 intertitle / Phase 1.

### Workflow rules learned

**A correction list is not a source map.** Every future Supercomputer handoff/report should include the complete timeline.

**Provenance is chronological, not retroactive.** When the human changes a decision, preserve the fact that the previous decision was valid at the time and record the newer decision as superseding it.

**Candidate presence is not approval.** A beta may contain Candidate material; only explicit human promotion changes state.

**Specialist-skill loading is a precondition.** Before authoring a production prompt, read `skills/manifest.yaml`, follow its load order, and load the named specialist. Joey owns production order/state/provenance; the specialist owns prompt grammar.

### Unresolved infrastructure / provenance items

- Gate-entry Take B UUID remains separately unresolved in existing repository state.
- `cinema-director/SKILL.md` is declared by the repository manifest but was not exposed by the current repository/harness during this session.

### Human gate

PR #52 prepared the first v2.9 source-of-truth. It did not approve a final cut or authorize publication, upscale, or festival submission.

---

## 2026-08-20 — v2.9 final correction after first assembled review

**Branch:** `agent/v2.9-final-correction`

### Human trigger

After reviewing the assembled v2.9 direction, Yiannis issued a new explicit correction set. These decisions supersede the relevant placements recorded by PR #52 without rewriting their historical validity.

### Subtitle correction

`324b5b27-02ed-464e-b8b0-7849d86ac3c7` keeps its existing Greek audio. The missing English subtitle must be added for the human-transcribed line:

«Η αρχική προθεσμία ήταν αρκετά αισιόδοξη.»

Subtitle:

“The initial deadline was quite optimistic.”

### Remove standalone interface/frame

`b8c562bf-07ca-4217-8f89-23449d0d4a43` must not appear in the active v2.9 timeline as a standalone frame, still, insert, or overlay. Its historical asset approval remains recorded.

### Phase 8 / Phase 9 revision

Phase 8 now contains only:

`09596bc2-5f1f-461f-abdf-694beb2bd8ae`

Phase 9 now contains only:

`197bcd61-eb5a-499f-be15-2dc4c72e51d3`

`197bcd61…` therefore moves from Phase 8 to Phase 9.

Remove from the active v2.9 cut:

- `bec2e4f1-a384-4572-941c-d8afc7385b1e`
- `9ea93421-b936-4543-86b4-a09891ac9909`
- `43f4a3c7-dfdc-4576-8cfe-113b9b6564d3`

These remain historical approved/used assets where applicable; their current placement is removed.

### Epilogue revision

Current Epilogue source order:

`4d665b7c-be96-40db-a79e-b0dd1518fb24`
→ `78adc280-3a94-4f58-bb4b-6a9f7b44a71f`
→ black.

Over black, Eleni's existing voice returns with only:

«Δεν ξέρω τι ακριβώς πρέπει να γίνει.»

Use audio-only from existing source `18b7a08f-ea77-4614-b695-da3fba1950d7`. This reuse is explicitly authorized for the Epilogue. Do not show the old picture and do not regenerate or clone the voice.

### Human gate

This correction changes the v2.9 review Candidate map. It still does not authorize final publication, upscale, submission, or new generation.
