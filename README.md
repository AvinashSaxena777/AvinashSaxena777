# Hi, I'm Avinash Saxena 👋

### Software Engineer · Backend & Distributed Systems · AI/LLM Integration

I'm a software engineer with 4+ years of experience building high-throughput backend systems and distributed data pipelines — and more recently expanding into GenAI and LLM integration. I recently completed my M.S. in Artificial Intelligence at San Jose State University (GPA: 3.9), where I built an AI multi-agent research platform combining distributed systems with LLM tooling.

Currently based in **San Jose, CA** and actively looking for **Senior Software Engineer** roles focused on backend infrastructure, CI/CD, or AI/LLM integration.

---

## 🛠 Tech Stack

**Languages**
`Go` `Python` `Java` `SQL` `Shell Scripting`

**Backend & Distributed Systems**
`gRPC / Protobuf` `RabbitMQ` `Apache Kafka` `Redis` `PostgreSQL` `Django` `Spring Boot` `REST APIs`

**AI & LLM**
`LLM Tool-Calling (MCP)` `Prompt Engineering` `LangChain` `smolagents` `RAG` `PyTorch`

**Observability**
`Prometheus` `Jaeger` `Grafana` `OpenTelemetry` `ELK Stack` `pprof`

**CI/CD & Infrastructure**
`Jenkins` `Docker` `Kubernetes` `KEDA` `Bazel` `AWS (SageMaker, EC2)`

---

## 💼 Experience

### 🎓 Research Assistant — San Jose State University
`Jan 2024 – May 2025`

Built an **AI Multi-Agent Research Platform** — a distributed system for analyzing academic papers using LLM agents.

- Architected a **Go-based MCP framework** as a standardized tool-calling layer for LLM agents — handled concurrent tool requests using Goroutines, with **smolagents** on top for agent orchestration
- Applied **prompt engineering** techniques — chain of thought, few shot, and meta prompting — to improve AI agent accuracy across different paper types
- Built **Python/Django** backend with Kafka event-driven architecture — decoupled heavy AI processing from main request flow, auto-scaled Docker workers on **Kubernetes via KEDA** based on Kafka consumer lag
- Set up **Jenkins CI/CD pipelines** — automated testing, Docker image builds, and rolling deployments across all services

---

### ⚙️ Senior Software Engineer — NTT Data *(Client: Dave & Buster's)*
`Sep 2021 – Jan 2024`

Designed and built the integration layer connecting Dave & Buster's existing systems with Salesforce Cloud for real-time pricing, product configuration, and rewards processing.

- Architected **Go microservices** handling millions of daily real-time events with sub-100ms response times
- Engineered async task processing using **Goroutines and RabbitMQ** — decoupled reward syncing from checkout flow, eliminated peak-hour bottlenecks
- Executed **pprof performance profiling** — identified Goroutine leak causing memory growth under load, resolved with context timeouts — reduced CPU utilization by 25%
- Designed **gRPC/Protobuf API contracts** for inter-service communication — binary serialization significantly faster than REST/JSON at scale
- Implemented **Redis distributed caching** with event-based invalidation — reduced latency by 40%, eliminated redundant Salesforce API calls
- Contributed to **Jenkins, Docker, and Kubernetes** CI/CD workflows supporting automated deployments

---

### 🔧 Software Engineer — Deloitte *(Client: Broadcom)*
`Jan 2020 – Sep 2021`

Maintained Broadcom's License Management application — a Java Spring microservice used by hundreds of vendors globally for hardware and software license generation.

- Modified existing **Java Spring microservices** to support new external license generation flow — built mock simulation service to unblock development against unstable external API
- Built **Python data pipeline** using Pandas and ELK stack — automated vendor compliance reporting, replaced manual database queries with real-time Kibana dashboards
- Diagnosed and resolved API performance issues using **Spring Boot Actuator and JVisualVM** — identified missing indexes and cold start issues, optimized with composite indexes and warmup scripts — reduced response times by 35%
- Improved observability with **Prometheus and Jaeger** — set up metrics tracking, distributed tracing, and alerting — significantly reduced MTTR for production incidents
- Hands-on experience with **Jenkins** CI/CD pipelines across large cross-functional teams

---

## 🎓 Education

**M.S. Artificial Intelligence** — San Jose State University *(GPA: 3.9/4.0)*
`Conferred Dec 2025`
Distributed Systems · Deep Learning · NLP · Recommender Systems

**B.E. Computer Science** — SGSITS Indore, India *(GPA: 3.8/4.0)*
`2015 – 2019`

---

## 📂 Projects

### [Deepfake Audio Detection Framework](https://github.com/avinashsaxena777)
Master's thesis — built a RAG-based framework for detecting AI-generated audio using LLM inference pipelines. Engineered automated ML pipelines to process unstructured audio data for real-time verification.

### [Intelligent Autonomous Robot Patrolling](https://github.com/avinashsaxena777)
Multi-threat detection system using YOLOv8 for real-time data stream analysis. Designed AWS infrastructure via SageMaker supporting 50+ concurrent sessions with 99.9% uptime.

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-avinashsaxenaofficial-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/avinashsaxenaofficial)
[![Email](https://img.shields.io/badge/Email-avinashsaxenagrad@gmail.com-EA4335?style=flat&logo=gmail)](mailto:avinashsaxenagrad@gmail.com)
[![Location](https://img.shields.io/badge/Location-San%20Jose%2C%20CA-34A853?style=flat&logo=google-maps)](https://maps.google.com/?q=San+Jose,+CA)
