# k2o-nethub — TODO

> **Last updated:** 2026-07-03 (scaffold rollout — K2O Standardization)
> Done items live in `log.md`. This file = active + pending only.

## Active

- No open feature work found in code/scripts — `pbr`/`dgw`/`selective` routing modes described in
  `README.md` are implemented in `nethub_server_deploy.rsc` (client-gen parameters present and wired).
  Treat as stable/maintenance mode.

## Backlog (doc/config gaps, low priority)

- [ ] `.specify/specs/020-routing-modes-v2/spec.md` is still marked `Status: Draft` (created
      2026-01-21) even though the routing-modes-v2 feature it describes ships in v5.0 — sync the
      spec status to reflect reality, or fold it into an accepted/superseded spec.
- [ ] `CLAUDE.md`'s FRIDAY Service Mesh block (and `.friday/manifest.yaml`) still list `Consumes:
      friday-memory` — that MCP is decommissioned repo-wide; needs updating to the current memory
      tier model (same fix already applied to the `k2o-minecraft-servers-lol` canary repo).
- [ ] `AGENTS.md` and `.friday/` are currently untracked in the working tree — confirm intent
      (commit or gitignore) next time this repo is touched.
