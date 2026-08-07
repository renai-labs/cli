## v0.2.2 (2026-08-07)

## Changes

- feat: opencode-exact SKILL.md parsing + skill-folder permissions that mirror load access
- fix: E2E-found fixes — opencode menu contract, skill-read rotation, CLI positionals/arrays, resource-check removal
- fix: strict review pass — token kind-scoped revoke, mirror completeness marker, discriminated version.data, tag parity, monitoring captures
- fix: review hardening pass + comment sweep
- feat(cli): add 'skills pull' wrapping the one-shape data op (PR 4)
- feat: one shared SKILL.md validator (@ren/skill-md) imported by API and CLI (PR 4)
- chore(gen): regenerate SDK/MCP/CLI + adapt first-party consumers (chunk 13)


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.2.2

---

## v0.2.1 (2026-08-06)

## Changes

- fix(api,cli): audit follow-ups — pod-member 400 mapping, migration owner backfill, explicit false predicate, transactional archive sweep, stale copy
- chore(api): renumber migration to 0035 + migrate new project binding routes to role guards
- feat(clients): visibility filters replace ?scope=user across app, CLI, client-core, tui-plugin
- docs: follow the project_agent mode rename in the architect skill and CLI docs


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.2.1

---

## v0.2.0 (2026-07-30)

## Changes

- feat(cli): add 'ren org create' mirroring the web new-organization flow
- feat(cli): poll the session job in the CLI and TUI plugin


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.2.0

---

## v0.1.16 (2026-07-22)

## Changes

- feat(api): add public invitation preview endpoint
- feat(cli): add ren blueprints validate command
- fix(skill): parse SKILL.md frontmatter with real YAML


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.16

---

## v0.1.15 (2026-07-15)

## Changes

- feat(cli): wake the sandbox before attaching the TUI to a Ren session (REN-694)


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.15

---

## v0.1.14 (2026-07-05)

## Changes

- fix(release): exclude compiled binaries from cli npm tarball
- feat(cli): resolve tui plugin version from npm latest instead of hardcoding
- ci(release): add tui-plugin to release flow; pin cli plugin ref to 0.0.1
- fix(cli): make ren upgrade channel-aware (binary vs npm)
- feat(cli): one-command onboarding via curl | bash
- fix(tui): pin opencode to 1.17.9 and disable auto-update
- refactor(client-core): use global tui.json for plugin config
- fix(tui): attach session command
- feat(cli): add ren tui launcher, attach, and install commands
- refactor(client-core): move auth, client factory, and config out of the CLI
- refactor(client-core): extract the generic invokeOperation dispatcher
- refactor(client-core): generate the single OPS manifest; CLI binds to it


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.14

---

## v0.1.13 (2026-07-05)

## Changes

- fix(triggers): blast-radius fixes for nullable trigger agent
- refactor: simplify channel→meta routing per review (REN-711)
- feat(api): session execution traces endpoint for meta agent self-observability (REN-662)
- feat(api): agent-driven chat replies, Slack DMs → private Ren, drop interactivity (REN-707)
- ft(skill): add humanizer skill and enforce its rules in Vale


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.13

---

## v0.1.12 (2026-06-15)

## Changes

- fix(sandbox): make attached-environment package installs work
- feat(sandbox): bootstrap-once runtime setup + sandbox recreate kill switch


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.12

---

## v0.1.11 (2026-06-11)

## Changes

- feat(telegram): allow setting fallback sender at claim time


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.11

---

## v0.1.10 (2026-06-11)

## Changes

- feat(telegram): settings UI, account link/unlink, revoke cleanup, command re-sync
- refactor(telegram): drop the agent create_topic action


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.10

---

## v0.1.9 (2026-06-08)

## Changes

- refactor(email): flat /api/emails CRUD, rename project-email → email
- feat: default exclude deprecated resources at query schema level
- fix: run prettier after generation to eliminate formatting churn
- fix(cli): correct agent version body format in README and onboarding docs
- fix(skill): remove yaml dependency from frontmatter parsing
- chore(cli): re-sync integrations guide bundle to integrations.md
- feat(docs): integrations guide as MCP resource + ren docs integrations
- refactor(canvas): adapt flat topology spec into blueprint on the client
- refactor(cli): derive hand-written commands from a single spec
- feat(cli): ren docs — offline command tree + data-model guide
- refactor(email): domain-side viewer list + html-to-text package


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.9

---

## v0.1.8 (2026-06-05)

## Changes

- refactor(google): address review — simplify provider, drop dead surface
- feat(google): per-user Google Workspace OAuth provider (BYO app)
- feat(app): author local (stdio) MCPs in create/edit UI
- fix(cli): make shell completion return results for subcommands


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.8

---

## v0.1.7 (2026-06-01)

## Changes

- rft(github): infer the org's single installation in routes
- feat(slack): expose install/channel management via SDK + CLI
- rft(slack): install flow should return json response
- feat(cli): generate ren github commands from new SDK ops


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.7

---

## v0.1.6 (2026-06-01)

## Changes

- chore(cli): fix prettier formatting


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.6

---

## v0.1.5 (2026-05-31)

## Changes

- feat(api/cli): expose session create + OpenCode URL to CLI


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.5

---

## v0.1.4 (2026-05-27)

## Changes

- feat(agent): create agent + initial version in one call
- feat(cli): version flag, upgrade command, skill scope + publish


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.4

---

## v0.1.3 (2026-05-26)

## Changes

- feat(cli): add 'ren org list' and 'ren org switch' for post-init org switching


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.3

---

## v0.1.2 (2026-05-26)

## Changes

- refactor(session): simplify messages API
- feat(session): paginated messages API for CLI/SDK/MCP
- feat(cli): expose per-command --scope user|org flag


Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.2

---

# Changelog

## v0.1.1 (2026-05-24)

Initial public release.

- Published to npm: https://www.npmjs.com/package/@renai-labs/cli/v/0.1.1
