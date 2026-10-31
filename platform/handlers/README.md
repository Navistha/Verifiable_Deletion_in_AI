# platform/handlers

**Who works here:** java2 (store handlers, audit log, verdict, dashboard, erasure study)

**What goes here:** Own aggregator pom plus one sub-module per store. Each handler deletes the user, forces cleanup (vacuum, merge, compaction, eviction), then scans the whole store for the canary.

**What does not go here:** Graph store handlers (java1). Chroma and Weaviate scanning (ml1, Python). Create a weaviate/ module here only if ml1 scanning fails.

**Rule:** edit only the folders you own. If you need a change in someone else folder, message the owner or open an issue.
