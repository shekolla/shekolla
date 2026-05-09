# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a GitHub profile repository — `README.md` is the only file and renders live at [github.com/shekolla](https://github.com/shekolla). No build steps, tests, or dependencies. After any edit, verify the result at that URL.

## README Structure

Five sections in fixed order:

1. **Header** — centered `<div>` block containing: `# Sai Kiran Shekolla`, bold title line, four `shields.io` link badges (Portfolio, LinkedIn, X, Email)
2. **What I do** — 6 domain bullets, then a `**Stack**` line followed by 11 `shields.io` tech badges
3. **Experience** — 4 roles in reverse-chronological order: Dexur → Finoramic (Figg) → Gridlex → Accenture
4. **GitHub Stats** — centered `<div>` with two side-by-side cards (main stats + top-langs)
5. **Get in touch** — plain text + email/LinkedIn/Twitter links

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
| GitHub username (`shekolla`) | Header badge for Portfolio + both stats card URLs (see below) |

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

## GitHub Stats Cards

Two cards rendered side-by-side in a centered div. Both embed the GitHub username:

```
https://github-readme-stats.vercel.app/api?username=shekolla&show_icons=true&theme=transparent&hide_border=true&count_private=true
https://github-readme-stats.vercel.app/api/top-langs/?username=shekolla&layout=compact&theme=transparent&hide_border=true
```

`theme=transparent` is intentional — it adapts to both GitHub light and dark mode. If the GitHub handle ever changes, update `username=` in both URLs.

## Commit Style

Plain imperative sentences matching the git log — no tags, no prefix brackets:

- `Update job title to Senior Software Engineer`
- `Add OpenSearch replication detail to Dexur experience`
- `Fix broken portfolio link`
