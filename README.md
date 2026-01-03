
---

# Kubernetes Practice & Mini Projects

## End-to-End Kubernetes (K8s) Learning Journey with Hands-On Manifests

---

## 📌 Repository Overview

This repository documents my **complete hands-on learning journey of Kubernetes (K8s)**, focusing on:

* Core Kubernetes concepts
* YAML-based resource definitions
* Cluster-level and application-level workloads
* Storage, networking, security, and scaling
* Helm-based package management
* Real-world Kubernetes mini projects

All Kubernetes practice in this repository is executed on a **local KIND (Kubernetes in Docker) cluster**.

---

## 🎯 What This Repository Represents

* ✔ Deep hands-on Kubernetes practice
* ✔ YAML-first learning (no UI dependency)
* ✔ Cluster + workload level understanding
* ✔ Real DevOps-style experimentation
* ✔ Foundation for a future **DevOps Mega Project**

This is **not a notes-only repository** — it contains **real manifests with proper comments and structure**.

---

## 🗂 Repository Structure

```
kubernetes-practice-and-mini-projects/
│
├── kind/
│   ├── install.sh
│   └── kind-config.yaml
│
├── practice/
│   ├── apache/
│   ├── nginx/
│   ├── mysql/
│   ├── todo-react-app/
│   ├── k8s-dashboard/
│   ├── helm/
│   └── crd/
│
├── .gitignore
└── README.md
```

---

## ⚙️ KIND Cluster Setup

The `kind/` directory contains everything required to set up the Kubernetes cluster used for practice.

### Included:

* KIND installation script
* Cluster configuration YAML

All Kubernetes manifests in this repository are tested on this KIND cluster.

---

## 🧪 Practice Directory (Core Kubernetes Hands-On)

The `practice/` directory contains **multiple sub-directories**, each focused on specific Kubernetes concepts and workloads.

### Kubernetes Concepts Covered

Through these directories, the following concepts are **fully implemented using YAML manifests**:

### 🔹 Core Objects

* Namespaces
* Pods
* Labels & Selectors
* Annotations

### 🔹 Workloads

* Deployments
* ReplicaSets
* StatefulSets
* DaemonSets
* Jobs
* CronJobs

### 🔹 Networking

* Services (ClusterIP, NodePort)
* Ingress
* Cluster networking fundamentals

### 🔹 Storage

* Persistent Volumes (PV)
* Persistent Volume Claims (PVC)
* Storage Classes

### 🔹 Configuration & Secrets

* ConfigMaps
* Secrets

### 🔹 Scaling & Resource Management

* Horizontal Pod Autoscaler (HPA)
* Vertical Pod Autoscaler (VPA)
* Resource Requests & Limits
* Probes (Liveness, Readiness)
* Resource Quotas

### 🔹 Security & Access Control

* RBAC (Roles, RoleBindings, ServiceAccounts)
* Custom Resource Definitions (CRDs)

### 🔹 Package Management

* Helm charts
* Helm-based application deployment

📌 All manifests include **clear comments** explaining what each resource does.

---

## 🧱 Mini Projects Using Kubernetes

Kubernetes manifests from this repository are also used in **real application-level projects**, hosted in separate repositories.

### 🔗 Reference Projects

* **Kubernetes 3-Tier Chat Application**
  👉 [https://github.com/MrSharma151/kubernetes-3tier-chatapp](https://github.com/MrSharma151/kubernetes-3tier-chatapp)

* **Two-Tier Flask Application on Kubernetes**
  👉 [https://github.com/MrSharma151/two-tier-flask-app](https://github.com/MrSharma151/two-tier-flask-app)

These projects demonstrate **real usage of Kubernetes manifests** in application deployments.

---

## 🧠 Learning Philosophy Followed

* YAML-first Kubernetes learning
* Avoiding UI-based shortcuts
* Understanding how Kubernetes works internally
* Practicing each concept independently
* Using local clusters for safe experimentation
* Treating Kubernetes as part of a **larger DevOps ecosystem**

---

## 🚀 Future Plan (Mega Project)

This Kubernetes knowledge will be applied in a **full-scale DevOps Mega Project**, which will include:

* Terraform for infrastructure provisioning
* Azure AKS as the Kubernetes platform
* CI/CD using Jenkins
* GitHub as source control
* Monitoring & logging
* Security & governance

Kubernetes will be used as the **core application orchestration layer**.

---

## ✅ Final Notes

* No copy-paste manifests
* No UI dependency
* Hands-on YAML implementations
* Real-world Kubernetes understanding

---

⭐ If you find this repository useful, feel free to explore or star it.

---

