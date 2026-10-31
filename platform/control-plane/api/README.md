# platform/control-plane/api

**Who works here:** java1 (control plane, lineage graph, bus, reference app, Fides comparison)

**What goes here:** Deletion request API, request state machine (received, fanned out, partially done, verified, failed, expired), Flyway state tables.

**What does not go here:** Bus code or store deletion logic.

**Rule:** edit only the folders you own. If you need a change in someone else folder, message the owner or open an issue.
