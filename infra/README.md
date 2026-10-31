# infra

**Who works here:** All five ids edit their own block of base.yml. java1 owns the shared block.

**What goes here:** base.yml (the single Docker Compose file) and .env.example (project name and port block per id).

**What does not go here:** Pinned compose files of the three audited apps (those live in ml/apps-audit/deployments/). Real .env files (git ignores them).

**Rule:** edit only the folders you own. If you need a change in someone else folder, message the owner or open an issue.
