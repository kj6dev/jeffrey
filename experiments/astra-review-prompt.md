# Career OS — Canonical Brief + Astra Review Prompt

## Purpose of this file

This is the complete context and prompt for a single high-leverage review by a frontier model.

The goal is **not** to generate more ideas indiscriminately. The goal is to pressure-test a deliberately constrained design for a personal Career OS that helps User make the best use of roughly 40 work hours per week while increasing mobility toward a much better future work environment.

Treat this file as the current source of truth. Challenge it where justified, but do not expand scope casually.

---

# 1. The problem

User is an iOS/software engineer whose work has shifted substantially toward AI tooling and AI-assisted software development.

The user learns quickly, tends to develop systems and reusable abstractions, and can focus intensely for long periods. Historically, the user has often spent substantial personal time learning and experimenting with AI because their job did not give them enough access or scope to do that at work.

That has changed. The user now has meaningful AI-related work at their current job, including an unusually ambitious internal AI tooling mandate that the user helped create.

The current situation is best summarized as:

> **Great problem, weak environment.**

The work itself is increasingly aligned with what User wants to do, but the surrounding environment has major limitations:

- relatively low idea density compared with what the user wants
- relatively low permeability of ideas between peers
- heavy friction around model/tool access and AI spend
- slow organizational movement
- restricted agent/tool execution
- limited access to frontier models
- few peers who feel like true frontier collaborators

The goal is **not** merely to maximize productivity at the current employer.

The goal is to use the current job as well as possible while increasing User's ability to move into a much stronger long-term environment.

---

# 2. Target career habitat

The desired future work environment was decomposed interactively rather than guessed from a job title.

User is most drawn to:

## Work shape

- building **capability-multiplying systems**
- especially systems that help builders create better products
- AI-native developer tools, workflows, platforms, or development systems
- near-frontier technology rather than last year's standard practice
- creation over pure research
- work that becomes real and useful, not elegant artifacts that disappear unused
- systems thinking, product sense, design sense, developer experience, and technical engineering all matter

## Environment

- **high idea density**
- **high idea permeability**
- exploratory peers constantly sharing experiments, hacks, techniques, papers, failures, and prototypes
- a strong peer gradient: colleagues who regularly expose User to things the user did not know
- low friction from idea -> experiment -> prototype -> real use
- meaningful experimental bandwidth
- access to current models/tools/compute
- leadership that materially believes AI is transformative, not merely interesting
- enough freedom that inference/tooling constraints do not prevent serious experimentation

## Motivational clarifications

User does **not** primarily want:
- title for its own sake
- formal authority for its own sake
- impact measured only as number of end users
- craftsmanship divorced from consequence

The user does want:
- agency
- interesting and/or importantly better systems
- strong peers
- learning through real collaboration
- the ability to make good ideas become real
- compensation that reflects market value
- remote/flexible work is strongly desirable

A useful summary:

> **Build capability-multiplying systems using current or near-frontier technology, among curious builders who continually expand User's own thinking, in an environment where promising ideas can rapidly become real.**

---

# 3. Career mobility

Career OS must not locally optimize User into becoming extremely effective only at their current employer.

It must help improve mobility toward the target habitat.

Career mobility currently decomposes into:

- **Eligibility** — can User actually do the target jobs?
- **Evidence** — can the user prove it?
- **Legibility** — will the market recognize the evidence?
- **Access** — can the user reach the environments and people where those jobs exist?
- **Readiness** — can the user move when the right opportunity appears?
- **Selection judgment** — can the user tell whether a job actually has the habitat the user wants?

The work-side system should consume a sanitized **market reference** derived externally from job-posting analysis, but it should not itself run a job search.

---

# 4. Core design principle

User is the scarce principal.

The AI system exists to protect and amplify:
- their judgment
- their deep-focus capacity
- their ability to create
- their ability to build relationships
- their ability to learn from high-value work

