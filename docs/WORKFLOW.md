# Joey Workflow — Cinematic Wayfinder

This repository combines **Wayfinder's work map** with **Joey's cinematic dependency pipeline**.

## Three layers, one source of truth

### Wayfinder layer

GitHub Issues organize the work:

- one canonical map issue;
- named decision, prototype, research, and task tickets;
- a visible frontier of unblocked work;
- one non-research ticket resolved per session;
- decisions recorded on the ticket and indexed from the map;
- uncertain future work remains fog, not premature tickets.

### Joey layer

Production dependencies are strict:

1. Story Bible
2. Character text lock
3. Face lock
4. Base outfit
5. Character sheet
6. Props
7. Empty environments
8. Scene plates
9. Video
10. Audio and edit

A downstream asset may depend only on explicitly approved upstream assets.

### Festival eligibility layer

Festival rules constrain what may be submitted; they do not change creative approval state.

Before applying festival constraints, identify the exact target:

- AAIFF 2026 → `docs/AAIFF_2026.md`
- Higgsfield Global Film Festival 2026 → `docs/HIGGSFIELD_GLOBAL_FILM_FESTIVAL_2026.md`

Do not merge the two rule sets. A Festival requirement does not silently approve a Candidate, replace an Approved asset, authorize regeneration, or permit migration between projects. When a Festival rule creates an unresolved eligibility question, record it as a blocker and wait for explicit resolution.

For the Higgsfield Global Film Festival specifically, the dedicated Cinema Studio project, AI-only audio, fictional-person/voice, prohibited-content, watermark/packshot, public-post and audit-retention requirements are hard submission gates. The two unresolved questions recorded in the festival overlay — existing Higgsfield generations and the scope of the political-statement prohibition — remain blockers until written Higgsfield clarification exists.

## Human decision boundary

The agent may research, structure, validate, prepare candidates, and perform deterministic repository work.

The human selects creative canon. Silence and the word “next” do not automatically approve an ambiguous result. A wrong character, wrong artifact type, or broken generation is marked `invalid` and never enters canon.

Festival compliance checks may mark material ineligible for a specific submission target, but they do not rewrite historical human approval or creative canon.

## Repository layout

- `canon/` — approved story and production rules
- `assets/` — approved, candidate, rejected, superseded, and invalid assets
- `provenance/` — AI disclosure, sources, licenses, and hashes
- `.joey/` — portable mirror of the issue map and state
- `skills/joey-workflow/` — the project-pinned workflow skill

The GitHub map issue is authoritative. `.joey/PRODUCTION_MAP.md` is a portable mirror.
