# Hi, I'm Hüseyin

Software Developer building backend services and distributed systems with Go. Currently contributing to the Kubernetes ecosystem.

---

### Upstream Contributions

**Merged:**
* **sigs.k8s.io/controller-runtime:** Passes the manager logger with name `leaderelection` via context to `leaderElector.Run()`, ensuring contextual logging in client-go uses the configured manager logger. ([PR #3576](https://github.com/kubernetes-sigs/controller-runtime/pull/3576))
* **kubernetes/kubernetes:** Updated agnhost test image tag to 2.66.1 for e2e tests. ([PR #141537](https://github.com/kubernetes/kubernetes/pull/141537))

**In Review / Active:**
* **kubernetes/kubernetes (API Machinery):** Sort map keys to ensure deterministic CEL validation order in apiextensions. ([PR #143271](https://github.com/kubernetes/kubernetes/pull/143271))
* **kubernetes/kubernetes (Kubelet / Storage):** Propagate `context.Context` through storage and `nodeinfomanager` methods to ensure consistent lifecycle and cancellation control. ([PR #141726](https://github.com/kubernetes/kubernetes/pull/141726), [PR #142585](https://github.com/kubernetes/kubernetes/pull/142585))

---

### Projects

* **[kube-prober](https://github.com/demirdilek/kube-prober)**: Distributed probing service written in Go. Uses stateless target sharding with Rendezvous Hashing (HRW), concurrent workers (HTTP/HTTPS, TCP, gRPC, DNS), and automated Prometheus metrics with provisioned Grafana dashboard. Documented with Architecture Decision Records (ADRs).
  
---

### Tech Stack & Tools

* **Language:** Go (Golang)
* **Systems & Tools:** Kubernetes, Docker, Linux, Git, Helm Charts, Argo CD 
* **Environment:** Terminal workflow with Vim/Neovim, tmux, and CLI tools

---

*Focusing on clean, concurrent Go code and learning distributed systems from the inside out.*

---

Connect on [LinkedIn](https://www.linkedin.com/in/demirdilek)