The system should absorb:
- coordination
- synthesis
- preparation
- follow-through
- reconstructive context gathering
- low-value cognitive switching
- recurring administrative reasoning

The AI should **not** become a new manager that generates endless tasks or rigid schedules.

The best human corollary is a hybrid of:
- chief of staff
- executive assistant
- research analyst
- knowledge manager
- technical staff partner

But the design should not imitate those human roles literally.

---

# 5. Main interface

The primary interface is one persistent **Career CoS** conversation.

This is where User asks things like:
- What should I work on?
- How deeply should I engage with this?
- Is this worth my time?
- How should I prepare for this meeting?
- Is this recurring pain worth systemizing?
- Am I spending too much effort on low-value work?
- What am I learning?
- What evidence am I building?
- Is my current work moving me toward the environment I want?

Project-specific work happens elsewhere:
- repo chats
- coding agents
- research agents
- doc agents
- project-specific sessions

The Career CoS keeps the global career context and decides when to delegate.

---

# 6. Core lifecycle

Any meaningful item that may deserve attention can become a **WorkObject**.

Examples:
- PR
- RFC
- meeting
- Slack thread
- email
- task
- project
- idea
- opportunity
- recurring friction
- learning gap
- follow-up

The current cognitive lifecycle is:

> **Notice -> Value -> Prepare -> Do -> Extract -> Remember**

Then the system recalibrates over time.

## Notice

Notice has three major modes:

### Reactive sensing
What entered User's world?

Possible sources:
- Slack
- email
- PR/review requests
- tickets/projects
- meetings/calendar
- manual capture
- agent/session summaries

Docs and RFCs are often referenced objects rather than primary channels.

### Standing context
What makes incoming work matter?

Examples:
- company goals
- org initiatives
- team charter
- quarterly allocations
- User's quarterly goals
- promotion expectations
- active commitments
- target career direction

### Proactive sensing
What opportunity exists that nobody explicitly assigned?

Examples:
- a shared AI discussion where User could add useful context
- a recurring technical failure pattern
- a new tool or approach worth trying
- a repeated friction point worth systemizing
- an important learning gap
- a possible cross-org strategic connection
- public work patterns from highly effective coworkers that may be worth imitating

Notice should distinguish:
- silent capture
- queue for later
- interrupt now

The system should know more than it tells User.

---

# 7. Value

Value does **not** assign a simplistic priority score.

Its job is:

> **How much of User should this WorkObject get, and in what mode?**

Current value dimensions:

- obligation
- consequence if handled poorly
- trajectory alignment
- learning value
- unique contribution
- relationship leverage
- audience / visibility leverage
- multiplier potential
- cost
- opportunity cost
- career mobility value

Expected output is an **EngagementDecision**, not merely a score.

Possible engagement modes:

- minimum sufficient
- normal
- deep
- leverage
- strategic

Example output:

- mode
- time/depth hypothesis
- why
- what would make it more valuable
- what not to overinvest in
- reassessment trigger

A key principle:

> Career OS should optimize **mode of engagement**, not merely task order.

---

# 8. Prepare

Prepare answers:

> **What needs to be true before User starts doing this?**

Current subproblems:

- desired outcome
- relevant history/context
- missing knowledge
- contribution hypothesis
- what can be delegated to AI
- what requires User's judgment
- stopping rule for preparation
- what should be captured afterward

Preparation may be 3 minutes or 90 minutes.

Examples:

## Mentor meeting
Risk: underinvestment.

Prepare should reconstruct:
- prior meetings
- commitments
- recent work
- useful updates
- 1-2 high-value questions
- what this mentor can uniquely help with

## Code review
Risk: overlearning irrelevant feature internals.

Prepare should:
- reconstruct enough domain context to judge the change
- use AI to inspect surrounding code/tests/history
- focus User on architecture, correctness, maintainability, and judgment
- avoid turning every review into a full codebase-learning exercise

---

# 9. Do

Do should be thin.

Career OS should route execution rather than hover.

