# 000T — HAIRCARE Project System Debrief

## Purpose

This document debriefs how the HAIRCARE project was structured, why it worked quickly, and how the same structure can be reused for other project chats.

## Core Finding

HAIRCARE worked because it was not treated as one messy conversation. It was treated as a small knowledge system with clear roles:

- `0000` governed the project.
- `0001` assessed products.
- `0002` preserved professional claims.
- `0003` converted verified evidence into scoped scientific rules.
- `001A–001H` supplied source evidence and product-specific captures.

That structure let the first chat execute the initial purpose on day one because each file already had a job.

## What Made HAIRCARE Easier to Execute

### Clear File Labels

The `0000`, `0001`, `0002`, `0003`, and `001A–001H` naming system gave the project an immediate filing cabinet.

The numbering did the thinking before the model started reading:

- `0000` meant start here.
- `0001` meant product assessment.
- `0002` meant professional claims.
- `0003` meant rules.
- `001A–001H` meant individual evidence packets.

This prevented the project from becoming a scavenger hunt.

### Separate Evidence From Conclusions

The project kept raw product captures, professional claims, scientific rules, and personal-use observations separate.

That mattered because haircare advice often mixes:

- product marketing
- personal experience
- stylist advice
- dermatologist guidance
- cultural memory
- ingredient folklore
- actual scientific evidence

HAIRCARE did not force all of that into one truth bucket. It preserved the input, then reviewed it.

### Source Integrity Notes

You flagged source issues early, such as when an Amazon listing appeared to show relaxer ingredients for a leave-in conditioner or when a product listing was vague.

That was a major accelerator because it told the model:

- do not blindly trust the listing
- compare manufacturer versus retailer records
- preserve discrepancy notes
- avoid premature conclusions

That is project-management gold, honestly. It kept the project from eating bad data and calling it dinner.

### A Charter Before a Routine

The project did not begin with “tell me what to buy” or “make me a routine.”

It began with:

- purpose
- problem
- constraints
- consequences
- evidence files
- future architecture

That made the project strategic instead of reactive. The system could build the decision framework before making product decisions.

### Living Documents Had Defined Owners

The current project structure identifies Google Docs as the canonical owner of living HAIRCARE knowledge.

That matters because it prevents version confusion:

- uploaded files are evidence or snapshots
- Google Docs are the living record
- local files are temporary working copies
- future Git mirrors must be verified before being treated as current

That single-owner rule is one reason this project is more stable than projects where files, chats, and exports all compete as “the real version.”

### The Project Had an Automatic Update Rule

The HAIRCARE instructions authorize relevant document updates during active work.

That reduced friction because the model did not need to ask, every time:

> Should I update the source log?
> Should this become a rule?
> Should this affect the product assessment?

Instead, the workflow became:

1. Read current canonicals.
2. Preserve new evidence.
3. Verify claims.
4. Update affected documents.
5. Report what changed.

That is why the project could move from information intake to execution quickly.

### The First Task Was Narrow Enough to Finish

The project’s first purpose was not “solve all haircare forever.”

It was closer to:

- organize product evidence
- identify discrepancies
- separate claims from rules
- prevent premature routine decisions
- schedule or preserve the next step

That is a manageable first-day goal. Other projects get stuck when the first task is too large, too abstract, or too emotionally loaded to close.

## Why Other Projects Stall

Other project chats tend to struggle when they lack one or more of these:

- a `START HERE` file
- a canonical source-of-truth rule
- a file registry
- a definition of what counts as evidence
- a distinction between raw material and finished conclusions
- an explicit first-day deliverable
- a next-action rule
- update authority
- a parking lot for unresolved questions

When those are missing, the chat keeps rediscovering the project instead of developing it.

## Repeatable Workflow For Future Projects

### Phase 1 — Set The Project Container

Create a `0000 START HERE` document with:

- project name
- purpose
- problem
- constraints
- desired outcome
- what is in scope
- what is out of scope
- file registry
- source-of-truth rule
- update instructions
- next-action rule

### Phase 2 — Separate Inputs By Type

Create separate files for different kinds of material:

