# Background and discovery corpus

This document preserves the important reasoning that led to Career OS so future agents do not have to rediscover it from chat history.

## Origin

The initial question was how User should direct learning and career growth as AI rapidly absorbs more implementation work.

The early conclusion was that generic knowledge accumulation is not enough. User gets disproportionate leverage when the user understands a domain well enough to see the solution space, tradeoffs, failure modes, and what "good" looks like, then uses AI for implementation.

This shifted the target away from "be better than AI at coding" toward:
- directing intelligence
- technical/product judgment
- building systems that multiply capability
- enterprise leverage
- career mobility

## Constraint to career

The broader life problem was intentionally set aside.

Career OS is scoped to making the best use of roughly forty professional hours per week, plus a narrow interface to external career calibration. It is not a whole-life operating system.

## Career-goal decomposition

Several apparent goals turned out to be proxies.

### Money and title

A materially larger salary matters for freedom, financial capacity, and market validation.

But formal power/title for its own sake did not survive decomposition.

When forced to choose between:
- more formal authority in a slow organization, or
- less authority in a responsive organization where good ideas move quickly,

User strongly preferred the responsive organization.

The underlying desire is closer to **agency and low idea-to-reality friction**.

### "Exciting work"

"Exciting" is ideal but not required. Making something importantly better is also satisfying.

When comparing:
- frontier experimentation
- excellent product creation
- large-scale impact

User most strongly preferred excellent creation, ideally using current or near-frontier technology.

Pure frontier exploration can be worthwhile for a bounded period even if much is discarded, but over longer periods User wants things to become real.

### Engine building / capability multiplication

A particularly strong discovery was that User enjoys building systems that make future creation easier, faster, better, or newly possible.

The board-game analogy that resonated was **engine building**.

This explains attraction to:
- reusable UI systems
- developer tooling
- AI workflows
- hooks and agent infrastructure
- systems that enable product creation

The preferred form is especially:

> **Build capability-multiplying systems to enable product creation for User and others.**

### Craft vs consequence

User enjoys elegant engineering and can overinvest heavily in it.

But elegance without consequence is unsatisfying. A beautifully designed system with little adoption feels like effort disappearing.

Impact measured merely as user count is not the primary motivator. What matters more is that the work **enters reality and changes what is possible or how people work**.

## Peer gradient and idea permeability

A major latent variable emerged: the gap between the technical conversations User wants to have and the conversations available in their current environment.

The problem is not merely "smart coworkers."

The desired environment has:
- people who regularly expose User to ideas the user does not know
- active experimentation
- frequent sharing of partial ideas, failures, techniques, papers, and prototypes
- people who remix each other's thinking
- builders who recognize useful ideas quickly and help make them real

A brilliant but siloed team would barely solve the problem.

A slightly less individually formidable team with highly porous idea flow would be far preferable.

This led to the concepts:

- **idea density** — how often the environment exposes User to valuable new ideas
- **peer gradient** — how often peers pull User beyond their current knowledge
- **idea permeability** — how freely ideas move and recombine between people

The current situation was summarized as:

> **Great problem, weak environment.**

User has created unusually aligned AI work, but the surrounding habitat remains much weaker than the work itself.

## Experimental bandwidth

Another major variable is the ability to actually practice at the frontier.

Severe constraints on:
- model access
- inference spend
- tooling
- permissions
- hardware
- autonomous execution

are not merely inconveniences. If they prevent meaningful experimentation, they restrict the profession User is trying to practice.

Efficiency work is welcome after exploration is possible. Premature rationing is different.

Experimental bandwidth is both:
- instrumental: it enables the work
- diagnostic: it reveals whether an institution genuinely believes AI is strategically transformative

## Resulting career target

The durable target is captured in `career-direction.md`.

The shortest version is:

> **Build capability-multiplying systems using current or near-frontier technology, among curious builders who continually expand User's own thinking, in an environment where promising ideas can rapidly become real.**

## Why a Career CoS

User generates more plausible ideas and projects than the user can pursue.

The system's job is therefore not to generate more work.

The chief-of-staff analogy was useful because a strong CoS:
- filters attention
- reconstructs context
- prepares the principal
- tracks commitments
- synthesizes patterns across separate work
- pushes back when the principal is allocating attention poorly

The useful abstraction is:

> **User is the scarce principal. AI should absorb work required to get them to the point where their judgment is most valuable.**

The main interface can simply be a persistent chat. Its value comes from instructions and authoritative state, not from any special chat technology.

## Initial architecture and reduction

The initial model grew into:
- WorkObjects
- EngagementDecisions
- Evidence
- Person
- Context
- Notice -> Value -> Prepare -> Do -> Extract -> Remember
- Scout
- Multiplier detector
- Recalibration

A frontier-model adversarial review was then used specifically to **reduce** the design.

The resulting v0 is intentionally smaller:
- Context
- Active Work
- Outcome Log
- Decide
- Prepare
- Close

The larger lifecycle remains useful as a conceptual model but is not a mandatory runtime process.

This reduction is important historical knowledge. Do not casually "improve" v0 back into the earlier architecture.
