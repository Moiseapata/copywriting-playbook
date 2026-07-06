# Copywriting Playbook — Claude-Optimized

## What This Is

A structured knowledge base of copywriting frameworks, templates, benchmarks, and strategies synthesized from transcripts of top marketers:

- **Alex Hormozi** — Value debt, $100M Leads, email tactics
- **Russell Brunson** — Hook-Story-Offer, Epiphany Bridge, webinar structure, Dream 100
- **Andre Chaperon** — Identity transformation (Frank vs Matt), Buckets, pre-framing, self-selection
- **Amy Porterfield** — Lead magnet types, golden question, profit-driven alignment
- **Sabri Suby** — Consumption optimization, loophole hooks, button delay
- **Alex Cattoni** — Landing page components, copy commandments
- **Harry Dry** — Visual-Falsifiable-Unique rules
- **Tyson 4D** — PASO framework, email writing process, client getting
- **Neville Medhora** — Copywriting as idea transfer, AI's role
- **Peep Laja** — Brand differentiation, conversion research
- **Matt Diggity (Kenyon Digital)** — How search works, keyword sweet spots, content workflow, E-E-A-T, topical authority, link building
- **Tim Cameron-Kitchen (Exposure Ninja)** — 2026 award-nominated strategies, GEO, AI search tracking, psychographic personas
- **Neil Patel** — Search Everywhere Optimization, platform decision codes, RICE prioritization
- **Semrush** — Keyword Magic Tool, gap analysis, clustering workflow
- **HubSpot (Jamal)** — Blog post structure, headline formula, SEO writing process
- **SEO Agency Owner / AI Developer** — Local SEO entity system, Core 30 structure, Claude Code AI agent pipeline

## How Claude Should Use This Repo

### 1. Always Start with `MASTER_INDEX.md`
Before answering any question, consult the index. Every concept is tagged. Find the relevant files, then read them.

### 2. Match the Framework to the Problem

| Problem | Check These Tags |
|---------|------------------|
| "My landing page isn't converting" | `#landing-pages`, `#consumption-optimization`, `#trust` |
| "My emails get low opens" | `#email`, `#curiosity`, `#subject-lines` |
| "My funnel is broken" | Run `prompts/diagnose-funnel.md` — Hook, story, or offer? |
| "I need a lead magnet" | `#lead-magnets`, start with `golden-question.md` |
| "How do I tell a story that sells?" | `#storytelling`, `#identity-transformation` |
| "What offer should I create?" | `#offer-construction`, `#value-debt` |
| "How do I write better copy?" | `#copy-rules`, `#visual-falsifiable-unique` |
| "I need email templates" | `templates/email/` directory |
| "My site doesn't show up on Google" | #seo, #fundamentals, start with `how-search-works.md` |
| "I want to find the right keywords" | #keyword-research, #semrush, start with `keyword-sweet-spot-framework.md` |
| "My pages are well-written but don't rank" | #on-page, #eeat, #content-creation |
| "How do I rank in AI (ChatGPT, Perplexity)?" | #ai-search, #geo, #search-everywhere-optimization |
| "I have a local business, how do I get visible?" | #local-seo, #entity-consistency |
| "I want to automate my SEO content creation" | #claude-skills, #ai-agent, start with `building-an-seo-content-skill.md` |
| "What's the winning SEO strategy for 2026?" | #strategy, #2026, start with `award-winning-strategies-2026.md` |

### 3. Combine Frameworks When They Reinforce Each Other
Example: Hormozi's "value debt" + Chaperon's "pre-framing" + Porterfield's "profit-driven alignment" all serve the same goal from different angles. Use them together.

### 4. Always Attribute
When pulling a specific tactic, name the source:
- "Brunson's Epiphany Bridge"
- "Harry Dry's visual-falsifiable-unique test"
- "Suby's loophole hook"

### 5. Use the Prompts Directory
The `prompts/` folder contains ready-to-execute instructions. When asked to "write a curiosity subject line," use `prompts/write-curiosity-subject-line.md` as the operational prompt.

### 6. Cite Benchmarks
When making claims about conversion rates or performance, use the data in `benchmarks/`.

## Repository Structure

copywriting-playbook/
├── README.md # This file
├── MASTER_INDEX.md # Tagged, searchable index of every concept
├── frameworks/ # Psychological models and strategic frameworks
│ ├── core-beliefs/ # 7 Beliefs, Chain of Beliefs, The Bridge, Identity
│ ├── offer-construction/ # Value Debt, New Opportunity, Stacking, Hook-Story-Offer
│ ├── attention/ # Curiosity Loopholes, Open Loops, Harry Dry's 3 Rules
│ └── trust/ # Pre-framing, Give in Public, Social Proof, Self-Selection
├── channels/ # Channel-specific tactics
│ ├── email/ # Subject lines, PAS, Welcome, Cadence, Deliverability
│ ├── landing-pages/ # 6 Components, Consumption, Button Delay, Thank You
│ ├── dm-funnels/ # Value Debt DM Sequence
│ └── webinars/ # Epiphany Bridge, What-Not-How, 3-Person Survey
├── lead-magnets/ # Strategy, types, alignment, naming
├── voice-of-customer/ # Research methods, pain extraction, avatar creation
├── prompts/ # Ready-to-execute Claude prompts
├── templates/ # Swipe-ready templates
│ ├── email/ # Welcome, Promo, Deadline, Re-engagement
│ ├── landing-page/ # Opt-in, Sales
│ └── dm/ # Value Debt DM Sequence
├── benchmarks/ # Industry conversion data
└── transcripts/ # Full cleaned source transcripts
├── seo/                            # Search Engine & AI Optimization
│   ├── fundamentals/               # How search works, 3 realities, search intent
│   ├── keyword-research/           # Sweet spot framework, Semrush method
│   ├── content-creation/           # Content workflow, E-E-A-T, on-page checklist
│   ├── topical-authority-and-links/# Clusters, link building, local SEO Core 30
│   ├── ai-search-geo/              # GEO, Search Everywhere, AI tracking
│   ├── strategy-2026/              # 5 award-winning strategies with results
│   ├── claude-skills/              # Building Claude skills for SEO content
│   └── benchmarks/                 # SEO performance data
