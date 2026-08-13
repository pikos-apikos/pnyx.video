---
name: controlled-cinematic-english
description: Controlled natural language for AI filmmaking intent, cinematic handoffs, shot contracts, continuity, and prompt compilation. Use before image/video director skills when user language can map to multiple cinematic actions, when continuity must be preserved, or when creative decision authority must remain explicit.
---

# Controlled Cinematic English

Controlled Cinematic English (CCE) is a controlled natural language for AI filmmaking workflows.

CCE is inspired by controlled-language principles and formal cinematography languages. It is not an industry standard and does not claim compliance with ASD-STE100 or Prose Storyboard Language.

CCE sits between free-form human intent and production-specific prompt grammars.

The objective is:

> Reduce semantic freedom at the boundary between director intent and model execution.

CCE does not replace a downstream skill's prompt grammar.

It compiles intent into a stable contract that a downstream skill can consume.

## Position in the workflow

Use this order:

```text
Human intent
→ CCE normalization and disambiguation
→ cinematic production skill
→ model/platform adapter
→ generation
→ result review
```

Examples of downstream production skills:

- Banana Pro Director
- Cinema Worldbuilder
- Higgsfield prompt/model adapters
- Seedance-specific prompt compilers
- storyboard or shot-list systems

## Human language is allowed

The user does not need film vocabulary.

Accept colloquial, incomplete, or non-technical language.

Do not force the user to translate an idea into cinematography terminology.

Translate user intent into production terminology only after the meaning is sufficiently clear.

## Disambiguation gate

Before execution, identify whether the request has one safe interpretation or multiple materially different interpretations.

Resolve silently when:

- the referent is unique in the current context;
- the requested change has one operational meaning;
- the interpretation does not change a material creative decision;
- the interpretation does not change a locked continuity property.

Ask one concrete question when ambiguity can materially change the output.

Do not ask:

> What do you mean?

Name the likely interpretations.

Examples of ambiguous intent classes:

- target asset or target shot;
- subject or referent;
- shot size;
- camera position;
- camera movement;
- subject blocking;
- performance intensity;
- lighting;
- pacing;
- runtime;
- final composition;
- continuity reference;
- model or tool;
- edit versus regeneration;
- narrative emphasis.

Do not ask for clarification when the current context already resolves the ambiguity uniquely.

## Ambiguous adjectives

Do not silently convert broad adjectives into arbitrary cinematic controls.

Examples:

- more dramatic
- more intimate
- more dynamic
- darker
- bigger
- closer
- slower
- stronger
- more cinematic
- more realistic

Determine whether the requested quality could refer to multiple material dimensions.

For example, "more dramatic" can change performance, framing, camera movement, lighting, pacing, sound, or edit rhythm.

If more than one interpretation remains plausible and the choice changes the shot materially, ask the user to choose.

## Ambiguous spatial language

Distinguish camera-space changes from subject-space changes.

Examples:

- "closer" can mean camera movement, tighter framing, or subject movement;
- "move left" can mean screen-left, world-space left, or camera-left;
- "lower" can mean camera height, framing, subject posture, or light position.

Do not select one interpretation only because it is common.

## Decision authority

Creative authority is explicit.

Use:

- `DECISION OWNER: HUMAN`
- `DECISION OWNER: AGENT`
- `DECISION OWNER: EXISTING CONTRACT`

Default material creative choices to:

`DECISION OWNER: HUMAN`

The agent can recommend an option.

A recommendation is not a decision.

The agent MUST NOT silently choose among materially different viable creative options unless the user explicitly delegates that decision.

Material creative decisions include:

- narrative emphasis;
- casting;
- canonical character appearance;
- wardrobe canon;
- mobility canon;
- shot design;
- composition;
- camera language;
- performance direction;
- lighting language;
- scene order;
- final visual selection.

## Known, unknown, assumption

Use these states internally when continuity or source truth matters:

- `KNOWN`
- `UNKNOWN`
- `ASSUMPTION`

Do not convert a material `UNKNOWN` into an `ASSUMPTION` only to continue generation.

If an unknown affects a canonical property, stop that affected action and resolve it.

## Canonical reference roles

Do not treat one image as evidence for properties that it does not show.

Keep reference roles distinct:

- `IDENTITY REFERENCE`
- `WARDROBE REFERENCE`
- `BODY / MOBILITY REFERENCE`
- `PROP REFERENCE`
- `ENVIRONMENT REFERENCE`
- `STYLE REFERENCE`
- `COMPOSITION REFERENCE`

