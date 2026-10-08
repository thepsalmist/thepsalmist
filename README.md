# Hi 👋, I'm Xavier Odhiambo

### Senior Backend & Platform Engineer · AI Engineering

Python backend systems, the platforms they run on, and the LLM features built on top of them. Seven years across SaaS, civic-tech, and data platforms. Based in Nairobi (UTC+3).

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&pause=1000&color=36BCF7&center=true&vCenter=true&width=700&lines=Python+%2B+Django+%2B+FastAPI+backend+services;LLM+orchestration%2C+RAG+pipelines%2C+self-hosted+models;Ansible%2C+Terraform%2C+Elasticsearch+clusters;Observability+with+OpenTelemetry%2C+Grafana%2C+Loki)](https://xodhiambo.com)

---

### 🧭 What I work on

**Backend systems**
- Django, DRF and FastAPI services, Celery and RabbitMQ async processing, PostgreSQL and ClickHouse query tuning and partitioning
- Integrations around messy third-party APIs: ad and analytics platforms, payment gateways with signed callbacks, idempotent retries and reconciliation

**Platform and reliability**
- Infrastructure as code with Ansible and Terraform; container migrations off VMs; CI/CD adopted across teams
- Elasticsearch cluster architecture with an acceptance benchmark harness that gates new clusters before they take live traffic
- Observability with OpenTelemetry, Grafana, Prometheus, Loki and Sentry, and the debugging that comes with it

**AI Engineering** *(LLM systems, not model training)*
- **Gated multi-stage RAG pipeline:** led an ad-quality and domain-trust classifier where cheap automated signals run first and the LLM content-quality stage (LlamaIndex, pgvector) only sees inputs worth the cost
- **Self-hosted model platform:** designed and operated an Ollama and Open WebUI platform with per-team access control, used daily by editorial and research teams for material that could not go to outside providers
- **LLM orchestration:** extended the reporting platform's orchestration layer with multi-provider routing, automatic failover and cost-aware model selection
- **MCP:** exposed service endpoints and their contracts to an MCP server, and connect MCP servers into a daily AI-assisted development workflow

---

### 💼 Experience

- **Search Atlas** · Senior Software Engineer · 2025–2026 · Django/DRF/Celery services for an SEO analytics platform, email delivery monitoring, LLM orchestration
- **Code for Africa** · Senior Software Engineer · 2022–2025 · [Mediacloud Story-Indexer](https://github.com/mediacloud/story-indexer), Wazimap-NG, Sensors.Africa, openAFRICA
- **QED Solutions** · Software Engineer · 2021–2022 · B2B procurement SaaS across African markets, AWS infrastructure, Terraform, ECS migration

---

### 📌 Featured

| Project | What it is |
|---|---|
| [es-cluster-benchmark](https://github.com/thepsalmist/es-cluster-benchmark) | Rally-based acceptance harness for new Elasticsearch clusters: indexing throughput, query latency under load, mixed read/write |
| [Mediacloud Story-Indexer](https://github.com/mediacloud/story-indexer) | Distributed news ingestion and indexing pipeline (Python, RabbitMQ, Elasticsearch); built the ingestion microservice and the dedup scheme |

---

### ✍️ Writing

Hands-on write-ups from real infrastructure work. More at [xodhiambo.com/blog](https://xodhiambo.com/blog) · [RSS](https://xodhiambo.com/blog/feed.xml)

<!-- BLOG-POST-LIST:START -->
- [How to Add OpenTelemetry Tracing to Dokku Apps with Grafana Tempo and Alloy](https://xodhiambo.com/blog/dokku-opentelemetry-tempo-tracing/)
- [How to Monitor Dokku Apps with Prometheus, Loki and Grafana (Ansible Setup)](https://xodhiambo.com/blog/dokku-monitoring-prometheus-loki-grafana/)
- [How to Set Up Dokku on Ubuntu 24.04 with Ansible (Hardened, Re-runnable Bootstrap)](https://xodhiambo.com/blog/dokku-ubuntu-ansible-bootstrap/)
- [How to Benchmark a New Elasticsearch Cluster](https://xodhiambo.com/blog/benchmark-new-elasticsearch-cluster/)
- [Elasticsearch query_string vs terms Filter: How to Find and Fix a Slow Collection Filter](https://xodhiambo.com/blog/elasticsearch-query-string-vs-terms-filter-benchmark/)
- [NordVPN on MikroTik with IKEv2: A Complete RouterOS 6.49 Setup Guide](https://xodhiambo.com/blog/nordvpn-mikrotik-ikev2-setup/)
<!-- BLOG-POST-LIST:END -->

---

### 🛠️ Stack

**Backend**

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/-Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![DRF](https://img.shields.io/badge/-DRF-A30000?style=for-the-badge&logo=django&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Celery](https://img.shields.io/badge/-Celery-37814A?style=for-the-badge&logo=celery&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white) ![ClickHouse](https://img.shields.io/badge/-ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black) ![Elasticsearch](https://img.shields.io/badge/-Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**AI Engineering**

![LlamaIndex](https://img.shields.io/badge/-LlamaIndex-000000?style=for-the-badge&logoColor=white) ![pgvector](https://img.shields.io/badge/-pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white) ![OpenRouter](https://img.shields.io/badge/-OpenRouter-6566F1?style=for-the-badge&logoColor=white) ![Ollama](https://img.shields.io/badge/-Ollama-000000?style=for-the-badge&logoColor=white) ![MCP](https://img.shields.io/badge/-MCP-191919?style=for-the-badge&logoColor=white)

**Platform**

![AWS](https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white) ![GCP](https://img.shields.io/badge/-GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/-Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

**Observability & CI/CD**

![OpenTelemetry](https://img.shields.io/badge/-OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white) ![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Sentry](https://img.shields.io/badge/-Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

---

### 🏅 Credentials

- AWS Certified Solutions Architect (Associate)
- Open-source contributor to **Django** and **CKAN**
- BSc Telecommunications Engineering, JKUAT

---

### 🤝 Open to work

Senior backend, platform and AI engineering roles: remote, Nairobi, or relocation to the UAE or Europe. Contract and consulting welcome.

[![](https://img.shields.io/badge/-Portfolio-000000?style=for-the-badge&logo=firefox&logoColor=white)](https://xodhiambo.com) [![](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/xavierodhiambo76) [![](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:xavierfrank4@gmail.com)

[![](https://github-readme-stats.vercel.app/api?username=thepsalmist&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)](https://github.com/thepsalmist)
