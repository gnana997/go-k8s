Authentication & Authorization:
 - Don't need to be an admin of the cluster
 - Use RBAC to provide the controller access to required resources

Autonomous Process:
 - Single Responsible Principle
 - Decoupling via event-driven messaging
 - No central indicator

Concurrency & Asynchrony:
 - Eventual consistent by design
 - Don't rely on (assume) order

Stateless vs Stateful:
 - API server (etcd) is the source of the truth
 - can use Inmemory cache via reconcilation

Defensive Programming:
 - Things will go wrong(crash)
 - No shared (wall) clock
 - Anticipate effects on the rest of the system

Side Effects:
 - Delivery and processing guarentees only within Kubernetes