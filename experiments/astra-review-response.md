A. Objective

Career OS optimizes the use of Adrien’s limited attention: meeting real work obligations, choosing where his judgment matters, and turning selected work into capabilities and credible options for a better environment.

It does not optimize task throughput, internal visibility, exhaustive knowledge capture, or automation for its own sake.

The target habitat is AI-native, capability-multiplying product engineering among strong, exploratory peers, with low friction between ideas and real use.

Local effectiveness supplies learning, credibility, and evidence. Mobility prevents those gains from becoming employer-specific lock-in. Neither is an adequate proxy for the other.

B. Challenge the decomposition

1. WorkObject is a useful envelope, but a dangerous database ambition
A meeting, project, learning gap, and Slack thread are not equivalent units of work. Treating all noticed material as durable WorkObjects would create a second inbox and eventually a project-management system.

Boundary: a WorkObject is an attention case, not a normalized representation of everything at work. Create one when Adrien needs an engagement decision or must retain a commitment. Reference underlying artifacts rather than copying them.

2. Engagement modes mix separate axes
“Minimum sufficient / normal / deep” describe depth. “Leverage / strategic” describe mechanisms or significance. A strategic item may require only a short introduction; a mandatory review may require deep attention.

Change: represent the decision directly:

recommended action, including decline, defer, or delegate
human focus and depth
timebox or stopping condition
rationale and important uncertainty
reassessment trigger, when relevant
“Strategic” and “multiplier potential” belong in the rationale, not mutually exclusive modes. The value dimensions are reasoning aids, not mandatory fields to fill out.

3. Evidence needs a narrower meaning
“Something that happened and may matter later” is effectively a general memory record. That is acceptable—but calling every entry evidence risks laundering interpretation into proof.

Keep the record, but require separation between:

Observation: what happened, when, and according to what source.
Assessment: why it might matter.
Claim limits: what it does not establish, where material.
Shipping an internal prototype does not establish adoption, causal impact, or externally usable proof.

4. Person does not earn first-class status in v0
Working relationship notes can live beside relevant commitments or meeting outcomes. A Person entity adds maintenance and dossier risk without being necessary for the initial scenarios.

Context does earn its place, but should contain only constraints and facts that change decisions—not an expanding organizational encyclopedia. Time-sensitive context needs an “as of” date.

5. The lifecycle should be optional, not procedural
The stages are distinct enough, but requiring every item to pass through all six would be a failure.

Notice can end in dismissal.
Value can end in “do this directly.”
Prepare can be unnecessary.
Extract can produce nothing.
Remember is a selective write policy, not another conversation.
Recalibration is a periodic comparison, not an additional per-item ceremony.

6. Scout and multiplier detection are checks, not subsystems
Both fit inside Value or Prepare:

Would a bounded experiment materially change the approach?
Does repeated friction justify changing the system?
Neither needs a separate agent, queue, or persistent candidate type in v0. A candidate worth acting on is simply an attention case.

7. The structurally necessary missing boundary is commitment versus accomplishment
An obligation must not disappear because extraction is lossy. Conversely, completing an obligation need not produce durable evidence.

Represent open commitments explicitly within active work: next action, due date if real, and closure condition. Do not rely on conversation recall.

8. Mobility is a lens, not an outcome the work system can fully observe
Career direction belongs in Context. Mobility dimensions guide assessment, but the work runtime cannot infer external access, readiness, or habitat quality from internal accomplishments alone.

Boundary: distinguish “this work may build a relevant capability” from “Adrien is becoming more employable.” The latter requires external calibration. Missing calibration means unknown, not automatically improving.

C. Five likely six-week failures

