# ml/unlearning/worker

**Who works here:** ml3 (unlearning methods, ladder study, escalation gate, mediator, RabbitMQ worker)

**What goes here:** The RabbitMQ worker (pika) that ships: receives unlearn requests, runs the step, returns results over the bus.

**What does not go here:** The mediator (removed from the release build).

**Rule:** edit only the folders you own. If you need a change in someone else folder, message the owner or open an issue.
