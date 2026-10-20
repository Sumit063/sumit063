# 👋 Hi, I’m Sumit Pandey

Backend engineer building **high-throughput, payment-grade distributed systems** in Java and Spring Boot,
with a systems and networking core: Linux, TCP/IP, TLS, DNS, and C when it needs to be close to the metal.

I care about services that are **correct under retries, observable in production, and boring to operate**.

**Open to backend / distributed systems / platform engineering roles.**

---

## 🔧 Tech Stack

**Languages** &nbsp; `Java 21` · `Python` · `SQL` · `C / C++` · `JavaScript` · `Go` · `Bash`

**Backend** &nbsp; `Spring Boot` · `Microservices` · `REST APIs` · `Kafka` · `RabbitMQ` · `Multithreading` · `Virtual Threads` · `WebSockets` · `JWT`

**Databases** &nbsp; `MySQL` · `PostgreSQL` · `Cassandra` · `Redis` · `Elasticsearch`

**Cloud & DevOps** &nbsp; `AWS (EKS, S3)` · `Kubernetes` · `Docker` · `Jenkins` · `Argo CD` · `CI/CD`

**Observability** &nbsp; `Micrometer` · `Prometheus` · `Grafana` · `Alerting` · `Incident Triage`

**Linux & Networking** &nbsp; `Linux` · `TCP/IP` · `TLS` · `DNS` · `HTTP/S` · `Socket Programming` · `epoll` · `libevent` · `Wireshark`

**AI Tooling** &nbsp; `Claude Code` · `Cursor` · `MCP` · `Agentic Workflows` · `LLM APIs` · `RAG`

---

## 🧠 What I Can Build

**Payment-grade backend services**
- Microservices that hold up at hundreds of TPS, built on Java 21, Spring Boot and MySQL
- Exactly-once behavior across retries: **idempotency keys, optimistic locking, Redis-based dedup** and rules-driven state machines
- Clean API contracts with external networks and partners, with validation, status checks and reconciliation-friendly flows

**Event-driven systems at scale**
- **Kafka** pipelines moving millions of events a day, with per-tenant topics for isolation and back-pressure
- **RabbitMQ** request–reply: sync APIs over async round trips with **virtual threads**, per-pod reply queues and **DLQ** failover
- Signed callbacks (**HMAC-SHA256**), parked-message recovery and replay, so nothing is silently lost

**Data modeling for correctness**
- **Cassandra** designs using **lightweight transactions (LWT)** for claims, stale-claim recovery and exactly-once pulls
- Relational schema design, indexing and query tuning in MySQL and PostgreSQL; Redis caching patterns done safely

**System design, end to end**
- Taking a product from requirements to **HLD/LLD**, database design and APIs, including third-party protocol integrations
- Reasoning about failure modes first: retries, timeouts, partial failures, ordering and consistency

**Production reliability & operations**
- Hunting down **race conditions, DB connection-pool exhaustion and latency spikes** in live systems
- On-call and incident triage; **Micrometer + Prometheus + Grafana** dashboards and alerts that actually page on symptoms
- Containerized services on **Kubernetes / AWS EKS**, shipped with **Jenkins** and **Argo CD**

**Networking & systems debugging**
- Root-causing issues from **Wireshark** packet captures and logs across TLS, TCP/IP, DNS and HTTP/S
- Low-level networking in C: **epoll**, non-blocking I/O, POSIX sockets, concurrent connection handling
- Tools for log analysis at **1M+ entries per session** and workflow automation that removes manual toil

**AI-assisted engineering**
- Agentic SDLC workflows across dozens of services with Claude Code, Cursor and MCP
- LLM integrations with structured outputs, embeddings and RAG, used where they add real value

---

## 🚀 Projects

| Name | Languages | Description | Repository | Open to Collaborate |
|----|----|----|----|----|
| **DevBoard** | Swift (WidgetKit) | Native macOS widgets for interview prep: LeetCode & GitHub heatmaps, daily AI-written system design / OS / networks / DBMS / infra questions with hints, resume-based questions, answers in Apple Notes | https://github.com/Sumit063/devboard | ✅ Yes |
| **Sprint Desk** | MERN | A multi-tenant issue, sprint and knowledge management platform with real-time collaboration, RBAC and workspace-level workflows | https://github.com/Sumit063/sprint-desk | ✅ Yes |
| **NetSage** | Go, React | Network traffic analysis and debugging tool focused on flows, protocol behavior and AI-assisted insights | https://github.com/Sumit063/netsage | ✅ Yes |
| **RAG Knowledge Base Assistant** | Django | Document-based Q&A with background indexing, vector search, citations and an API-first design | https://github.com/Sumit063/rag_kb | ✅ Yes |
| **Log Analyzer** | Python, PostgreSQL, React | Log analysis platform with regex pipelines, background parsing and a UI for large production logs | Private | ❌ No |
| **Feature Automation Platform** | Django | Internal automation for feature-level configuration that cuts manual ops work | Private | ❌ No |

---

## 🧪 Toolkits & Engineering Labs

Focused repositories built to explore system fundamentals and tooling.

| Name | Languages | Purpose | Repository | Open to Collaborate |
|----|----|----|----|----|
| **NetLoop** | C | Event-driven TCP server/client with libevent: non-blocking I/O, concurrent forwarding and graceful teardown | https://github.com/Sumit063/netloop | ✅ Yes |
| **MiniTrace** | C | Minimal syscall tracer to understand Linux process execution and kernel interactions | https://github.com/Sumit063/minitrace | ✅ Yes |
| **ai-core-kit** | Python, Go, Node.js | Core AI integration patterns: text generation, structured outputs, embeddings, semantic search and mini-RAG | https://github.com/Sumit063/ai-core-kit | ✅ Yes |

> This section keeps growing as I build focused, single-purpose engineering tools.

---

## 💼 Experience (Summary)

**Software Development Engineer, payments & fintech backends**
- Build and run microservices for high-volume payment and billing flows, with exactly-once guarantees across retries
- Design Kafka and RabbitMQ pipelines, Cassandra and MySQL data models, and the HLD/LLD for new products
- Own production health: on-call, incident triage, performance fixes and observability for containerized services on Kubernetes

**Software Development Engineer, network security**
- Debugged complex customer escalations across TLS, TCP/IP, DNS and HTTP/S from packet captures and logs
- Built internal automation and log-analysis tooling that cut triage and manual effort significantly

---

## 🤝 Collaboration

I’m open to collaborating on:
- Distributed systems, event-driven architectures and payment-style reliability problems
- Backend or systems projects involving networking, data pipelines or observability
- Developer tools that make debugging and understanding systems easier
- AI tooling with solid engineering foundations
- Literally anything innovative, exciting and challenging!

---

## 🔗 Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-Sumit063-181717?style=flat&logo=github)](https://github.com/Sumit063)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sumit%20Pandey-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/sumit063)
[![Instagram](https://img.shields.io/badge/Instagram-sumit063-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/sumit._063)

---

_Building practical systems. Thinking in terms of behavior, failure modes, and scale._
