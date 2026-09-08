# SPDD trial observations

Second trial, separate clean directory. Product inputs: input/career-os-handoff.md and input/scenarios.md; only OpenSPDD analysis and canvas templates used. No Spec Kit artifact was opened/copied as an input to this trial. Same author/session saw the first trial, so this is directory/input separation, not a blind or statistically independent context experiment. This limitation constrains comparison claims.

Source assumption: SPDD means Wei Zhang/Jessie Jie Xia's Structured-Prompt-Driven Development, linked by its author article to gszhangwei/open-spdd. The handoff supplies no URL; if a different method was intended, this trial must be relabeled and rerun. No unidentified process invented.

Tooling: built pinned upstream CLI locally, verified version, ran init and generated only spdd-analysis and spdd-reasons-canvas for Codex. Followed their instructions in this session; no separate CLI model run. Analysis includes original baseline verbatim as required. Product generation stopped.

Resolved ambiguities: applied versus approved edits, absent facts, event versus commitment closure, and source availability. Assumptions and later model/upkeep gates are explicit in analysis. Proposed refinements: explicit pending edit status and reconcile changed input. No accepted scope additions.

Adaptations: software class diagram is descriptive of the three files, not a schema; method signatures become conversational input/output contracts. Controller/repository/exception boilerplate omitted because no codebase or software blocker exists. Reusable prompt library and sync-to-code machinery not adopted. Filename uses required fallback ticket marker; no issue tracker created. Implementation confirmation step not requested because handoff explicitly stops before implementation.

Maintenance: two core authored framework documents (analysis and canvas), plus observations and walkthrough. Analysis repeats entire baseline and could drift if maintained. Canvas combines contract and design tasks, so loading all of it operationally risks confusing instructions with future setup work; final behavior instructions should exclude setup tasks.

Concrete gain: Operations forces precise response and proposed-edit contracts. Regression risk: Entities/Structure/Operations/Norms templates strongly suggest unnecessary OO layers and exception machinery; bounded adaptations are essential for v0. No actual-model or independent fresh-agent performance is established.
