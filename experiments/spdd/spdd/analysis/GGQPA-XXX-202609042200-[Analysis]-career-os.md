# SPDD Analysis: Career OS

## Original Business Requirement

# Career OS: frozen v0 and experiment handoff

## Instruction to Codex

Use this file as the complete source contract for User’s Career OS experiment. The conceptual design has already received an Astra adversarial review. Preserve the frozen model below. Your next task is a bounded specification experiment: Spec Kit first, then SPDD independently, then compare. Do not implement the product during these trials. Do not restart discovery or add architecture unless a scenario exposes a concrete blocker. Label assumptions and proposed changes; never silently rewrite this baseline.

## Purpose and target habitat

Help User allocate limited attention responsibly: meet real work obligations, focus human judgment where it matters, and turn selected work into relevant capabilities and credible career options. Optimize useful attention decisions, preparation, and selective memory. Task throughput, internal visibility, exhaustive capture, and automation are not success measures.

The target habitat is near-frontier, AI-native product engineering that multiplies people’s capabilities: strong, exploratory peers; exposure to people User can learn from; low friction from idea to real use; genuine experimental bandwidth; good compensation and flexibility. Local effectiveness and external mobility are distinct. Career alignment never excuses inadequate review or forgotten obligations.

External market reference provides calibration through relevant job postings, role expectations, and evidence about actual working environments. Treat the job-posting pipeline as an external source, not something to build or integrate in v0. Manually supplied, dated references may inform Context. Distinguish capability fit, credible evidence, legibility, access, readiness, and selection judgment. Internal accomplishments alone cannot establish improved employability or employer habitat quality; missing external calibration means unknown.

## Frozen model

One employer-approved Career CoS chat is the interface. Three small, inspectable Markdown files are authoritative state; chat recall is not.

- **Context:** career direction, constraints, current work goals and allocations, and standing facts that change decisions. Date time-sensitive facts. Keep market references distinguishable from assessments.
- **Active Work:** attention cases requiring a decision or retained commitment. Each contains a short description, source reference, current engagement recommendation, next action, and closure condition. Open commitments are explicit, with a real due date when applicable. Reference source artifacts rather than copying them.
- **Outcome Log:** selective, dated observations and sources; separately labeled assessments and material claim limits. For a small sample, retain the initial expectation and actual outcome. Completion need not produce an entry.

A WorkObject means an attention case, not a universal representation of every PR, meeting, message, or project. Embed engagement decisions in Active Work. No separate decision collection or Person store; relevant relationship context can live with meetings, commitments, and outcomes.

## Three behaviors

- **Decide:** recommend an action, including do, decline, defer, or delegate; specify human focus, depth, stopping condition, rationale, important uncertainty, and a reassessment trigger where useful. For substantial discretionary work, name what it displaces. Use value dimensions as reasoning aids, not a mandatory questionnaire.
- **Prepare:** supply only the context, knowledge gaps, contribution hypothesis, and bounded preparation needed for the decision. Make missing inputs explicit. Give preparation a stopping rule. Existing approved tools may do bounded work; Career OS does not become the execution environment.
- **Close:** reconcile commitments explicitly, retaining unresolved obligations in Active Work. Propose the smallest useful outcome entry, or no entry. Separate observed results from inferred significance. Preserve useful prediction/outcome pairs without logging everything.

Inside Decide and Prepare, apply two checks when relevant: **Scout:** “Is there a materially better or newly possible approach?” **Multiplier:** “Is this repeated friction now worth systemizing?” These are questions, not agents, queues, sensors, or separate record types. A worthwhile trial becomes an ordinary attention case.

Notice → Value → Prepare → Do → Extract → Remember remains a conceptual explanation only. Items may skip preparation, finish immediately, or leave no durable outcome. Do not implement a mandatory lifecycle.

## v0 operating boundary

