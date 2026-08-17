# Hi, I'm Hüseyin

Software & Site Reliability Engineer (SRE) focused on building high-performance, concurrent Go microservices and Kubernetes-native infrastructure.

---

### Core Tech Stack

* **Language:** Go (Golang) — Primary language for building concurrent, low-latency microservices.
* **Orchestration & Infrastructure:** Kubernetes, Helm, Argo CD (GitOps), Docker, Linux.
* **Observability & SRE:** Prometheus, Grafana, Alertmanager, 4 Golden Signals, Multi-Window SLO Burn Rates.
* **Development Workflow:** Terminal-driven development with Vim & CLI-first toolchains.

---

### Key Projects

* **[kube-prober](https://github.com/demirdilek/kube-prober)**
  A zero-coordination, Kubernetes-native probing engine built in Go. Features a Dual-Informer architecture (`EndpointSlice` + `StaticTarget` CRDs), stateless Rendezvous Hashing (HRW) sharding, multi-protocol health monitoring (HTTP, TCP, TLS, gRPC, DNS), and automated 4 Golden Signals telemetry with diagnostic hints for Prometheus and Alertmanager. Documented with 23 Architecture Decision Records (ADRs).

---

### Highlights & Engineering Principles

* **High Availability & Resilience:** Production-grade deployments leveraging PodDisruptionBudgets (PDB), HorizontalPodAutoscaler (HPA), and TopologySpreadConstraints.
* **Stateless Distributed Sharding:** Rendezvous Hashing across replicas to eliminate duplicate network probes under dynamic horizontal scaling.
* **GitOps-First:** Continuous Delivery and declarative cluster state reconciliation managed via Argo CD.
* **Minimalist & Hardened Runtimes:** Multi-stage `scratch` base images running non-root (`nobody`) with read-only root filesystems and dropped capabilities.

---

*Navigating Linux with Vim, one shortcut at a time.*
