# 👋 Hi, I'm Jagdish Salgotra  
### Principal Engineer | Distributed Systems | Cloud-Native Architecture | Search & GenAI

I’m a Principal Engineer with 15+ years of experience designing **distributed, event-driven, and cloud-native systems** at scale.  
My work focuses on **microservices architecture**, **real-time analytics**, and **semantic search**, built with a strong emphasis on **resilience, observability, and developer velocity**.

---

### 🧰 Tech Toolbox

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-FF6B6B?style=for-the-badge&logo=argo&logoColor=white)

---

## 🧱 Featured Project – Event-Driven E-Commerce Order Fulfillment System (EDEOFS)

**Goal:** Solve inefficiencies in order fulfillment across distributed warehouses through event-driven design, ensuring low latency, zero downtime, and deep observability.

**Highlights**
- ⚙️ **Architecture:** Domain-Driven Design (DDD), Clean Architecture, microservices with Java 25 & Spring Boot 3.5.5  
- 🔄 **Concurrency:** Leveraged *Project Loom virtual threads* for scalable I/O and high throughput  
- 🧩 **Data Layer:** Postgres (transactional), MongoDB (catalogs), Redis (cache/pub-sub)  
- 🚀 **Event Streaming:** Kafka-based order lifecycle and inventory sync (100K concurrent users, 50K req/s)  
- 🌐 **API Gateway:** GraphQL for external queries; gRPC for internal service calls  
- 🛡 **Security:** Spring Security 6.5, role-based access control (customer/admin)  
- 📦 **Observability:** Prometheus · Grafana · Loki · Tempo for metrics, dashboards, logs, and traces  
- ☁️ **Deployment:** Dockerized microservices on Kubernetes (EKS/GKE) with CI/CD via GitHub Actions & ArgoCD  
- 📉 **Impact:** 40% reduction in fulfillment time, 99.99% availability, proactive alerting enabled  

**Key Modules**
| Domain | Description |
|---------|--------------|
| 🧾 User Management | Secure auth and RBAC with adaptive policies |
| 🛍 Product Catalog | Real-time search and inventory visibility |
| 🛒 Shopping Cart | Redis-backed session persistence |
| 📦 Order Fulfillment | Kafka-driven validation and inventory updates |
| 💳 Payments | Idempotent order processing with mock gateway |
| 📣 Notifications | WebSocket-based status updates |
| 📊 Admin Analytics | Grafana dashboards for real-time metrics |

> **Tech Stack:** Java 25 · Spring Boot 3.5.5 · Kafka · Redis · Postgres · MongoDB · GraphQL · gRPC · Prometheus · Grafana · Loki · Tempo · Docker · Kubernetes

---

## 🧪 Other Projects & Experiments

### 🌱 **Project Loom Demonstrator**  
Java microservice demonstrating *virtual threads* and structured concurrency — benchmarks traditional thread pools vs Loom under real load.

### ☸️ **Kubernetes Microservices Blueprint**  
Reference setup for **Spring Boot + K8s** deployments with ArgoCD, Helm, and GitHub Actions-based CI/CD.

### 🐍 **Python Monitoring Agent**  
Lightweight metrics collector pushing to Prometheus and triggering Grafana alerts; supports custom metric definitions.

### 📝 **Next.js Blog (Personal Site)**  
Static + dynamic content built with Next.js + TypeScript + MDX.  
Covers topics like **system design**, **cloud-native architecture**, and **technical leadership**.

---

## 🔭 Currently Exploring

- 🧠 **LLMs & Vector Databases:** LangChain, Pinecone, and hybrid semantic retrieval patterns  
- ⚙️ **eBPF Observability:** tracing performance bottlenecks in microservices  
- 🕸️ **Service Meshes:** Istio and Linkerd for traffic routing and zero-trust communication  
- 🧩 **High-performance data stores:** ClickHouse and ScyllaDB for analytical workloads  
- ☁️ **FinOps / Cost Optimization:** automation for workload right-sizing and scaling policies  

---

## 🧠 Engineering Philosophy

> “Scalability isn’t just about handling load — it’s about clarity, composability, and enabling teams to move fast without breaking things.”

- Build **observability-first** systems — metrics, traces, and logs are part of the design, not an afterthought.  
- Prefer **event-driven boundaries** over tightly coupled APIs — autonomy breeds reliability.  
- Strive for **operational simplicity** — automation > firefighting.  
- Lead by **mentoring, documenting, and unblocking**, not by gatekeeping.

---

## 📬 Connect

- 💼 [LinkedIn](https://linkedin.com/in/jagdishsalgotra)  
- 💻 [GitHub](https://github.com/jagdishsalgotra)  
- 📧 [jagdishsal@gmail.com](mailto:jagdishsal@gmail.com)

---

⭐ *If you find any of my work useful, feel free to fork, discuss, or collaborate — I’m always open to ideas around distributed systems, observability, and architecture design.*
