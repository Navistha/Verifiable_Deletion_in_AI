# contracts

**Who works here:** Shared folder. Every change needs approval from java1 and ml3. java1 (control plane, lineage graph, bus, reference app, Fides comparison); ml3 (unlearning methods, ladder study, escalation gate, mediator, RabbitMQ worker)

**What goes here:** The ten frozen message contracts as JSON Schemas, the OpenAPI files, one valid and one invalid example per schema, and CHANGELOG.md. Frozen as v1 in week 8; afterwards any change is a pull request with both signatures, a new version number and a CHANGELOG entry.

**What does not go here:** Implementation code. Generated classes (Java generates them in platform/common; each ML folder generates its own into an ignored _generated/ folder). Contract 11 (lineage export) is added only if another owner, for example java2 verdict, reads it; then that reader approves it with java1.

**Rule:** edit only the folders you own. If you need a change in someone else folder, message the owner or open an issue.
