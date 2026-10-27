# Vulcis Engineering Standard

- **Development:** `develop` is the default integration branch for pre-production work. Feature/fix/docs branches are short-lived. Use PRs and Squash and merge. Do not overwrite unrelated history or force-push to reconcile branches.
- **Language:** English for technical issue/PR titles, branch names, Conventional Commits, status and field names. Portuguese may be used for scope, acceptance and explanatory documentation.
- **Projects:** one per product; `Pending` (gray), `Ready` (blue), `Active` (orange), `Review` (purple), `Done` (green). `Area` is a work domain; `Phase` is a product phase; `Milestone` is a deliverable; `Priority` is urgency. Use GitHub native Issue Types, Assignees and dependency links when available.
- **Agents:** prefer the current checkout. Extra worktrees are only for concurrent ownership or WIP protection.
- **Quality:** checks proportionate to risk; no redundant pipelines. Human acceptance normally happens at a complete release package rather than each routine PR.
- **Safety:** do not publish secrets or security vulnerabilities; preserve content and binaries when consolidating branches.
- **Repositories:** `AGENTS.md` and product-specific rules remain local. Shared templates should eventually live in the public organization-wide `vulcis/.github` repository; until that is configured, repositories may use small local fallbacks.

This is a public, concise standard. The [developer reference](https://github.com/vulcis/orqis/blob/develop/docs/engineering/development-workflow.md) contains additional product-specific details.
