# Hi, I'm Sai Kiran Shekolla

Senior Software Engineer. I build scalable backends, ETL pipelines, and the infra that keeps them fast and cheap. Currently at **Dexur**, working on healthcare data at scale.

[Portfolio](https://shekolla.github.io) · [LinkedIn](https://www.linkedin.com/in/shekolla/) · [X](https://x.com/ShekollaSai) · shekollasaikiran@gmail.com

## What I do

- **Scalable systems** — AWS (S3, SQS, Lambda, Kafka, Redis), PostgreSQL, OpenSearch
- **ETL & data** — Airflow + Docker pipelines, incremental loads, denormalization
- **Healthcare data** — claims, providers, outcomes; privacy and accuracy matter
- **Infra & security** — NGINX tuning, IAM/SG hardening, VPN + VPC, bastion/jumpserver for audited access
- **Cost-efficient self-hosting** — moved workloads off managed services where the math worked
- **ML/NLP** — LLMs, NER, document parsing, sentiment

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shekolla&layout=compact)

## Experience

### Dexur — Senior Software Engineer · May 2024 – Present
Healthcare data platform: analytics, search, and ingestion at scale.
- Built **Airflow + Docker** pipelines that ingest **clinical data** in many formats — parse, normalize, compute clinical metrics, flag outcomes, index into OpenSearch, and feed downstream Superset dashboards. Retries, alarms, and daily reconciliation throughout.
- Split reads onto **dedicated PostgreSQL replicas** and denormalized hot data into **OpenSearch** — aggregations dropped from seconds to sub-second.
- Tuned **Apache Superset** (caching, server-side timeouts, query rewrites) — dashboards usable under real load.
- Hardened infra with **NGINX** reverse proxy, rate limiting, IP blocking; cleaned up IAM/SG; designed VPN + VPC for client message ingestion.
- Stood up a **bastion/jumpserver-style** access layer for production — every session logged, audit-ready, cost far below managed equivalents.
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

## Get in touch

Open to collaboration and interesting problems in healthcare data, infra, or ML.
[shekollasaikiran@gmail.com](mailto:shekollasaikiran@gmail.com) · [LinkedIn](https://www.linkedin.com/in/shekolla/) · [Twitter](https://twitter.com/ShekollaSai)
