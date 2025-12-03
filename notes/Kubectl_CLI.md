# The Kubectl CLI
#### Interacting with Kubernetes clusters via the CLI


## kubctl
- Is the primary command-line utility for interacting with Kuvernetes cluster. It allows you to manage and control Kubernetes resources, such as pods, services, deployments, and more, by sending API requests to the Kubernetes control plane.

- kubeclt [command] [res. type][name][flags]

### Main types of commands / use-cases

- __Inspect cluster resources__: Commands such as **get**, **describe**, and **logs** can be sued to describe the state of individual resources or groups of resources. 

- **Imperative resource management:** Commands such as **run**, **scale**, **create**, and **delete** can be used to imperatively create, update and delete resources.

- **Declarative resource management:** Commands such as **apply**, and **diff** can be used to declaratively manage resources.