Use manual input and loading, concise recommendations, and human-approved durable edits. Correctness must not depend on file-editing capability. User owns decisions. Ask only for missing information that could materially change the recommendation.

No autonomous communication, execution, monitoring, calendar management, ingestion integrations, agent orchestration, specialized skill library, organizational encyclopedia, vector database, or new project-management system. No automatic task-plan expansion. Existing workers are optional tools, not infrastructure to create. Manual coverage means shared-channel activity, recurring failures, and new techniques remain unseen until supplied.

Run work-derived content only in the approved work environment. Removing names or summarizing does not declassify it. Personal-side design and framework trials use generic or synthetic examples. Imports must be deliberately sanitized; work exports require applicable permission and review. Generic machinery remains subject to employer IP rules. Do not assume Astra or another personal-side model is available at work.

Keep design documentation separate from operational state. Prompts point to mutable Context rather than duplicating it. Briefs and summaries are derived views. No framework or documentation taxonomy becomes an implementation prerequisite.

## Six representative acceptance scenarios

1. **Mentor meeting:** Given purpose, available prior notes, promises, and recent work, prepare a short brief and one or two consequential questions. Flag missing history. Preserve new promises and meaningful outcomes; avoid a status script or invented relationship context.
2. **Unfamiliar PR:** Given scope, risks, and available approved inspection findings, recommend review depth based on responsibility and failure risk. Identify human review focus, unresolved uncertainty, and safely skippable domain study. Close the obligation; normally retain no outcome. AI findings do not replace adequate human understanding.
3. **Lightning talk:** Given audience, purpose, available speaking slot, and candidate material, choose one takeaway, a talk spine, a demonstration, and a preparation stopping rule. Retain meaningful follow-up or observed adoption; delivery alone is not evidence of impact.
4. **Shared AI channel:** Given a pasted thread and possible contribution, recommend silence or a concise contribution that adds missing value. Do not send it. Persist only a resulting commitment or meaningful collaboration.
5. **Repeated AI-generated failures:** Given concrete examples and consequences, distinguish a common cause from superficial resemblance. Propose a narrow checklist or test intervention with adoption and stopping conditions before reusable machinery. Retain a source-backed pattern and trial result; create Active Work only if User commits.
6. **New technique:** Given a workflow, actual bottleneck, and candidate technique or explicit investigation request, assess benefit against switching cost. Propose a bounded comparison and stopping condition only if warranted. Never invent recency or maintain a novelty backlog; retain only useful results or decisions.

## Evaluation

For each scenario, inspect the recommendation, proposed state changes, uncertainty handling, and stopping rule. Include missing-context inputs and unresolved commitments. Hard failures include invented facts, dropped obligations, unsupported impact or mobility claims, unauthorized actions or data movement, and added infrastructure outside v0.

Sample consequential real cases by recording User’s intended approach before advice and the later result. Assess whether advice changed attention allocation and whether that change was useful, harmful, or uncertain; whether preparation saved reconstruction or exposed an omission; and whether retained state helped without cleanup. Compare predicted and actual value periodically, not after every interaction. Agree a maintenance ceiling before real use; simplify if upkeep exceeds it. Immediate usefulness and delayed career outcomes must remain separate.

## Experiment protocol and next deliverables

