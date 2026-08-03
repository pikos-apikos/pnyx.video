---
name: joey-workflow
description: "Plan and run a multi-session AI-cinematic production as a Wayfinder-style issue map plus Joey's dependency-driven canon pipeline. Use for films, documentaries, series, music videos, commercials, or cinematic worlds that need persistent state, human-approved creative decisions, traceable assets, and one frontier ticket at a time."
disable-model-invocation: true
---

# Joey Workflow — Cinematic Wayfinder

Joey Workflow combines two disciplines:

1. **Wayfinder governs the work:** one destination, one canonical map issue, precise decision tickets, a visible frontier, fog of war, and no more than one non-research ticket resolved per session.
2. **Joey governs production dependencies:** story bible → character specification → face lock → base outfit → character sheet → props → empty environments → scene plates → video → audio/edit.

The combination prevents attractive but disconnected assets and stops the agent from repeatedly generating downstream work after losing track of human approvals.

## Non-negotiable boundary

The human owns creative canon decisions. The agent may research, structure, compare, validate, perform deterministic repository work, and prepare candidates.

The agent MUST NOT:

- reinterpret “next” as approval of an unclear candidate;
- invent a new character because the current frontier was forgotten;
- resolve more than one non-research ticket per session;
- promote a creative candidate without explicit human approval recorded on its ticket;
- treat an infographic, dossier, contact sheet, or prompt as the requested image unless the ticket explicitly asks for that artifact;
- continue after the user says stop.

## Source of truth

- GitHub Issues: canonical Wayfinder map and decision tickets.
- Repository files: canon, prompts, manifests, provenance, and approved assets.
- Issue resolution comments: why decisions were made.
- Git history: accepted changes and supersession history.

A local `.joey/PRODUCTION_MAP.md` mirrors the map for portability; the GitHub map issue is authoritative.

# Wayfinder layer

## Map issue

Create exactly one map issue containing:

- Destination
- Canon source
- Notes
- Decisions so far
- Not yet specified
- Out of scope

The map is an index. Full prompts and asset specifications live in files or tickets.

## Tickets

Each ticket contains:

- exact question or task;
- Joey stage;
- mode: HITL decision, HITL prototype, AFK research, AFK/HITL task;
- named dependencies;
- inputs;
- acceptance criteria;
- output path.

Refer to tickets by title, not bare numbers.

## Frontier

The frontier contains open, unclaimed tickets whose dependencies are satisfied.

- Pick only from the frontier.
- Claim before work when possible.
- Work one non-research ticket per session.
- Parallel research is allowed only when it cannot pre-empt a creative decision.
- Keep uncertain future work in fog; do not rigidly pre-slice the whole film.

## Resolution

1. Record the answer or approval on the ticket.
2. Commit the approved artifact or metadata.
3. Close the ticket.
4. Add one linked gist to the map's Decisions so far.
5. Recalculate the frontier.

Rejected, superseded, and invalid outputs stay traceable but are never reused as references.

# Joey layer

Every asset has one state: `candidate`, `approved`, `rejected`, `superseded`, or `invalid`.

## Stage 1 — Story Bible

Lock premise, emotional question, reality level, time/place, visual and sound language, characters, relationships, and production rules.

**Gate:** explicit human approval.

## Stage 2 — Character text lock

One character at a time. Lock identity, story function, face/body, hair, skin, identity markers, movement, stillness, speech, emotional register, and prohibited drift.

**Gate:** explicit human approval.

## Stage 3 — Face lock

Identity image only: neutral mid-gray seamless, controlled light, simple baseline clothing, no scene, infographic, dossier, or narrative environment unless requested.

**Gate:** select one exact candidate and record its file and SHA-256.

## Stage 4 — Base outfit

One full-body outfit reference using the approved face lock. No character sheet first.

## Stage 5 — Character sheet

Default three-panel continuity sheet, built from approved face and outfit references.

## Stage 6 — Props

One recurring continuity-sensitive object per ticket.

## Stage 7 — Empty environments

Lock architecture, geography, materials, light, weather range, and spatial relationships without characters.

## Stage 8 — Scene plates

Combine only approved character, outfit, prop, and environment references.

## Stage 9 — Video

Motion begins only after the visual scene anchor is approved. Lock subject motion, camera motion, duration, sound bed, continuity, and final frame.

## Stage 10 — Audio and edit

Dialogue/lipsync, sound, score, selected takes, grade, edit rhythm, disclosure, and final delivery.

# Invocation

## Chart a production

1. Name the destination.
2. Locate or create canon.
3. Create the map issue.
4. Add only currently precise tickets.
5. Wire named dependencies.
6. Stop after charting unless the user explicitly requests the first ticket too.

## Continue a production

1. Load the map at low resolution.
2. Query the frontier.
3. Select and claim one ticket.
4. Load only its dependencies and relevant canon.
5. Invoke the specialist skill.
6. Produce one candidate or deterministic result.
7. Stop at the human decision boundary.

## Autonomous mode

Autonomous continuation means research, structuring, deterministic repository work, and candidate preparation. It never means making the human's creative selection or repeatedly rendering the whole pipeline.

# Specialist routing

- `story-bible-builder`
- `character-builder`
- `banana-pro-director-3.0`
- `cinema-director`

Specialists own prompt grammar. Joey Workflow owns order, state, provenance, and the decision boundary.

# Required session report

- Map
- Current ticket
- Status
- Canonical changes
- Invalidated outputs
- Next frontier

Never claim a stage is complete because prompts or plans exist. A stage completes only when its gate is satisfied and recorded.
