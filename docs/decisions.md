# Decision log

This file records decisions that future agents are likely to otherwise rediscover or reverse.

## D001 — Scope Career OS to professional work

**Decision:** Career OS optimizes roughly the professional 40-hour side of User's life. It is not a whole-life operating system.

**Reason:** The broader life-allocation problem is valuable but too large. Career is a domain where there is a clear "there there" and where the system can be evaluated.

---

## D002 — Target habitat is explicit

**Decision:** Career direction is a first-class canonical input.

**Reason:** A system that only optimizes current-job performance could make User increasingly successful in a habitat the user ultimately wants to leave.

---

## D003 — Mobility is separate from local effectiveness

**Decision:** Internal work can be assessed for possible mobility value, but external mobility remains unknown without external calibration.

**Reason:** Local impact, promotion evidence, employability, access, and target-habitat quality are not interchangeable.

---

## D004 — One Career CoS interface

**Decision:** Use one primary Career CoS chat/interface.

**Reason:** Global career reasoning benefits from shared context. Project-specific execution remains in project/repo/research chats.

**Non-decision:** The chat itself has no special technical status. The value is in authoritative state and behavior instructions.

---

## D005 — Do not model every artifact as a durable WorkObject

**Decision:** A work object/case exists when User needs an engagement decision or a commitment must be retained.

**Reason:** Treating every meeting, Slack thread, project, doc, and idea as a normalized object creates a second inbox/project-management system.

---

## D006 — Replace engagement-mode taxonomy with direct recommendation

**Rejected:** mutually exclusive labels such as `minimum sufficient / normal / deep / leverage / strategic`.

**Decision:** Represent:
- recommended action
- human focus/depth
- timebox or stopping condition
- rationale
- material uncertainty
- reassessment trigger when useful

**Reason:** "Deep" describes depth while "strategic" describes significance; they are independent axes.

---

## D007 — Commitments and outcomes are different

**Decision:** Open commitments are explicit in Active Work and must be closed deliberately. Outcome capture is selective and may produce no entry.

**Reason:** Lossy extraction is desirable for memory but dangerous for obligations.

---

## D008 — Reduce v0 persistence to three surfaces

**Decision:** v0 stores only:
- Context
- Active Work
- Outcome Log

**Rejected for v0:**
- first-class Person store
- separate EngagementDecision collection
- general evidence database
- universal normalized work-object store

---

## D009 — Lifecycle is conceptual, not mandatory

**Decision:** Notice -> Value -> Prepare -> Do -> Extract -> Remember remains a useful reasoning model but not a required per-item workflow.

**Reason:** Mandatory traversal would create ceremony.

v0 exposes only:
- Decide
- Prepare
- Close

---

## D010 — Scout and Multiplier are checks, not subsystems

**Decision:** Fold two checks into Decide/Prepare:
- Is there a materially better/newly possible approach?
- Is repeated friction now worth systemizing?

**Rejected for v0:** separate agents, queues, candidate stores, or autonomous scanners.

---

## D011 — Person is not first-class in v0

**Decision:** Keep relationship context locally with relevant meetings, commitments, or outcomes.

**Reason:** A Person entity adds maintenance and dossier risk before there is evidence it is needed.

---

## D012 — Framework experiments are not runtime dependencies

**Decision:** Spec Kit and SPDD were tested as bounded specification methods.

**Result:** Keep the concise behavioral contract, templates, scenario checks, and useful clarification; adopt neither framework as ongoing machinery.

**Reason:** Both added some useful structure but would create duplicate live artifacts and drift.

---

## D013 — Frontier models design machinery; approved work models run it

**Decision:** Strong personal-side models may critique/decompose generic Career OS design, but employer-specific runtime must use the approved work environment.

**Reason:** Frontier-model access is not assumed at work, and work data must not cross boundaries casually.

---

## D014 — Generic repo is separate from employer state

**Decision:** This repository contains generic/personal project machinery and design history. Real employer state lives only in the approved work environment.

**Reason:** portability, confidentiality, IP boundaries, and public-repo possibility.

---

## D015 — Expand from observed friction

**Decision:** Do not implement future capabilities merely because they sound useful.

Add:
- state when repeated use shows the system should have known something
- sensors when the same missing source repeatedly matters
- skills when the same reasoning pattern repeatedly recurs
- workers when bounded work is too large for the CoS

**Reason:** User has strong system-building instincts and can overinvest in elegant machinery before need is proven.