- `0001` for live assessment or synthesis
- `0002` for raw claims, quotes, notes, or source logs
- `0003` for rules, principles, decisions, or verified conclusions
- `001A+` for individual source packets, products, cases, people, topics, or evidence items

### Phase 3 — Preserve Before Processing

Before asking for conclusions, preserve:

- source name
- source URL
- date captured
- exact wording when available
- whether the wording is a quote, paraphrase, screenshot, listing, or personal note
- any known issue with the source

### Phase 4 — Define The First-Day Win

Each project needs a small initial execution goal.

Good first-day wins include:

- build the file registry
- classify the uploaded evidence
- identify conflicts
- create the first decision framework
- produce the first source-of-truth document
- make a next-action checklist
- schedule a reminder or follow-up

Bad first-day goals include:

- solve the entire legal case
- create the whole business
- finalize a medical protocol
- automate the full workflow
- produce every deliverable at once

### Phase 5 — Create An Update Loop

Every project should have a rule for what happens when new information arrives:

1. Read the current source-of-truth.
2. Add the new evidence to the correct log.
3. Classify the information.
4. Decide whether it changes any rule, assessment, or next action.
5. Update only the affected document.
6. Report what changed and what remains unresolved.

## Recommended File Template For Future Projects

| File | Purpose |
|---|---|
| `0000 START HERE — PROJECT CHARTER` | Governance, scope, source-of-truth rules, file registry, update rules |
| `0001 LIVE ASSESSMENT` | Current working synthesis, status, decisions, product/case/person/topic assessments |
| `0002 SOURCE LOG` | Raw notes, quotes, claims, source provenance, screenshots, links |
| `0003 RULES / DECISION FRAMEWORK` | Verified principles, rules, criteria, legal standards, scientific rules, business rules |
| `0004 OPEN QUESTIONS` | Unresolved issues, missing facts, research needs, blocked items |
| `001A+ EVIDENCE PACKETS` | Individual products, documents, people, claims, vendors, events, or source files |
| `9999 CHANGELOG` | Optional revision history when the project becomes complex |

## Input Rules That Make Codex Faster

### Use Stable Labels

Use labels like:

- `001A`
- `001B`
- `001PS`
- `001UO`
- `001DX`
- `001GD`
- `001RL`
- `001CL`

Stable labels help the model reference items without renaming them every time.

### Tell The Model What Each File Is For

Useful labels:

- `evidence`
- `snapshot`
- `living document`
- `source log`
- `draft`
- `final`
- `archive`
- `do not edit`
- `canonical`

### Add Source Warnings Early

If something looks wrong, say it plainly:

- “Amazon may have copied the wrong ingredient list.”
- “This is a screenshot, not text.”
- “This is my paraphrase, not a quote.”
- “This file is historical, not current.”
- “This version may be stale.”

These notes save huge amounts of cleanup later.

### Give The First Task A Finish Line

Instead of:

> Help me organize this project.

Use:

> Create the project charter, classify these files, identify conflicts, and tell me the next three actions.

That gives the model a finish line.

## Codex-Side Workflow Standard

When developing a project like HAIRCARE, Codex should:

1. Read `0000 START HERE` first.
2. Identify canonical files and snapshots.
3. Read only the files relevant to the current task.
4. Preserve raw source claims before analyzing them.
5. Separate fact, observation, inference, recommendation, and unresolved issue.
6. Update the correct living file instead of producing loose chat-only conclusions.
7. Verify saved changes when edits are made.
8. End with a short “changed / unresolved / next” report.

## The HAIRCARE Standard

The HAIRCARE model works because it creates a disciplined but flexible system:

- It lets messy real-life input enter the project.
- It refuses to let messy input become messy conclusions.
- It keeps the original evidence intact.
- It separates what is known from what is inferred.
- It creates living documents that can evolve.
- It gives every new piece of information somewhere to go.

That is the repeatable pattern.

## One-Sentence Reusable Rule

For future projects:

> Build the container before chasing the answer: create a charter, assign each file a role, preserve evidence separately from conclusions, define the first-day win, and maintain a living source of truth with an update loop.