Failure	Type	Smallest mitigation
The assistant creates administrative work. Every request produces a questionnaire, engagement rubric, preparation plan, and extraction request. Adrien stops consulting it.	Conceptual, amplified by prompting	Default to a short recommendation. Ask only questions that could change it. Persist nothing unless it affects a future decision or commitment.
It confidently reconstructs context it never received. Manual input is incomplete; the persistent chat is treated as reliable memory. Mentor prep and priority advice become subtly wrong.	Implementation and epistemic boundary	Files are authoritative; chat is not. Identify missing decision-critical context and state assumptions. “I don’t have the prior notes” is a valid output.
Everything aligned with AI becomes strategic. The assistant flatters Adrien’s interests, justifies system-building, and makes local work sound like mobility.	Conceptual	Require a concrete outcome and plausible beneficiary. For substantial discretionary effort, identify what it displaces. Prefer a manual trial over a reusable system when recurrence or adoption is unproven.
Memory becomes either clutter or amnesia. Exhaustive capture is unreadable; aggressive lossiness drops promises and the few observations needed for learning.	Conceptual and implementation	Keep active commitments separate from the selective outcome log. Close active work explicitly. Retain only a small sample of prediction/outcome pairs for recalibration.
The system becomes another AI engineering project. Schemas, framework artifacts, runtime polishing, and prompt tuning consume the time it was meant to recover.	Implementation and incentive	No integrations or agent orchestration during the trial. Fix a setup and weekly maintenance budget in advance. If state maintenance exceeds the budget, remove fields or behaviors before adding automation.
D. Smallest coherent v0

Interface and storage
One employer-approved chat plus three small files:

Context
Career direction and relevant constraints.
Current work goals and allocations.
Decision-relevant standing facts, with dates where needed.
Active work
Short case description and source reference.
Open commitment, if any.
Current engagement recommendation.
Next action and closure condition.
Outcome log
Selective observations with dates and source references.
Assessment explicitly separated from observation.
For sampled cases: prior expectation and later outcome.
The chat is the interface, not the database. Start with manual loading and human-approved edits. If the approved runtime supports file editing, it can propose the same edits directly; correctness must not depend on that capability.

No dedicated Person store. No standalone EngagementDecision collection: embed the current decision in active work. Preserve an older decision only when useful for evaluating it.

Three behaviors
Decide: What should Adrien do, how deeply, and why?
Prepare: Supply only the context and preparation needed for that decision.
Close: Resolve commitments and propose a minimal outcome-log entry—or explicitly propose no entry.
Do, Notice, and Remember remain conceptual boundaries, not separate implementations. Scout and multiplier checks are folded into these behaviors. Workers remain optional existing tools, not v0 infrastructure.

Minimum operating contract
Adrien owns decisions and approves durable changes.
No autonomous communication, execution, or monitoring.
No reconstructed facts without supporting input.
No mandatory full rubric.
No automatic expansion into a task plan.
A substantial discretionary recommendation names its tradeoff against current work.
Preparation has a stopping rule.
Minimum test of the thesis
For a small sample of consequential cases, capture Adrien’s initial intended approach before advice and later ask:

Did the recommendation change the allocation of attention?
Was that change useful, harmful, or still uncertain?
Did preparation save reconstruction effort or reveal an important omission?
Did extraction retain something useful without creating cleanup?
Review sampled cases weekly, not every interaction. Assess immediate usefulness separately from delayed outcomes. Six weeks can test attention support and evidence capture; it cannot establish improved career mobility.

Removed: separate entity machinery, mandatory lifecycle traversal, specialized skills, and independent recalibration infrastructure.

Added: explicit commitment closure and a tiny evaluation sample. Without these, v0 can appear helpful while dropping obligations or merely producing persuasive prose.

E. Scenario tests

