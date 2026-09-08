# Agent instructions for this repository

This repository is the durable source of truth for Career OS.

## Before changing anything

Read:
1. `docs/career-direction.md`
2. `docs/v0-contract.md`
3. `docs/decisions.md`
4. `runtime/behavior-instructions.md`
5. `evals/scenarios.md`

## Current phase

v0 is frozen for **synthetic validation**.

Do not implement integrations, monitoring, databases, multi-agent orchestration, UI, calendar management, Slack/email ingestion, or job-search pipelines unless a later documented decision explicitly changes scope.

## Decision discipline

When asked to improve Career OS:

1. Identify the observed failure or friction.
2. Check whether the current contract can address it with simpler instructions or narrower responsibility.
3. Prefer a prompt/contract change over infrastructure.
4. Add persistent state only if the system repeatedly "should have known" something.
5. Add a skill only if the same reasoning pattern repeatedly recurs.
6. Add a sensor only if the same missing source repeatedly matters.
7. Add a worker/subagent only for bounded work too large for the CoS.
8. Record material design changes in `docs/decisions.md` and `CHANGELOG.md`.

## Hard boundaries

- The repo contains generic/personal Career OS machinery, not employer-confidential state.
- Do not infer that de-identification automatically makes work data exportable.
- Do not claim persistence unless a write is confirmed.
- Do not claim career mobility improvement without external calibration.
- Do not turn every repeated task into automation.
- Do not treat chat memory as authoritative state.

## Style

Keep artifacts concise and inspectable.
Avoid parallel sources of truth.
Prefer one canonical document over framework-generated duplication.