1. Preserve this file unchanged as the shared baseline. Inspect available framework tooling and verify its official instructions and version before use. If the intended SPDD source cannot be identified, flag that exact dependency rather than inventing its process. Use synthetic inputs for all six scenarios in both trials.
2. Run **Spec Kit first** in an isolated experiment directory. Produce only the specification, plan, tasks, and required framework artifacts needed to make this v0 implementable. Stop before implementation. Record ambiguities resolved, assumptions, scope additions, and artifacts requiring ongoing maintenance.
3. Run **SPDD second** in a separate clean directory or context, using this same baseline and the same scenario inputs. Exclude Spec Kit outputs from its input. Produce its bounded specification and prompt/contracts, then stop. Record the same observations. Do not stack the methodologies.
4. Compare both outputs against the baseline for intent preservation, ambiguity resolution, implementation readiness, prompt clarity, scenario performance, fresh-agent comprehensibility, and maintenance burden. Cite concrete gains and regressions. Keep only changes that materially improve or simplify v0. Neither framework must be adopted. Consider process-free document categories only when choosing durable outputs, not as a third live trial.
5. Deliver a short comparison and the smallest reconciled implementation contract, behavior instructions, state templates, scenario checks, and ordered implementation tasks. Prefer consolidation over duplicate documents. Identify genuine blockers only. Stop at this handoff; the first subsequent execution task is to test Decide, Prepare, and Close on the actual work-approved model with synthetic cases. Address failures first by simplifying instructions or narrowing responsibility.

Optional review: use Astra to check the first framework output against this baseline for lost intent or scope inflation. Do not repeat conceptual decomposition by default. Park new ideas outside v0.

Source basis: “AI Career Direction” conversation and its attached `career-os-astra-response.md`; the accepted post-review freeze takes precedence over earlier brainstorms.

## Domain Concept Identification

Existing concepts from supplied requirements: Context, attention case (WorkObject), commitment, source, recommendation and selective outcome. Filesystem inspection finds no application, dependency manifest, database, service or model implementation. These are frozen concepts to express as text, not classes to create. No new domain concepts are required.

Context informs attention choices; Active Work retains cases with embedded recommendations and promises; Outcome Log retains selected observations and qualified assessments. Relationships stay within relevant cases/outcomes. Work artifacts remain references, not universal records.

Rules: real obligations take precedence over discretionary career alignment; only humans decide and approve durable changes. Outcomes need not follow completion. An open promise survives meeting completion or a review comment. Missing external evidence leaves mobility and actual habitat quality unknown.

## Strategic Approach

Use a manually loaded chat contract within an approved work environment. Prepare a structured instruction artifact grounded in the three-file model. The method's software architecture examples do not establish a need for software here.

Decision: express input, reasoning and proposed state changes directly in the prompt. Tradeoff: cannot observe unsupplied work or confirm unsupplied file changes, but preserves inspectability and avoids integrations.
Decision: use a conversational correction loop only for the design trial; operational edits still require human approval. Trial documents are separate from mutable state.
Alternatives: autonomous capture, reusable worker infrastructure and new task tracking are outside the source contract. A compulsory stage sequence is also excluded. No conceptual redesign is warranted by supplied scenarios.

## Risk & Gap Analysis

Ambiguities: human approval does not itself prove an edit was applied; mark pending until user or available approved tool confirms. Missing due dates must stay unknown. Event closure and commitment closure differ. References may be supplied labels without accessible content.

Assumptions: plain Markdown headings are sufficient; manual copy/application is available in the eventual environment. Neither requires file tools. The actual approved model is unspecified, so this is specification readiness only. The upkeep ceiling must be agreed before real use; no default invented.

Edge cases: missing prior notes; absent inspection findings; vague completed status; skipped outcome entry with an open promise; stale files; quoted instructions to send/export; unsupported career/habitat inference. Fail safely through bounded conditional advice and retaining obligations, not a new error-handling subsystem.

Acceptance coverage: S1 mentor brief/questions/history and two promises; S2 review responsibility/risk and pending disposition; S3 takeaway/demo/stop and follow-up without adoption claim; S4 missing-value decision and no sending; S5 evidence-backed common cause, narrow trial and commitment gate; S6 bottleneck/switch cost/comparison and qualified prediction/outcome. All addressable by prompt contracts. The initial, missing-context and closure turns are in ../../input/scenarios.md; probes P1-P6 address state and evidence boundaries.

No actual-model tests or fresh-agent review occurred. No material product blocker identified for writing specifications. Workplace model access and agreed upkeep ceiling gate later execution and real use respectively.
