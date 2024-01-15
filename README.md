# Kubernetes
Everything about Kubernetes 

## Docker vs. Kubernetes

### Docker is a container platform
### Kubernetes is a container orchestration platform.


Some problems with docker containers:
1. Single host nature of docker container
2. Autohealing
3. Autoscaling
4. Enterprise level support
Kubernetes solves all these problems. Docker is never used in production because it does not have enterprise level support.

## Kubernetes Architecture

### Control plane (Master component of Kubernetes)
-> API Server---- Exposes Kubernetes to the external world. Any request to the worker node always goes through this.
-> etcd--- acts as a backup service. Key-Value store
-> Scheduler-- responsible for scheduling your pods or resources on kubernetes.
-> Controller Manager--- 
-> Cloud Controller Manager

### Data plane (Worker component of Kubernetes)
-> Kubelet--- responsible for creating and ensuring your pods are always running.
-> Kubeproxy--- provides networking, IP adresses and load balancing for the pods.
-> Container runtime--- runs your containers





