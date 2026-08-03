# References and attribution

`joey-workflow` is an original integration layer built for this project. It combines two source traditions while adding its own production-state, provenance, and human-approval rules.

## Wayfinder

- **Original skill:** [Wayfinder — `SKILL.md`](https://github.com/mattpocock/skills/blob/main/skills/engineering/wayfinder/SKILL.md)
- **Author / repository:** [Matt Pocock — `mattpocock/skills`](https://github.com/mattpocock/skills)

Concepts adapted from Wayfinder include:

- one named destination;
- a canonical map issue;
- decision tickets rather than uncontrolled execution;
- frontier and dependency handling;
- fog of war / not-yet-specified work;
- one focused non-research ticket per session;
- explicit human-in-the-loop decisions.

This repository does not claim authorship of Wayfinder. The Joey Workflow applies its planning discipline to cinematic production.

## Joey's cinematic workflow

- **Source video on Joey's YouTube channel:** [YouTube — AI cinematic workflow](https://www.youtube.com/watch?v=fMU7Ku8ma4A)
- **Companion article / resources:** [Everything You Need to Start Building Your AI Cinematic World](https://pyrite-mallow-3b0.notion.site/Everything-You-Need-to-Start-Building-Your-AI-Cinematic-World-and-my-thoughts-on-HF-s-updated-T-C-3ae49da027d780cea5b2e139b25800ec)

Ideas adapted from Joey's workflow include:

- story/world bible before visual generation;
- text-locking characters before rendering them;
- identity / face lock before outfit and character sheet;
- canonical props and empty environment plates before scene composition;
- scene plates before motion/video generation;
- consistency through approved references rather than repeated text-only prompting.

The source video is the verified YouTube reference supplied for this workflow. A direct stable channel handle is intentionally not guessed here; the creator/channel attribution is available from the linked YouTube video page.

## This integration

The combined **Joey Workflow — Cinematic Wayfinder** adds project-specific operational rules that are not attributed to either source verbatim:

- candidate / approved / rejected / superseded / invalid asset states;
- SHA-256 and repository provenance for approved assets;
- explicit prevention of accidental auto-approval;
- separation of deterministic AFK tasks from creative HITL gates;
- invalid-output quarantine;
- GitHub Issues as the production map and repository files as canonical assets.

When reusing or publishing this skill, preserve this attribution file and the upstream links.