Possible routing:

- User does it directly
- project-specific agent handles it
- research worker handles a bounded investigation
- repo/code worker handles technical inspection
- org/context worker gathers internal context

The Career CoS should retain only enough context to know:
- why the work matters
- what the desired outcome is
- what should return afterward

---

# 10. Extract

Extract asks:

> **What changed because User did this?**

Possible outputs:

- result
- evidence
- decision
- learning
- relationship update
- opportunity
- friction
- multiplier candidate

Extract should be **aggressively lossy**.

Most work should produce little or no durable state.

The goal is not to archive everything.

---

# 11. Remember

Persistent state should be small and inspectable.

Current minimal semantic model:

## WorkObject
Anything that may deserve attention.

## EngagementDecision
How User should engage with a WorkObject right now.

## Evidence
Something that actually happened and may matter later.

## Person
Working relationship context only, not personality dossiers.

## Context
Stable or semi-stable things that make work meaningful:
- goals
- initiatives
- charters
- promotion expectations
- career direction

Important principle:

> Separate **observed facts** from **AI assessment**.

The system may change its mind about whether something was strategically important without rewriting what actually happened.

---

# 12. Recalibration

The system should compare:

> **Predicted value vs actual value**

Examples:
- mentor meetings may consistently produce more value than User predicts
- architecture RFCs may look strategic but repeatedly produce little
- certain recurring review patterns may consistently produce reusable system opportunities

This is how the system becomes personal rather than remaining generic career advice.

Two separate recalibrations matter:

## Performance recalibration
Is User getting better at selecting and executing valuable work?

## Mobility recalibration
Is User becoming more capable of entering the target career habitat?

---

# 13. Cross-cutting processes

Two processes cut across the lifecycle.

## Multiplier detector

Question:

> **Should User ever have to do this exact kind of thinking again?**

But it must resist User's tendency to overbuild systems.

The standard should be:
- repeated enough
- consequential enough
- generalizable enough

The system should be allowed to say:

> Do the stupid thing manually. Building a system is not worth it.

## Scout

Question:

> **Is there something newly possible or newly relevant that would materially improve this work or User's understanding?**

This includes:
- current AI tooling
- new frameworks
- newly practical model capabilities
- new process patterns
- new ways to decompose or automate work

It should not encourage technology tourism merely because something is novel.

---

# 14. Peer and org sensing

Potential later capability:

## Peer-pattern sensing

Lightly observe public work behavior of unusually effective coworkers:
- how they frame proposals
- when they weigh in
- how they create alignment
- how they communicate status
- how they get things adopted

Extract reusable patterns without creating creepy dossiers or personality models.

## Shared watering-hole sensing

Monitor relevant shared channels for:
- open discussions where User has useful expertise
- interesting information worth volunteering
- cross-org collaboration opportunities
- places where "have we considered X?" could be genuinely useful

The goal is not performative visibility.

The distinction is:
- useful contribution
vs
- replying everywhere to be seen

---

# 15. Market reference

User already has a job-posting ingestion/process pipeline.

That should eventually export a sanitized reference such as:

- recurring qualifications
- rising skills
- differentiators
- gaps
- target-role signals

Career OS can use that as external calibration without directly doing job search.

Example:

> This the employer project closes a competency gap that appears repeatedly in the kinds of roles User wants.

---

# 16. Public / private architecture

Potential repo split:

## Public / generic
`career-os/`

Contains:
- schemas
- prompts
- skills
- lifecycle definitions
- generic docs
- generic agent behavior

## Private employer environment
`career-os-work/`

Contains:
- company strategy
- org/team context
- Slack-derived state
- people context
- project state
- accomplishments
- work integrations

## Private personal environment
`career-os-personal/`

Contains:
- job-market model
- job-search pipeline outputs
- compensation info
- external career history

Important:
- public repo contains the machine, not employer data
- employer-confidential information must not flow into the public repo
- contributing generic code created during work may still be subject to employer IP/open-source policies

