# Framework provenance

Verified locally 2026-09-04. Baseline checksum: baseline.sha256. All trial inputs copied before specification authoring.

## Spec Kit

Official source: https://github.com/github/spec-kit
Pinned checkout: 4a7341a93d944d6efe153b71da4a1adb9c2b578c
Local CLI: specify-cli 1.0.5.dev0, Python 3.14.4. This is a development snapshot, not a claimed stable release. Templates bundled at this revision were used; no independently fetched latest template bundle.
Instructions read: README.md; templates/commands/specify.md, plan.md, tasks.md; spec, plan and constitution templates. Commands were followed as agent instructions by the current assistant. No optional extension hooks installed.
CLI invocation from workspace: `uv run --project experiments/framework-sources/spec-kit specify init experiments/spec-kit --integration codex --non-interactive`.
Version verification: same local project, `specify version`. Init log: spec-kit-init.txt.
An initial invocation used obsolete --ai/--no-git options and failed before mutation. Current help resolved it to --integration and no git extension. This illustrates why version verification matters.

## SPDD

Author-published method: https://martinfowler.com/articles/structured-prompt-driven/ (Wei Zhang and Jessie Jie Xia, published 2026-04-28). Its linked CLI repository: https://github.com/gszhangwei/open-spdd
Source identity assumption: this is the intended SPDD; handoff names acronym only. No other SPDD process substituted silently.
Pinned checkout: 59669ac18c1c0bdee76b780771ac51567a73d52c
Local CLI reports v0.0.0-20260821063729-59669ac18c1c, source-built Go binary. Commit is the reproducible identity; not claimed latest stable tag.
Built with `go build -o /Users/bryancostanza/Developer/jeffrey/experiments/framework-sources/bin/openspdd ./cmd/openspdd` from pinned checkout.
From experiments/spdd: `../framework-sources/bin/openspdd init --tool codex`, then `generate spdd-analysis --tool codex` and `generate spdd-reasons-canvas --tool codex`. No --all, generation/implementation command or global PATH edit.
Instructions read/followed: internal/templates/data/core/spdd-analysis.md and spdd-reasons-canvas.md, plus README and author method. Generated Codex skills preserve those templates. Analysis and canvas produced by current assistant, not a separate blind agent run.

## Protocol limits

Separate directories and identical baseline/scenario inputs; same author/session, not blind context isolation. Framework software defaults were adapted where they conflict with manual v0 and recorded in observations. No product code, operational state, real work data, communications or data exports. Go/uv installed local framework build dependencies; upstream source code and scaffolding are not Career OS implementation. The workspace has no product git remote and no commits/pushes were made.
