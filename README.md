<div align="center">

# Sai Kiran Shekolla

**Senior Software Engineer** · Backend · ETL Pipelines · Distributed Systems

9+ years building distributed backend systems, data pipelines, and the infra that keeps them fast and cheap.

[![Portfolio](https://img.shields.io/badge/Portfolio-000?style=flat-square&logo=github&logoColor=white)](https://shekolla.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shekolla/)
[![X](https://img.shields.io/badge/X-000?style=flat-square&logo=x&logoColor=white)](https://x.com/ShekollaSai)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:shekollasaikiran@gmail.com)

</div>

---

## What I do

- **Distributed systems & architecture** — cross-region replication, event-driven pipelines, partitioned reads, DR design
- **ETL & data pipelines** — Airflow + Docker, multi-format ingestion, incremental loads, denormalization, reconciliation at scale
- **Backend systems** — high-throughput APIs and services on AWS (S3, SQS, Lambda, Kafka, Redis), PostgreSQL, OpenSearch
- **Infra & security** — NGINX tuning, IAM/SG hardening, VPN + VPC, bastion/jumpserver access layers; cost-efficient self-hosting
- **Healthcare data** — claims, providers, outcomes at scale; privacy and accuracy as hard constraints
- **ML/NLP** — LLMs, NER, document parsing, sentiment

---

## Stack

**Languages & Frameworks** — ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)

**Data & ETL** — ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Storage** — ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)

**Cloud & Infra** — ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)

---

## Experience

### Dexur — Senior Software Engineer · May 2024 – Present
Healthcare data platform: analytics, search, and ingestion at scale.
- Built **Airflow + Docker** pipelines that ingest clinical data in many formats — parse, normalize, compute clinical metrics, flag outcomes, index into OpenSearch, and feed downstream Superset dashboards. Retries, alarms, and daily reconciliation throughout.
- Split reads onto **dedicated PostgreSQL replicas** and denormalized hot data into **OpenSearch** — aggregations dropped from seconds to sub-second.
- Tuned **Apache Superset** (caching, server-side timeouts, query rewrites) — dashboards usable under real load.
- Hardened infra with **NGINX** reverse proxy, rate limiting, IP blocking; cleaned up IAM/SG; designed VPN + VPC for client message ingestion.
- Stood up a **bastion/jumpserver-style** access layer for production — every session logged, audit-ready, cost far below managed equivalents.
- Deployed **self-hosted NetBird VPN** (WireGuard) as a Zero Trust access layer across all internal subdomains — infra dark to the public internet, SSO-gated via Google, per-user access policies, full audit trail; no licensing cost, no third-party SaaS in the data path.
- Configured **OpenSearch cross-cluster + cross-region replication** for DR.
- Event-driven pipelines on **S3, SQS, Lambda, Kafka, Redis**; automated ops with systemd, cron, CloudWatch alarms, daily reports.

### Finoramic (Figg) — Senior Software Engineer · Jun 2019 – May 2024
Personal-finance platform parsing millions of bank statements.
- **Finance chatbot** on open-source LLMs with intent + entity recognition.
- **In-house NLP engine** for financial PDFs — custom data structures, parser confidence scoring, 90–95% accuracy.
- **RealTimeGPU** — parallel GPU system for password recovery, order-of-magnitude faster.
- **PopplerLambda** — serverless document processing.
- Insurance + investment modules, profile extraction from bank statements, Golang REST wrappers, testing framework for the parser.

### Gridlex — Software Engineer · Jun 2018 – May 2019
- Correlation-based portfolio construction (Pearson + alternatives) over historical stock data.
- Algorithms for 50+ financial indicators.
- Django front-end for portfolio management.

### Accenture — Software Engineer · Mar 2017 – May 2018
- Web automation + scraping tools in Python / BeautifulSoup.

---

## Get in touch

Open to collaboration and interesting problems in distributed systems, data infra, or ML.

[shekollasaikiran@gmail.com](mailto:shekollasaikiran@gmail.com) · [LinkedIn](https://www.linkedin.com/in/shekolla/) · [Twitter](https://twitter.com/ShekollaSai)
