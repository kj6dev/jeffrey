# Implementation Plan: Career OS v0

Date: 2026-09-04 | Spec: [spec.md](spec.md) | Branch: none

## Summary
Specify a manually operated approved chat using three Markdown files. Deliver behavior instructions, state templates and scenario checks. Product implementation is stopped at this plan/tasks handoff.

## Technical Context
Language/Version: natural-language instructions and Markdown; no programming runtime required.
Primary Dependencies: actual employer-approved model/chat for subsequent validation, manually loaded files.
Storage: Context.md, Active Work.md, Outcome Log.md in approved environment, created only during later execution.
Testing: six synthetic conversational walkthroughs and cross-scenario probes; actual-model execution pending.
Target Platform: employer-approved chat, specific model not provided and not assumed available here.
Project Type: manual interaction contract.
Performance Goals: useful attention allocation with adequate responsibility; no latency or throughput target.
Constraints: human-approved edits, explicit obligations, minimal retention, approved data boundary.
Scale/Scope: one person, three files, no new execution infrastructure.

## Constitution Check
Before research: all five principles constrain the plan. No new entities, lifecycle or integration required.
After design: data-model.md retains exactly three state files; contracts/chat.md embeds decisions and manual saving; quickstart.md requires synthetic validation before real use. Pass by document inspection, not runtime proof.

## Project Structure
Trial artifacts: spec.md, plan.md, research.md, data-model.md, contracts/chat.md, quickstart.md, tasks.md, checklists/requirements.md.
Future approved-environment deliverable: one behavior instruction document plus Context.md, Active Work.md, Outcome Log.md. Design checks are reference material, not fourth operational state.
Structure decision: no src/, API, UI, database schema, build tool or test runner. Framework templates are trial scaffolding, not a prerequisite for operation.

## Complexity Tracking
No justified baseline violations. Framework coding fields are adapted to the actual chat/manual-file boundary. Unknown model choice is a later execution dependency, not a reason to invent architecture.
