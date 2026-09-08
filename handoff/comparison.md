# Career OS specification trial comparison

Recommendation: retain the concise behavior contract, templates and scenario checks; adopt neither framework as ongoing machinery. This is a comparison of bounded, adapted specification artifacts, not evidence that one method produces better actual-model behavior.

## Basis and limitations

Spec Kit ran first, then SPDD in a separate clean directory using byte-identical baseline and scenario inputs. The assistant followed official pinned command templates after CLI setup. SPDD consumed no Spec Kit artifacts. Both trials share one author/session, so input-directory separation does not provide blind cognitive independence. Worked responses and assessments are author-generated. Actual-model performance, fresh-agent comprehension and real maintenance benefit remain unmeasured. No optional Astra review performed.

Source/version evidence and commands are in [frameworks.md](../experiments/shared/frameworks.md). SPDD source identity is a labeled assumption: the author-published Structured-Prompt-Driven Development method linked to OpenSPDD. The handoff provided no source URL. If another SPDD was intended, the second trial and comparison need rerunning. Neither CLI independently generates model responses; installed command instructions were executed by this assistant.

## Concrete gains and regressions

Intent preservation: both keep one chat, three files, embedded decisions, selective outcomes and human responsibility. Spec Kit's [FR-006 and FR-012](../experiments/spec-kit/specs/001-career-os/spec.md) make obligation and mobility limits traceable. SPDD's [Safeguards](../experiments/spdd/spdd/prompt/GGQPA-XXX-202609042200-[Docs]-career-os-contract.md) keeps these near the response contract. Neither adds a domain concept. Broad software scaffolding was explicitly adapted away in both trials; this comparison therefore tests bounded adaptations, not default unmodified use.

Ambiguity resolution: both expose the same four useful clarifications: proposal versus applied state, unknown timing, event versus obligation closure, and reference availability. Spec Kit distributes rationale across [research](../experiments/spec-kit/specs/001-career-os/research.md), [data model](../experiments/spec-kit/specs/001-career-os/data-model.md) and [chat contract](../experiments/spec-kit/specs/001-career-os/contracts/chat.md). SPDD puts the operational answer directly in Operations after an analysis. Keep explicit manual edit confirmation and unresolved-promise handling; no new architecture follows.

Implementation readiness: Spec Kit's [six ordered tasks](../experiments/spec-kit/specs/001-career-os/tasks.md) clarify sequencing and acceptance, including actual-model testing first. SPDD Operations gives four consolidated setup/validation tasks and precise conversational inputs/outputs. Neither can establish workplace readiness without the actual model or authorize real use without a maintenance agreement. Keep a single ordered task list in the reconciled contract.

Prompt clarity: SPDD's Operations makes response and edit semantics prominent, but its full canvas mixes runtime behavior with future implementation tasks. Spec Kit provides a separately loadable chat contract but repeats rules across several files. Keep a dedicated behavior instruction without setup tasks; point it to mutable Context.

Scenario coverage: [Spec Kit walkthrough](../experiments/spec-kit/scenario-walkthrough.md) and [SPDD walkthrough](../experiments/spdd/scenario-walkthrough.md) both retain two S1 promises, keep S2 disposition open, distinguish S3 requests from adoption, select S4 silence, limit S5 to supported causes/retrospective evidence, and qualify S6's single comparison. Both explicitly reject the quoted S4 send/export instruction. Missing-context variants and P1-P6 are covered. No meaningful performance difference can be claimed from these author-worked examples. Actual-model failure rate and attention benefit are unknown.

Fresh-agent comprehensibility: static dependency inspection suggests Spec Kit needs more document navigation to reconstruct rationale and operations. SPDD's canvas offers one reading surface but requires the frozen input/scenario pack for full fidelity and contains task instructions unsuitable for ordinary chat. This is an inference from document structure, not a fresh-agent test. The reconciled start point is implementation-contract.md, linking one behavior instruction and one shared scenario pack.

Maintenance burden: Spec Kit has eight feature documents plus a constitution, observations and walkthrough (11 authored artifacts, excluding inputs and generated scaffolding). SPDD has analysis and canvas plus observations and walkthrough (4 authored artifacts), with the baseline duplicated verbatim in analysis. Both would create drift if every artifact remained live. Framework CLI/scaffolding is experiment provenance only. The reconciled durable design consists of two documents; this comparison and experiment artifacts are archival. Actual upkeep has not been measured.

## Retain and discard

Retain: exact manual edit semantics, explicit commitment reconciliation, evidence/assessment/limit separation, six reusable synthetic scenario checks, and test-first ordering on the actual approved model. These clarify the accepted baseline without changing its purpose.

Discard from ongoing use: framework taxonomies, duplicated analysis/constitution/spec/data-model documents, class diagrams, software layer examples, generated commands and framework installation prerequisites. No prompt library, agent orchestration, API, schema or new project tracker. No third methodology trial was run.

Deliverable: [implementation contract, templates, checks and tasks](implementation-contract.md), plus [behavior instructions](behavior-instructions.md). Source freeze unchanged. No product implementation or operational state created. First next execution task remains testing Decide, Prepare and Close on the actual work-approved model with synthetic cases.