---

# 17. Minimal v0

The conceptual system is sophisticated.

The implementation should not be.

Current minimal v0:

1. shared state
2. WorkObject schema
3. EngagementDecision schema
4. Evidence schema
5. Career CoS instructions
6. Value capability
7. Prepare capability
8. Extract capability
9. manual interaction only

Explicitly **not v0**:

- Slack monitoring
- email daemon
- org-chart intelligence
- peer behavior modeling
- job-market integration
- autonomous calendar management
- complex scheduling
- vector database
- large agent graph
- elaborate UI
- giant multi-agent hierarchy

Use it manually on real work first.

Add:
- state when the system "should have known that"
- a sensor when the missing context repeatedly comes from the same source
- a skill when User keeps asking for the same reasoning pattern
- a subagent when bounded work is too large for the CoS itself

---

# 18. Agent architecture

Do **not** create separate agents merely because the human analogy includes several jobs.

Current preferred shape:

## One Career CoS
Owns:
- global state
- lifecycle
- career direction
- attention reasoning
- delegation

## Skills / capabilities
Examples:
- notice
- value
- prepare
- extract
- recalibrate
- mentor prep
- unfamiliar-code review
- only specialized after repeated use proves need

## Worker agents
Disposable, bounded:
- research
- repo/code
- org/context
- deep analysis

Workers return structured results to the CoS.

---

# 19. Documentation / process

User has been experimenting with:
- GitHub Spec Kit
- SPDD / structured prompt-driven development
- BMAD
- Spec Kitty
- a process-free documentation system based on well-known document types

Current proposed sequence:

1. canonical brief
2. one frontier-model critique
3. freeze v0 again
4. run a spec framework as an experiment
5. compare framework artifacts with User's process-free document taxonomy
6. keep only the durable documents that actually help
7. then implement with Codex/Claude/Cursor

The process-free documentation idea may be the more durable layer.

Development frameworks may be temporary exoskeletons.

---

# 20. Use of frontier models

User does **not** currently have frontier models like Astra available inside the employer environment.

Therefore:

> **Frontier models design the machinery. Work-approved models run the machinery.**

Do not assume Career OS runtime can call Astra.

A frontier model can still help with:
- decomposition
- architecture critique
- prompt design
- eval design
- specification quality
- discovering missing abstractions

The desired frontier-model use is low-volume, high-leverage reasoning.

---

# 21. Representative scenarios

Use these to test whether the design is coherent.

## Scenario A — Mentor meeting

User has a mentor meeting tomorrow.

The user tends to underprepare.

Career OS should:
- reconstruct prior meetings
- surface commitments
- identify meaningful updates
- recommend 1-2 high-value questions
- identify where the mentor has unique perspective/access
- avoid turning the meeting into a status dump

## Scenario B — Unfamiliar PR

User must review code for an Expenses feature the user does not care to master.

Career OS should:
- identify the review as a real obligation
- estimate appropriate depth
- use AI to reconstruct enough context
- focus human judgment where needed
- avoid unnecessary feature-domain study
- detect whether repeated review friction suggests a reusable system

## Scenario C — Lightning talk

User has a short presentation.

Career OS should consider:
- audience
- what should be remembered
- whether the talk can create follow-up collaborators
- whether it should demonstrate judgment rather than just output
- appropriate prep depth

## Scenario D — Shared AI channel

A discussion appears in a company-wide AI channel.

User has relevant knowledge.

Career OS should decide:
- whether the user has something genuinely useful to add
- whether the discussion connects to their target direction
- whether silence is better
- whether this is a meaningful relationship/access opportunity

## Scenario E — Repeated AI-slop PR failures

Several PRs show the same AI-generated failure mode.

Career OS should:
- detect the pattern
- create a multiplier candidate
- ask whether the repeated friction justifies a reusable review system
- avoid overbuilding before enough evidence exists

## Scenario F — New technique

