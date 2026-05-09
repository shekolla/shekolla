# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a GitHub profile repository — `README.md` is the only file and renders live at [github.com/shekolla](https://github.com/shekolla). No build steps, tests, or dependencies. After any edit, verify the result at that URL.

## README Structure

Seven sections in fixed order:

1. **Header** — centered `<div>` with name, tagline (`Backend · ETL Pipelines · Distributed Systems`), one-liner positioning hook, and four `shields.io` link badges
2. **What I do** — 6 bullets ordered by theme priority: distributed systems → ETL → backend → infra → healthcare → ML/NLP (supporting skill, not core identity)
3. **Stack** — 4 categorised badge rows: Languages & Frameworks / Data & ETL / Storage / Cloud & Infra
4. **Projects** — 4 personal/OSS projects linking to github.com/shekolla repos
5. **Experience** — 4 roles in reverse-chronological order: Dexur → Finoramic (Figg) → Gridlex → Accenture
6. **Education** — BTech in Electrical & Electronics Engineering
7. **Get in touch** — plain text + email/LinkedIn/Twitter links

`---` horizontal rules separate every section.

## Content Rules

- Bullet points describe actual shipped work — no aspirational or vague claims
- Tone is terse, engineering-focused — no marketing language
- Tech must reflect real stack: AWS (S3, SQS, Lambda, Kafka, Redis), PostgreSQL, OpenSearch, Airflow, Docker, NGINX, Django, Golang, Python
- Current role: **Senior Software Engineer at Dexur**, May 2024–Present

## Fields That Must Stay In Sync

Some details appear in multiple places — update all occurrences together:

| Field | Locations |
|-------|-----------|
| Email (`shekollasaikiran@gmail.com`) | Header badge `href` + "Get in touch" link |
| LinkedIn (`/in/shekolla/`) | Header badge `href` + "Get in touch" link |
| Twitter/X (`@ShekollaSai`) | Header badge uses `x.com`; "Get in touch" uses `twitter.com` — both need updating |
| GitHub username (`shekolla`) | Header badge for Portfolio href |

## Badge Patterns

**Link badges** (header) use this pattern:
```
[![Label](https://img.shields.io/badge/Label-COLOR?style=flat-square&logo=LOGO&logoColor=white)](URL)
```

**Tech badges** (stack row) use:
```
![Label](https://img.shields.io/badge/Label-COLOR?style=flat-square&logo=LOGO&logoColor=white)
```

All badges use `style=flat-square` for consistency. The logo names follow [Simple Icons](https://simpleicons.org/) slugs (e.g. `apachekafka`, `apacheairflow`, `amazonaws`).

## Commit Style

Plain imperative sentences matching the git log — no tags, no prefix brackets:

- `Update job title to Senior Software Engineer`
- `Add OpenSearch replication detail to Dexur experience`
- `Fix broken portfolio link`
