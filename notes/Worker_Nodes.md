# Worker Nodes

## Kubelet
- Is an agent that runs on each worker node and communicates with the control plane. It ensures that containers are running in the pods as defined by the pod specifications.
## Container Runtime
- Responsible for running the containers on each worker node. Kubernetes supports several runtimes, such as Docker, containerd, or CRI-O.
## Kube-Proxy
- Manages network rules on each worker node. It maintains network connectivity and load balancing for services, ensuring that requests are routed to the appropriate pods
## Other K8s Objects
- Higher-level Kubernetes objects such as ReplicaSets, Deployments, Jobs, Services, StatefullSets, among others.

