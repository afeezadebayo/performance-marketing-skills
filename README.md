# Performance Marketing — SKILL.md files for AI agents

[![13 skills](https://img.shields.io/badge/skills-13-0b7285)](#whats-inside)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code & Codex](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free, ready-to-run **performance marketing** skills for **Claude, Claude Code, OpenAI Codex** and any agent that
reads the [Agent Skills](https://agentskills.io/specification) format. Paid search, Shopping, Meta, TikTok and
LinkedIn ads, tracking, incrementality testing, marketing mix modelling, media planning and reporting — built for
the automated bidding era. Each skill is a single `SKILL.md`: a senior practitioner's workflow — when to use it, the
inputs to ask for, a numbered process, decision rules, an output template and sources — loaded only when a task
needs it.

Part of the [Marketing Skills library](https://github.com/afeezadebayo/marketing-skills) by
[Afeez Adebayo](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/marketing/performance-marketing/)

## Install

Each skill is its own folder with a `SKILL.md`, so you can drop any folder straight into an agent.

**Claude Code**
```bash
git clone https://github.com/afeezadebayo/performance-marketing-skills.git
cp -r performance-marketing-skills/paid-media-audit ~/.claude/skills/        # all projects
# or  .claude/skills/   inside one project
```

**OpenAI Codex**
```bash
cp -r performance-marketing-skills/paid-media-audit ~/.agents/skills/         # all repos
```

**Claude.ai / Desktop** — zip a skill folder, then **Settings → Capabilities → Skills → Upload skill**
(code execution must be enabled). To bulk-load the whole category into a Claude Project, custom GPT or
knowledge base, grab the single-folder `.zip` from the
[library page](https://afeezadebayo.com/skills-md/marketing/performance-marketing/).

Then start a new session and ask your agent which skills it can use.

## What's inside

| Skill | What it does |
|---|---|
| [`paid-media-audit`](paid-media-audit/SKILL.md) | Audit paid media across eight layers, reconcile platform results with GA4, CRM and finance. The entry point. |
| [`media-planning-budgeting`](media-planning-budgeting/SKILL.md) | Build media plans and budget allocations from unit economics, response curves and channel roles. |
| [`conversion-tracking-capi`](conversion-tracking-capi/SKILL.md) | Audit and design conversion tracking: Consent Mode v2, server-side events, values, offline imports. |
| [`google-search-ads`](google-search-ads/SKILL.md) | Build and improve Google Search campaigns in the AI Max and broad-match era. |
| [`performance-max-shopping`](performance-max-shopping/SKILL.md) | Set up and improve Performance Max and Shopping: feeds, goals, asset groups, channel reporting. |
| [`meta-ads`](meta-ads/SKILL.md) | Build, audit and scale Meta ads: Advantage+, CAPI, creative volume, scaling rules, lift tests. |
| [`paid-social-tiktok-linkedin`](paid-social-tiktok-linkedin/SKILL.md) | Plan and run campaigns on TikTok, LinkedIn, Pinterest, Snapchat, Reddit and X. |
| [`ad-creative-testing`](ad-creative-testing/SKILL.md) | Build an ad creative strategy and testing system: angles, concepts, hooks and a tagged library. |
| [`landing-page-cro`](landing-page-cro/SKILL.md) | Improve landing pages for paid traffic: message match, proof, friction, speed and prioritised tests. |
| [`audience-first-party-data`](audience-first-party-data/SKILL.md) | Build first-party audiences: Customer Match, Custom Audiences, exclusions and value-based lookalikes. |
| [`incrementality-testing`](incrementality-testing/SKILL.md) | Design and read lift studies and geo experiments that show whether ads create sales. |
| [`marketing-mix-modelling`](marketing-mix-modelling/SKILL.md) | Scope, build or review an MMM with Google Meridian, Meta Robyn or PyMC-Marketing. |
| [`paid-media-reporting`](paid-media-reporting/SKILL.md) | Build reporting leadership trusts: business truth, blended MER, incrementality factors, cohorts. |

## How these skills work

Agents use *progressive disclosure*: they read each skill's `name` and `description` (~100 tokens) at the start
of a session and load the full `SKILL.md` only when your request matches — so you can install many without
filling the context window.

## Author & licence

By [**Afeez Adebayo**](https://afeezadebayo.com) — Marketing, SEO & Growth (SEO & Organic Growth at Grey, YC W22).
[LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon) · [Newsletter](https://afeezadebayo.com/newsletter/)

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — use, share and adapt, including
commercially, with credit to Afeez Adebayo and a link to the source page in each file.

<sub>Keywords: performance marketing skills, paid media, SKILL.md, Agent Skills, Claude skills, Claude Code skills,
Codex skills, AI agent skills, Google Ads, Performance Max, Meta ads, TikTok ads, LinkedIn ads, conversion tracking,
incrementality testing, marketing mix modelling, media planning, paid media reporting, landing page CRO.</sub>
