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
