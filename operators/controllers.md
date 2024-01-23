Kubernetes comes with serveral features to make the life of a (controller) developer easier
- Scheduling and Supervision (self-healing)
- Configuration and Secret Management
- Service Discovery and Networking
- Storage Management
- (Cloud) Portability
- Declarative API Stability and extensibility (CRDs)
- AuthN and AuthZ (RBAC)
- SDKs

Depending of the complexity of the controller
- lots of primitives and objects to learn
- Optimistic concurrency in an asynchronous eventual consistent system
    - There is no now
    - The (global) state is always behind you (distributed, delayed and unknown to the local observer)
- Fast moving project