# The Control Plane

## API Server
- Exposes the Kubernetes API, which is the **main** entry point for all administrative tasks(kubectl, dashboard, etc.)

## Scheduler
- Responsible for placing pods on the most suitable nodes. It selects nodes based on resource availability and other contraints.

## Controller Mananger
- Responsible for running controller processes that handle routine tasks (e.g. ReplicaSet controller, nodes controller, job controller, etc.)

- **ReplicaSet** is a controller that ensures a specified number of identical Pod replicaes are running at all times. It guarantees the availability of a workload by automatically creating or deleting Pods to match the desired replica count.

## Etcd
- Distributed key-value store that stores all cluster data, including the configuration and state of the cluster. Acts as the single source of truth for the cluster's state.

## Cloud Controller Manager (Optional)
- Enables Kubernetes to interact with the underlying cloud infrastructure. It handles tasks such as managing cloud-based load balancers, persistent storage, and node management.