User is implementing an agent workflow.

A newer approach or framework may exist.

Career OS should:
- notice the possibility
- distinguish useful new capability from novelty tourism
- decide whether learning/testing it is justified by the current work

---

# 22. Current unresolved questions

These are legitimate open questions, not invitations to generate dozens more.

1. What is the smallest useful persistent data model?
2. Which records should be Markdown/OKF-compatible vs simpler operational state?
3. How should EngagementDecision be represented?
4. What should the Career CoS system prompt contain vs external canonical files?
5. What evals demonstrate that Value/Prepare/Extract are actually helping?
6. What is the minimum viable interface for manual use?
7. What belongs in a durable process-free documentation set?
8. Does Spec Kit materially improve the implementation handoff?
9. Which capabilities should remain generic vs become specialized skills?
10. What is the right privacy/security boundary for work integrations?

Do not add more unresolved questions unless they reveal a genuine structural flaw.

---

# 23. Constraints for this review

This review should **constrain**, not expand.

Do not:
- invent a large product roadmap
- add new integrations unless they reveal a missing core abstraction
- propose dozens of agents
- optimize for novelty
- recommend a large software stack
- turn this into a generic productivity system
- turn it into a life-management system
- redesign the user's entire career
- assume access to employer-confidential data
- assume frontier models are available in the work runtime

Prefer:
- deletion
- simplification
- sharper boundaries
- better abstractions
- fewer persistent concepts
- explicit uncertainty
- testable scenarios
- the smallest coherent v0

---

# 24. Your task, Astra

Act as a **principal systems designer and adversarial reviewer**.

Your goal is to determine whether the current Career OS model is coherent enough to freeze and move into specification/implementation.

Proceed in this order.

## A. Reconstruct the objective

In your own words, state:
- what Career OS is actually optimizing
- what it is explicitly not optimizing
- what the target career habitat is
- why the system needs both local-work effectiveness and career mobility

Keep this brief.

## B. Challenge the decomposition

Inspect:
- WorkObject
- EngagementDecision
- Evidence
- Person
- Context
- Notice -> Value -> Prepare -> Do -> Extract -> Remember
- Recalibration
- Scout
- Multiplier detector
- Career direction
- Career mobility

Identify only:
- concepts that are actually duplicates
- concepts that are too broad
- concepts that are missing and structurally necessary
- boundaries that are likely to fail in practice

Do **not** propose extra abstractions merely because they are interesting.

## C. Attack v0

Assume User builds the current v0 and uses it for six weeks.

Describe the **five most likely reasons it becomes annoying, useless, misleading, or overengineered**.

For each:
- explain the failure mode
- identify whether it is conceptual or implementation-specific
- suggest the smallest mitigation

## D. Reduce the system

Produce the **smallest coherent v0** you believe can test the core thesis.

If you remove something from the current v0, explain why.

If you add something, the burden of proof is high.

## E. Test against scenarios

Run the reduced v0 conceptually against the six representative scenarios.

For each scenario:
- what enters the system
- what decision the system makes
- what User sees
- what gets persisted, if anything

Keep each scenario compact.

## F. Evaluate the documentation boundary

Advise what should be:
- canonical durable documentation
- operational state
- system prompt / agent instructions
- derived view

Do not choose a framework yet.

## G. Spec-framework readiness

State whether this design is ready to hand to a framework such as Spec Kit.

If not, identify the **smallest number of unresolved questions that truly block specification**.

## H. Final verdict

Give one of:

- **Freeze and specify**
- **Revise before specifying**
- **The model is fundamentally wrong**

Then give at most **five concrete changes** before the next step.

---

# 25. Output style

Be concise.

The user is technically sophisticated and already understands the history.

Do not:
- restate this file at length
- generate a giant roadmap
- brainstorm adjacent features
- explain obvious AI concepts
- praise the idea
- end with vague "next steps"

The purpose of your response is to **reduce uncertainty and constrain the design**.
