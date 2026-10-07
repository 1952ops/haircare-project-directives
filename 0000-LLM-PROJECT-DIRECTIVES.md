# 0000 — LLM Project Directives

## Purpose

This file gives future LLMs, agents, and coding assistants the working rules for project setup, file naming, and evidence organization.

The user prefers ADHD-friendly, highly visible naming conventions. When a conversation starts becoming a project, workflow, research thread, evidence set, reusable idea, source-of-truth document, or repeatable system, the assistant should proactively suggest project-convention names before the file structure drifts.

## Standing Assistant Behavior

When the user introduces a possible project, ask:

> Should I name this using the project convention?

When the project shell is obvious, suggest the exact starting file:

> Should I name this `0000 — START HERE — PROJECT CHARTER`?

When the user proposes a filename outside the convention, gently suggest the corrected convention and explain why in one sentence. Do not overcorrect casual notes that are clearly not meant to become project files.

## Core Project Files

Use these files for the project structure:

```text
0000 — START HERE — PROJECT CHARTER
0001 — LIVE ASSESSMENT
0002 — SOURCE LOG
0003 — DECISION FRAMEWORK
0004 — OPEN QUESTIONS
9999 — CHANGELOG
```

### Meanings

| Label | Purpose |
|---|---|
| `0000` | Project charter, governance, scope, registry, source-of-truth rules |
| `0001` | Current working assessment, synthesis, or project status |
| `0002` | Source log, raw claims, provenance, preserved notes |
| `0003` | Decision framework, accepted rules, standards, or criteria |
| `0004` | Open questions, missing facts, unresolved items |
| `9999` | Changelog and revision history |

## Evidence Item Labels

Use single letters for ordinary evidence packets:

```text
001A — EVIDENCE — FIRST EVIDENCE ITEM
001B — EVIDENCE — SECOND EVIDENCE ITEM
001C — EVIDENCE — THIRD EVIDENCE ITEM
```

Evidence labels are stable. Do not rename an evidence item just because the assessment changes.

## Special Record Type Labels

Use two-letter suffixes that match the visible phrase whenever possible:

| Code | Meaning |
|---|---|
| `PS` | Professional Source |
| `UO` | User Observation |
| `DX` | Discrepancy |
| `GD` | Governance Decision |
| `CL` | Claim |
| `RL` | Rule |
| `RQ` | Research Question |
| `TS` | Test |
| `EX` | Experiment |
| `RV` | Revision |

### Examples

```text
001PS — PROFESSIONAL SOURCE — FIRST PROFESSIONAL SOURCE
001UO — USER OBSERVATION — FIRST USER OBSERVATION
001DX — DISCREPANCY — FIRST DISCREPANCY
001GD — GOVERNANCE DECISION — FIRST GOVERNANCE DECISION
001CL — CLAIM — FIRST CLAIM
001RL — RULE — FIRST RULE
001RQ — RESEARCH QUESTION — FIRST RESEARCH QUESTION
001TS — TEST — FIRST TEST
001EX — EXPERIMENT — FIRST EXPERIMENT
001RV — REVISION — FIRST REVISION NOTE
```

## Why These Codes

Use `PS`, `UO`, and `GD` because they are exact acronyms for their descriptions:

- `PS` = Professional Source
- `UO` = User Observation
- `GD` = Governance Decision

Keep `DX` for discrepancy because it is distinct, collision-resistant, and reads as a problem/conflict record.

Avoid less direct codes like `PR`, `OB`, or `GV` when an exact acronym is available.

## Full Example Layout

```text
0000 — START HERE — PROJECT CHARTER
0001 — LIVE ASSESSMENT
0002 — SOURCE LOG
0003 — DECISION FRAMEWORK
0004 — OPEN QUESTIONS

001A — EVIDENCE — ORS Relaxer
001B — EVIDENCE — ORS Leave-In Conditioner
001D — EVIDENCE — Plant Guru African Black Soap
001E — EVIDENCE — Jamaican Mango & Lime Black Castor Oil
001F — EVIDENCE — ORS Deep Conditioner
001G — EVIDENCE — ORS Heat Protector
001H — EVIDENCE — Rogaine Minoxidil Foam

001PS — PROFESSIONAL SOURCE — YouTube Hair Professional Notes
002PS — PROFESSIONAL SOURCE — AAD Black Hair Care Guidance

001UO — USER OBSERVATION — Wash Day and Scalp Response
002UO — USER OBSERVATION — Product Identity and Hair State
003UO — USER OBSERVATION — Heat Styling and Relaxer Placement

001DX — DISCREPANCY — Amazon Ingredient List Mismatch
002DX — DISCREPANCY — Product Image Unavailable In Scratch

001GD — GOVERNANCE DECISION — Google Docs Are Canonical
002GD — GOVERNANCE DECISION — Uploaded Files Are Evidence Snapshots

001CL — CLAIM — Oil Should Only Be Applied To Ends And Mid-Shaft
002CL — CLAIM — Grease Does Not Penetrate Scalp

001RL — RULE — SCALP-001 — Cleanse The Scalp
002RL — RULE — FIBER-001 — Oils Differ In Penetration

001RQ — RESEARCH QUESTION — Finished pH Of Black Soap
001TS — TEST — Coconut Oil Mid-Shaft-To-Ends Only

9999 — CHANGELOG
```

## File-Naming Rules

1. Keep labels stable once assigned.
2. Do not reuse a label for a different item.
3. Separate the object from the conclusion.
4. Preserve source material even when the assessment changes.
5. Mark source problems immediately with `DX`.
6. Use `0000` before creating complex project artifacts.
7. Use `0001` for living analysis and status.
8. Use `0002` for raw source claims and evidence preservation.
9. Use `0003` for rules and decisions only after review.
10. Use `0004` for unresolved questions instead of burying them in chat.

## Correction Protocol

If the user names a file outside the convention, respond briefly:

```text
Small naming catch: I’d label this `[suggested label]` so it stays inside the project convention.
```

Then proceed with the user’s actual task.

## Source-Of-Truth Protocol

When a project has living documents, identify the canonical owner before editing. Uploaded files, local files, screenshots, and exports may be evidence or snapshots, not necessarily the current source of truth.

If access to the canonical source is unavailable, say so instead of treating old uploads or memory as current.

## Missing Attachment / Scratch Path Protocol

If a referenced local attachment path is missing, do not assume the evidence is invalid or never existed. Scratch files can disappear, move, or fail to copy between tool contexts.

When the missing file matters to the current task:

1. Check whether the file exists under another provided workspace path.
2. Check whether the user supplied a Library file ID or source-file citation for the same item.
3. Ask the user to re-upload only if the evidence is needed and no accessible copy exists.
4. Track the event as a discrepancy if it could affect project interpretation.

Use a label like:

```text
001DX — DISCREPANCY — Local Image Read Error For 001D Site Screenshot
```

For HAIRCARE, product screenshots can be useful for tracking wash-day outcomes, label variants, packaging changes, or source integrity. Preserve them as evidence snapshots when available, but do not treat a transient read error as a product conclusion.

## One-Sentence Rule

Use `0000–0004` for the project shell, single-letter `001A` style labels for evidence items, and direct-acronym suffixes like `001PS`, `001UO`, `001DX`, and `001GD` for special records.