One asset can fill more than one role only when the relevant property is clearly visible and intentionally canonical.

An identity portrait does not automatically define wardrobe, body, mobility equipment, props, environment, or blocking.

A scene plate does not replace a canonical identity reference when the downstream workflow requires a separate identity anchor.

## Continuity contract

For each shot, identify the continuity properties that must remain stable.

Possible properties:

- identity;
- hair;
- wardrobe;
- body;
- mobility equipment;
- held props;
- location;
- time of day;
- weather;
- screen side;
- depth layer;
- eyeline;
- contact points;
- damage, dirt, wetness, or other state changes;
- lighting direction;
- scene geography.

Do not add a continuity property that the project has not established.

## CCE shot intent contract

Use the minimum fields needed for the shot.

```text
GOAL:
SHOT PURPOSE:
SUBJECTS:
CANONICAL REFERENCES:
FRAME:
CAMERA:
BLOCKING:
ACTION:
PERFORMANCE:
LIGHT:
WORLD:
CONTINUITY:
SOUND:
RUNTIME:
LAST FRAME:
DECISION OWNER:
UNKNOWNS:
```

This is an internal or handoff contract.

Do not force every field into every request.

Do not expose this complete form to the user when a short clarification or short pre-prompt check is sufficient.

## CCE asset intent contract

For character and still-image asset work, use the minimum applicable fields:

```text
GOAL:
TARGET ASSET:
SUBJECT:
IDENTITY REFERENCE:
WARDROBE REFERENCE:
BODY / MOBILITY REFERENCE:
PROP REFERENCE:
ENVIRONMENT REFERENCE:
FRAMING:
POSE:
EXPRESSION:
LIGHT:
OUTPUT MODE:
DECISION OWNER:
UNKNOWNS:
```

## Compile to Banana Pro Director

CCE runs before Banana Pro Director.

CCE resolves:

- which asset is being created or changed;
- which character is the target;
- which canonical reference role each uploaded image has;
- which properties are locked;
- which properties are intentionally changing;
- whether the request is identity, wardrobe, body/mobility, prop, environment, framing, or scene work;
- which decisions remain human-owned.

Then Banana Pro Director keeps its own mode order and prompt grammar.

Do not add CCE labels to the final image-generation prompt unless the downstream skill explicitly requires them.

## Compile to Cinema Worldbuilder

CCE runs before Cinema Worldbuilder.

Map CCE intent into the existing Cinema Worldbuilder blocks:

- shot purpose and dramatic state → `Scene & Mood`
- composition and blocking → `Frame Map`
- subject continuity → `Subject Lock`
- multi-subject relationships → `Cross-Frame Rules`
- physical action and camera movement → `Movement`
- final composition → `Last Frame`
- environment continuity → `World Plate`
- diegetic sound intent → `Sound Bed`
- physical image realism → `Capture Realism`
- lens and capture specification → `Camera Capture`

Do not replace, rename, reorder, or duplicate the downstream skill's locked blocks.

CCE is an input compiler, not a competing output format.

## Minor iteration rule

A minor edit can bypass a full pre-prompt confirmation only when the edit target is unambiguous.

The CCE disambiguation gate still runs.

If the user says:

> Update it.

and more than one current artifact can reasonably be the target, ask which artifact.

If only one artifact is active and the context uniquely identifies it, update it without unnecessary confirmation.

## User-facing terminology

The production contract uses professional cinematic terminology.

User-facing conversation can adapt to the user's film literacy.

When the user is not comfortable with film terminology, add a short plain-language gloss in parentheses after a film term when it improves understanding.

Do not add these glosses to:

- production prompts;
- model prompts;
- code blocks containing prompts;
- stored production specifications;
- shot contracts;
- documentation intended for agents;
- machine handoffs.

## Prompt preservation

Preserve explicit user intent.

Do not:

- upgrade a suggestion into a requirement;
- convert mood into camera movement without evidence;
- add a shot because it is aesthetically conventional;
- remove an unusual choice because it is not conventional;
- reinterpret a correct film term into a different term;
- add continuity that the source does not establish;
- choose a creative option solely to avoid asking a necessary question.

## Completion check

Before sending an instruction to a production skill, verify:

1. The target is explicit.
2. The subject is explicit.
3. Canonical reference roles are known where required.
4. The requested change is explicit.
5. Locked continuity is preserved.
6. Material unknowns remain visible.
7. The decision owner is correct.
8. The downstream production grammar is unchanged.
9. The user's language has not been over-interpreted.

CCE is successful when the downstream model has fewer plausible unintended interpretations without reducing the director's creative authority.