Scenario	Input	Decision	Adrien sees	Persist
A. Mentor meeting	Meeting purpose, available prior notes, open promises, recent work	Invest bounded preparation in one consequential question and relevant updates; identify missing history	A brief, 1–2 questions, promises to address—not a status script	New commitments; a consequential insight or introduction if one occurs
B. Unfamiliar PR	Review request, change scope, risk context, approved code-tool findings if available	Meet review responsibility; depth follows failure risk, not interest in the feature. AI inspection does not substitute for adequate human understanding	Review focus, unresolved uncertainties, and what domain study can safely be skipped	Usually nothing after closure; a concrete recurring failure if observed
C. Lightning talk	Audience, allotted time, purpose, candidate material	Choose one takeaway and cap prep; pursue collaborators only if there is a real invitation or useful next step	Talk spine, demonstration choice, stopping rule	Material follow-up or observed adoption—not presentation delivery automatically
D. Shared AI channel	Manually pasted thread and Adrien’s possible contribution	Respond only if it adds missing value; silence is valid	“Skip,” or a concise contribution with rationale	Nothing unless a commitment or meaningful collaboration results
E. Repeated AI-slop failures	Several specific examples and their consequences	First distinguish a shared cause from superficial similarity; test a narrow intervention before building a system	A bounded checklist/test experiment with an adoption and stopping condition	Source-backed pattern and trial outcome; active work only if Adrien commits
F. New technique	Current workflow, actual bottleneck, candidate technique or an explicit request to investigate	Test only if it could change the bottleneck enough to justify switching cost	A comparison question, bounded experiment, and stop condition; no invented claim of recency	Only a useful result or decision; not a permanent novelty backlog
In manual v0, D–F do not happen unless Adrien supplies the signal. That is an intentional coverage limit, not a defect to solve immediately.

F. Documentation boundary

Layer	Contents
Canonical durable documentation	Objective and non-goals; runtime/data boundaries; record semantics; behavioral contract; scenario-based acceptance tests. Keep these in one compact design contract plus a test document if useful.
Operational state	Current context, active work, selected outcomes. These change through use and are not design documentation.
System prompt / instructions	Principal-first behavior; uncertainty handling; selective persistence; preparation stopping rules; delegation and approval limits; pointers to canonical files. Do not duplicate mutable goals or relationship context here.
Derived views	Weekly attention summary, accomplishment narrative, meeting brief, provisional mobility assessment. Regenerate from state; do not make them competing sources of truth.
Use Markdown for human-inspected context and outcome records; a simple structured block or table is sufficient for active work. Do not make OKF compatibility an implementation gate unless an existing consumer requires specific fields.

Security must be a documented behavior, not merely a repo split:

Work-derived content stays in the approved work environment.
Summarizing or removing names does not automatically declassify it.
Personal-to-work imports are deliberately sanitized.
Employer-to-personal or public exports require the relevant permission and review.
Generic machinery remains subject to employer IP and open-source rules.
G. Spec-framework readiness

Ready for a tightly bounded specification, using the reduced v0 above. The existing brief is not an appropriate unconstrained framework input: it contains enough future concepts to invite an unnecessarily large implementation.

No conceptual question needs to remain blocking. Adopt these defaults in the specification:

Manual approved chat and inspectable files.
Embedded engagement decisions, not a separate decision service.
Explicit commitments and selective outcomes.
Three behaviors and the six scenario tests.
No assumption of frontier-model runtime access.
The first execution task is to test those behaviors on the actual work-approved model using synthetic scenarios. Any failure should first lead to simpler instructions or narrower responsibilities, not more agents.

Spec Kit’s value remains empirical: does it improve that handoff without generating artifacts Adrien must continually reconcile? Framework adoption itself is not a prerequisite for implementation.

H. Final verdict

Freeze and specify.

Make these five changes in the freeze:

Replace engagement-mode categories with action, human focus, depth, stopping condition, and uncertainty.
Reduce persistence to Context, Active Work, and selected Outcomes, with decisions embedded and no Person entity.
Make commitments explicit and lifecycle stages optional; never confuse lossy extraction with permission to forget obligations.
Specify the manual runtime and information boundary, including authoritative files, approved writes, and no implicit work-data export.
Add a small actual-runtime evaluation, measuring changed attention, useful preparation, and maintenance burden—not claiming six-week mobility gains.