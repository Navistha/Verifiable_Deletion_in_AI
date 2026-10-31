# platform

**Who works here:** java1 owns the parent pom. java2 owns its own modules. java1 (control plane, lineage graph, bus, reference app, Fides comparison); java2 (store handlers, audit log, verdict, dashboard, erasure study)

**What goes here:** The Java Maven multi-module build. parent pom.xml lists only top-level modules; control-plane and handlers have their own aggregator poms so one person never edits the other module list.

**What does not go here:** Python code, experiment results or study scripts.

**Rule:** edit only the folders you own. If you need a change in someone else folder, message the owner or open an issue.
