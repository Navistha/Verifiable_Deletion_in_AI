# platform/control-plane/bus

**Who works here:** java1 (control plane, lineage graph, bus, reference app, Fides comparison)

**What goes here:** RabbitMQ exchanges and queues, retry with backoff, dead-letter queue, idempotency keys, the client for the ML worker.

**What does not go here:** ML worker code (that is ml3 in ml/unlearning/worker).

**Rule:** edit only the folders you own. If you need a change in someone else folder, message the owner or open an issue.
