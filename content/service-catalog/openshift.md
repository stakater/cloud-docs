# Managed OpenShift

## Overview

**Stakater Cloud Managed OpenShift** provides a fully managed, production-grade OpenShift cluster with enterprise-level security, scalability, and automation — without the operational overhead.

---

## Key Features

- **Fully Managed** – Installation, configuration, upgrades, and patching handled by Stakater.
- **Integrated Developer Tools** – Built-in CI/CD, monitoring, logging, and service mesh.
- **Security & Compliance** – Role-Based Access Control (RBAC), network policies, encryption at rest & in transit, and GDPR alignment.
- **Automated Backups** – Configurable retention policies for both control plane and workload data.
- **Scalable Resources** – Add or remove worker nodes with minimal downtime.

---

## Service Limits

| Resource Type | Default Limit | Notes |
|---------------|--------------|-------|
| Control Plane Nodes | 3 | HA-enabled |
| Worker Nodes | 3 | Can be increased upon request |
| LoadBalancer Services | 2 | Adjustable based on quota |
| Persistent Volumes | 2 TB total | Expandable |
| API Requests per Second | 500 | Adjustable for enterprise workloads |

---

## Pricing

Pricing is based on the **cluster-as-unit** model with optional add-ons.

**Base Price (per cluster/month):**

- **Small (up to 4 vCPU, 16 GB RAM per node)** – €X,XXX
- **Medium (up to 8 vCPU, 32 GB RAM per node)** – €X,XXX
- **Large (up to 16 vCPU, 64 GB RAM per node)** – €X,XXX

**Included in Base Price:**

- 1 production-grade OpenShift cluster
- Control plane management and upgrades
- 24/7 platform monitoring
- Basic support (business hours)

**Optional Add-Ons:**

- Extra worker nodes – €XXX per node/month
- Premium support (24/7 P1 coverage) – €XXX/month
- Managed database services
- GPU-enabled nodes
