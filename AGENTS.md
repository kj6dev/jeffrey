# Career OS design and specification workspace

The hosted repository is private at `kj6dev/jeffrey` on GitHub. `develop` is the default working branch. Commit project documents, trial outputs, and import provenance. Keep `experiments/framework-sources/` untracked: it contains reproducible upstream checkouts and local binaries; pinned revisions and setup commands are documented in `experiments/shared/frameworks.md`.

`docs/` contains the broader project corpus: background, career direction, principles, decisions, v0 contract, and deferred capabilities. `runtime/` contains proposed behavior instructions and blank design templates, not live employer state. `evals/` contains the packaged validation outline. Read `docs/career-direction.md`, `docs/v0-contract.md`, `docs/decisions.md`, and `docs/import-reconciliation.md` before changing the design. Future capabilities are candidates, not authorized implementation tasks.

`imports/2026-09-08-career-os/` preserves the original ChatGPT repository ZIP, its original agent instructions as source evidence, and file hashes. Archived instructions do not override this file. The packaged runtime instructions and evaluation outline have unresolved differences from the earlier handoff; consult `docs/import-reconciliation.md` before validation. Preserve the frozen baseline when resolving them. Prefer observed failures and simpler instructions over new infrastructure; record material design decisions in `docs/decisions.md` and `CHANGELOG.md`.

`career-os-handoff.md` is the immutable source contract. Framework trials use only synthetic content. Do not load unrelated personal context into trial requirements or modify the frozen baseline.

`experiments/shared/` holds identical scenario inputs and source verification records. `experiments/spec-kit/` and `experiments/spdd/` are separate specification trials, in that order. SPDD must not consume Spec Kit outputs. `experiments/framework-sources/` contains pinned upstream tooling, not Career OS product code. `handoff/` holds reconciled design artifacts, not operational state.

Stop before product implementation. The next execution task after the handoff is synthetic Decide/Prepare/Close testing on the actual work-approved model. No operational state, autonomous communication, integrations, agents, or framework adoption is authorized by these trials. Human approval of durable state edits is a product requirement; creating synthetic design artifacts here is already authorized.
