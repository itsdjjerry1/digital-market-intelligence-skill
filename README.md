# Digital Market Intelligence — Agent Skill

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](#release-notes)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A reusable **Agent Skills** package for Similarweb-style digital market research. It helps an AI agent investigate competitors, website acquisition channels, SEO opportunities, AI-search visibility, mobile apps, e-commerce demand, and potential sales leads—while clearly distinguishing verified facts, provider estimates, and analyst inference.

> **This is a research skill, not a hosted analytics platform.** It does not automatically grant access to Similarweb's proprietary datasets or reveal a site's private analytics. Provider/API access and credentials must be configured separately.

## What's included

- `digital-market-intelligence/SKILL.md` — the core agent instructions and workflows.
- `digital-market-intelligence/references/source-map.md` — guidance for choosing and evaluating data sources.
- `digital-market-intelligence/templates/market-intelligence-report.md` — a reusable report template.

## Download

- **Latest source ZIP:** use GitHub's green **Code → Download ZIP** menu on this repository.
- **Tagged package:** download `digital-market-intelligence-skill-v1.0.0.zip` from the repository's release assets when available.

## Install

1. Download and extract this repository.
2. Copy the `digital-market-intelligence` folder into an Agent Skills-compatible client that supports local skills.
3. Keep the folder name `digital-market-intelligence`; it matches the skill's frontmatter `name`.
4. Configure any data providers or tools you want the agent to use. Examples include first-party analytics exports, a licensed web-intelligence API, SEO keyword data, app-intelligence sources, or marketplace data.
5. Ask for a task, for example:

   > Benchmark `example.com` against five competitors in India over the last six months. Compare traffic sources and keyword gaps where credible data exists, assess sampled AI-search visibility, and return a prioritised 90-day growth plan. Cite sources and label estimates.

## Capabilities

- Website traffic and engagement research, when credible data is available
- Competitor and market benchmarking
- Acquisition-channel and referral analysis
- SEO, keyword-gap, and paid/organic search research
- Sampled brand mentions/citations in AI-search products
- Mobile-app, marketplace, e-commerce, and prospect-company research
- Evidence-backed opportunity prioritisation and report generation

## Evidence and safety principles

The skill is designed to:

- never fabricate visits, bounce rates, session duration, downloads, keyword volume, sales, AI citations, or market share;
- identify the provider, geography, scope, period, and estimate/measurement type for material metrics;
- mark unavailable metrics explicitly and state confidence and limitations;
- use public information, authorised APIs, licensed datasets, and user-provided data;
- avoid bypassing logins, paywalls, CAPTCHAs, access controls, rate limits, or robots restrictions;
- link claims to supporting sources and make recommendations actionable.

## License

MIT. See [LICENSE](LICENSE).

## Release notes

See [CHANGELOG.md](CHANGELOG.md).
