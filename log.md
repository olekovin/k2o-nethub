# k2o-nethub — Change Log

> Append-only. Never edit past entries — only add new ones at the bottom.
> Template: Intent / Reason / Impact / Gate / Rollback / Status.

## 2026-07-03 — Scaffold rollout (TODO.md + log.md)

- **Intent:** Bring this repo up to the workspace scaffold convention — `TODO.md` (living) +
  `log.md` (append-only) — matching the canary rollout done in `k2o-minecraft-servers-lol`.
- **Reason:** Workspace-wide compliance audit found `TODO.md`/`log.md` missing from most repos.
  This repo is feature-stable (README-documented routing modes confirmed implemented in the
  `.rsc` scripts); found only doc/config drift (stale spec status, stale `friday-memory` mesh
  reference) worth tracking, no functional gaps.
- **Impact:** Adds `TODO.md` and `log.md` only. Does not touch `CLAUDE.md`, `.friday/manifest.yaml`,
  or any `.rsc` script — the stale `friday-memory` reference and spec-status drift are noted as
  backlog items, not fixed in this pass.
- **Gate:** 🟢 docs-only, no infra touched.
- **Rollback:** `git rm TODO.md log.md`.
- **Status:** done.
