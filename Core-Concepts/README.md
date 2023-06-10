# Core-Concepts

- In the first section, we start with the core concepts.

- We look at the cluster architecture at a high level and then look at some of the API primitives, such as the basic concepts like Pods, ReplicaSets, Deployments followed by services.

## Cluster Architecture

- Kubernetes Architecture
- ETCD in Kubernetes
- Kube-API Server
- Controller Managers
- Kube Scheduler
- Kubelet
- Kube Proxy

---

- The purpose of Kubernetes is to host your applications in the form of containers in an automated fashion so that you can easily deploy as many instances of your application as required and easily enable communication between different services within your application.

- The Kubernetes cluster consists of a set of nodes, which may be physical or virtual, on premise or on cloud.

- The `master node` is responsible for managing the Kubernetes cluster, storing information regarding the different nodes, planning which containers goes where, monitoring the nodes and containers on them, etc ...

  - `Etcd` is a database that stores information in a key value format.