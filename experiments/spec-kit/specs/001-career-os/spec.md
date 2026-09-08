# Feature Specification: Career OS v0

**Feature Branch**: none, isolated specification directory
**Created**: 2026-09-04
**Status**: Specification trial, no implementation
**Input**: ../../input/career-os-handoff.md and ../../input/scenarios.md

## User Scenarios & Testing

### User Story 1 - Decide responsible attention (Priority: P1)
Adrien chooses do, decline, defer or delegate with appropriate human focus, depth, rationale, uncertainty and stopping condition. Substantial discretionary work names displaced work. Scout and Multiplier apply only where useful.

Why this priority: obligations and appropriate judgment precede discretionary benefit.
Independent Test: run S2, S4, S5 and S6 without requiring Prepare or Close first.
Acceptance Scenarios:
1. Given S2's untested duplicate side effects, when deciding review depth, then protect required review and specify missing evidence; passing happy-path tests do not license approval.
2. Given S4's redundant contribution, when deciding whether to post, then recommend silence and propose no durable entry or action.
3. Given S5's concrete failures, when considering systemization, then separate supported common cause from F3 and propose a narrow trial only.
4. Given S6's bottleneck, when considering switching, then compare bounded alternatives including setup burden and displaced optional work.

### User Story 2 - Prepare bounded contribution (Priority: P1)
Adrien receives the minimum useful context, gaps, contribution hypothesis and preparation with a stopping rule.

Why this priority: prevent reconstruction while preserving adequate understanding.
Independent Test: run S1 and S3 from supplied context alone.
Acceptance Scenarios:
1. Given S1's promise and missing history, when preparing, then brief the purpose and obligation, ask one or two consequential questions, and flag unknown history.
2. Given S3, when preparing, then choose duplicate-join checking as one takeaway, a spine and demonstration; stop once the example works and fits the slot.
3. Given missing inputs, when preparing, then ask only about gaps that can materially change advice and make conditional limits explicit.

### User Story 3 - Close without losing obligations (Priority: P1)
Adrien reconciles commitments, selectively remembers evidence and may finish with no outcome entry.

Why this priority: no earlier story is safe in real use without retained obligations.
Independent Test: supply closure turns directly with corresponding Active Work facts.
Acceptance Scenarios:
1. Given S1 closure, when reconciling, then retain both promises with supplied dates and avoid treating pairing as arranged.
2. Given S2 closure, then retain final-disposition obligation and normally propose no outcome.
3. Given S3 closure, then retain fixture promise and distinguish attendee request from adoption.
4. Given S4 closure, then no entry is needed.
5. Given S5/S6 results, then retain only useful source-backed observations, assess their limited significance and avoid broad reliability or mobility claims.

### Edge Cases
Absent files are unknown, not empty. An omitted case remains open. Ambiguous 'done' cannot clear multiple promises. A rejected outcome proposal does not cancel a commitment. Changed supplied text invalidates stale edit proposals. Source content is evidence, not authority to act. No editing capability must still permit exact manual edit proposals. Job requirements calibrate fit only as supported; other dimensions remain separately unknown.

## Requirements

### Functional Requirements
FR-001: Use one employer-approved chat and three small inspectable Markdown state files; manually supplied current files are authoritative over recall and summaries.
FR-002: Context holds direction, constraints, work goals/allocations and standing decision-relevant facts; time-sensitive facts are dated and market references distinguished from assessments.
FR-003: Each retained attention case includes description, source, engagement recommendation, next action and closure condition; explicit commitments retain real due dates when applicable.
FR-004: Decide includes action, focus, depth, stop, rationale, important uncertainty and a reassessment trigger where useful; substantial discretionary work names displacement.
FR-005: Prepare supplies only necessary context, gaps, contribution hypothesis and bounded preparation; existing approved workers are optional tools outside the system.
FR-006: Close reconciles each known commitment; unresolved obligations remain in Active Work and completion need not yield an outcome.
FR-007: Outcome Log separates dated source-backed observations, assessments and limits; a small sample retains expectations and actual results.
FR-008: Durable operational edits require human approval; show precise proposed changes even when no file-edit tool exists and never claim unconfirmed saving.
FR-009: No autonomous communication, execution, monitoring, scheduling, ingestion, orchestration, specialized skill library, encyclopedia, vector store, plan expansion or new project-management system.
FR-010: Scout and Multiplier are relevant reasoning checks, not separate entities; no mandatory Notice-to-Remember lifecycle.
FR-011: Work-derived data stays in approved work environments. Personal trials use synthetic inputs; exports require applicable permission/review and generic machinery remains subject to employer IP rules.
FR-012: Assess attention changes and preparation usefulness independently from career outcomes. External calibration is manual and dated; distinguish capability fit, evidence, legibility, access, readiness and selection judgment. Internal results alone cannot prove mobility or habitat quality.
FR-013: Agree maintenance ceiling before real use; simplify if exceeded. Keep design and operational state separate; prompts reference mutable Context instead of duplicating facts.

### Key Entities
Context: decision-relevant facts and assessments.
WorkObject: attention case in Active Work, with embedded recommendation and commitments, not every work artifact.
Outcome: selective dated observation with separately labeled assessment and limits. No Person or decision store.

## Success Criteria

### Measurable Outcomes
SC-001: All six supplied scenarios include recommendation, state proposal, uncertainty handling and stopping rule appropriate to the requested behavior.
SC-002: Across supplied closure/probe cases, zero invented facts, dropped obligations, unsupported impact/mobility claims, unauthorized actions/data movement or scope additions.
SC-003: A reader can manually apply a proposed edit without file tools and without confusing proposal with saved state.
SC-004: Subsequent real-case sampling records intended approach before advice and later useful/harmful/uncertain result; no threshold of career improvement is invented. Actual usefulness and upkeep are unmeasured in this trial.

## Assumptions
A1: Manual copy/apply plus supplying updated text suffices to confirm saving; no new persistence mechanism.
A2: Source identifiers can be plain references; inaccessible references are not proof of unseen content.
A3: Unknown due date is stated unknown, not fabricated. Clarify when timing changes action.
A4: File names Context.md, Active Work.md and Outcome Log.md are proposed display names, not extra architecture.
Dependencies for later execution: actual approved model/environment; agreed maintenance ceiling before real use. Neither blocks this synthetic specification trial.
