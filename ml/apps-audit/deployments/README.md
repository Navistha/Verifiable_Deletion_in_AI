# ml/apps-audit/deployments

**Who works here:** ml1 (three real apps, canaries, vector and index scanning, early ML items in weeks 1-12)

**What goes here:** Compose files and the version lock file (pinned version, date, verified store list) for each app. Pinned versions change only through ml1.

**What does not go here:** Shared infrastructure services (infra/base.yml).

**Rule:** edit only the folders you own. If you need a change in someone else folder, message the owner or open an issue.
