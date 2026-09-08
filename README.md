# Career OS

This workspace includes the broader ChatGPT repository package and the original specification trials. See [import reconciliation](docs/import-reconciliation.md) for provenance, document authority, and differences to resolve before synthetic validation.

A small, inspectable AI-assisted system for helping User allocate professional attention well, prepare for consequential work, preserve commitments and useful outcomes, and increase mobility toward a better long-term career habitat.

## Status

**v0 is specified, not implemented.**

The next step is synthetic validation on the actual work-approved model before any monitoring, integrations, agent orchestration, or real workplace dependence.

## Core thesis

User is the scarce principal. The system should spend AI effort to reduce reconstructive work and improve attention allocation while preserving User's judgment for consequential decisions.

Career OS is **not**:
- a generic productivity system
- a second project tracker
- an autonomous manager
- a visibility/promotion gaming machine
- a life-management system
- an excuse to automate every repeated annoyance

## v0 in one picture

```text
                    Career CoS chat
                          |
          +---------------+---------------+
          |               |               |
       Context        Active Work      Outcome Log

Core behaviors:
  Decide   -> what should User do, how deeply, and why?
  Prepare  -> what context/prep is actually needed?
  Close    -> resolve commitments and retain only useful outcomes

Checks folded into those behaviors:
  Scout      -> is there a materially better/newly possible approach?
  Multiplier -> is repeated friction now worth systemizing?
```

## Source of truth

Read in this order:

1. [`docs/career-direction.md`](docs/career-direction.md)
2. [`docs/v0-contract.md`](docs/v0-contract.md)
3. [`runtime/behavior-instructions.md`](runtime/behavior-instructions.md)
4. [`evals/scenarios.md`](evals/scenarios.md)

Background and rationale:
- [`docs/background.md`](docs/background.md)
- [`docs/decisions.md`](docs/decisions.md)
- [`docs/design-principles.md`](docs/design-principles.md)

Historical experiments are under [`experiments/`](experiments/). They are evidence and archaeology, **not live requirements**.

## Development rule

> **Do not expand Career OS from brainstormed capability. Expand it from observed v0 friction or repeated opportunity.**

When using Codex/Claude/Cursor:
- preserve the frozen v0 unless a real test exposes a flaw
- prefer deleting or narrowing behavior over adding machinery
- do not reintroduce rejected abstractions without evidence
- keep employer-specific state out of this repository

## Next action

Run the synthetic scenarios against the actual work-approved model using `runtime/behavior-instructions.md`.

Only after the model passes the hard gates should the three runtime templates be instantiated in the approved work environment.
