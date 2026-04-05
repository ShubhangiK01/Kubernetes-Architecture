# Kubernetes-Architecture
Concept of Kubernetes architecture with diagrams and practical YAML examples.

## 1. Kubernetes Cluster Components:

- **Master Node / Control Plane**
  - API Server
  - etcd
  - Controller Manager
  - Scheduler

- **Worker Nodes**
  - kubelet
  - kube-proxy
  - Containers runtime
  - Pods

- **Other Concepts**
  - Pods, ReplicaSets, Deployments
  - Services, Ingress
  - ConfigMaps & Secrets
  - Horizontal Pod Autoscaler (HPA)

## 2. Architecture Diagram
See `Diagrams/` folder for YAML manifests demonstrating:
 
## 3. Example Deployments

See `examples/` folder for YAML manifests demonstrating:
- Deployment
- Service
- ConfigMap
- Horizontal Pod Autoscaler
