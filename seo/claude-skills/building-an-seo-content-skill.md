# Building a Claude Skill for SEO Content Writing

**Source:** Anastasia (Blogger/YouTuber); [Unnamed SEO/Marketing YouTuber]
**Tags:** #seo #claude-skills #ai-workflow #automation #content-creation

## Core Concept

A Claude Skill turns Claude from "a stranger you re-explain your process to every day" into "someone who already knows exactly how you work." Unlike a one-off prompt, a skill is a specialized, packaged set of instructions — plus reference files — that Claude follows consistently across conversations without needing to be reminded of the details.

**Context on stakes:** a McKinsey study found 80% of businesses using AI get *worse* results than before, almost always because of improper setup. Correct setup is the difference between AI making you meaningfully more efficient and AI producing generic, unusable output (or, in SEO specifically, output that risks penalties).

## Skill vs. Other Claude Features

| Feature | Scope |
|---|---|
| Custom Instructions | Apply globally to every chat in the account |
| Projects | A static workspace with a fixed set of documents/instructions for one task |
| Skills | Activated on demand, in any conversation; can include reference files Claude actively reads during execution |

A skill isn't just a text prompt — it's a folder that can contain a style guide, a CSV, screenshots, or any other reference material Claude pulls from while working.

## The Three Foundational Documents

### 1. Tone of Voice Document
Describes writing style, expressions, sentence structure, and "banned" (AI-sounding) words/phrases.

**How to create it:** Don't write it from scratch — provide Claude with 3-5 samples of your actual writing and ask it to analyze them and generate the document. Takes about 2 minutes and is grounded in your real style rather than generic descriptors like "conversational."

**Best practice:** Be extremely specific. Include examples of good *and* bad sentences, and maintain a running list of hated AI-sounding phrases.

### 2. Mini Sitemap (CSV File)
A simple list of your most important pages: URL, title, short description/meta description.

**Purpose:** Tells Claude which pages exist on your site and what's on them, so it can strategically add real internal links instead of inventing them.

**Best practice:** Quality over quantity — include only key pages you actually want linked to (cornerstone content, transactional pages, core resources), not your entire sitemap.

### 3. Experience Document
A collection of personal results, case studies, examples, and screenshots (client wins, ranking screenshots, text files with stories) — can be a single compressed folder.

**Purpose:** Gives Claude the real-world data and stories needed to add credibility and E-E-A-T signal to generated content (see `content-creation/eeat-framework.md`).

**Best practice:** Use real numbers, results, and short stories — this is what adds unique credibility that generic AI content can't replicate.

## Step-by-Step Setup

1. **Prerequisites:** a paid Claude plan (needed for the Skills/Capabilities settings).
2. **Enable the Skills Creator:** in Settings → Capabilities → Skills Preview, enable the pre-built "Skills Creator" skill (disabled by default). It assists in building your new skill.
3. **Prepare the master prompt:** use/adapt a detailed prompt template, filling in your website and workflow details. Takes ~5 minutes but is the most important prep step.
4. **Build the skill:** start a brand-new conversation, paste the completed master prompt, and **before hitting enter, attach all three documents** (Tone of Voice, Mini Sitemap CSV, Experience folder). The prompt should be designed to invoke the Skills Creator automatically. Processing takes a few minutes.
5. **Download and upload:** Claude returns a skill file (zipped) plus a usage guide. Keep the skill zipped (don't unzip it), then go to Settings → Capabilities → Skills Preview → Upload Skill and drag it in.

## How the Skill Behaves Once Built

Activate it in a new conversation (type `/` and select it), then give a brief. It will **not** start writing immediately — it follows a structured process:

1. **Clarifying questions:** asks for the primary keyword, target word count, and content angle before doing anything else.
2. **Research:** searches for up-to-date information on the topic.
3. **Proposes an outline/anatomy:** a structured plan including the questions it will answer, built around best practices for both traditional and AI search citation.
4. **Source integration plan:** lists external sources it intends to cite — you can remove or swap any of them at this stage.
5. **Internal linking strategy:** shows exactly how and where it will embed internal links, based on your Mini Sitemap.
6. **Case study integration:** pulls relevant wins/experiences from your Experience Document into the piece.

Only after you approve this plan does it write the full post.

## Quality Control Checklist (Run on Every Output)

1. **Tone:** does it actually sound like you? (Success here depends almost entirely on how specific your Tone of Voice document is.)
2. **External links:** are they real and functional, not hallucinated? A properly configured skill cites real sources.
3. **Internal links:** does it link naturally and correctly to the intended pages on your site, per the Mini Sitemap?

## Why This Beats a Giant One-Off Prompt

- **Persistence:** a regular chat forgets everything between sessions; a skill is a reusable package uploaded once.
- **Accuracy & personalization:** a regular prompt works from Claude's general memory; a skill actively reads your uploaded documents (real voice, real sitemap, real experience) every single time it runs.
- **Consistency:** produces a clean, repeatable system across all content, rather than re-litigating tone and structure in every conversation.

## Best Practices Summary

- **Tone of Voice:** specific > general. Show, don't just describe.
- **Mini Sitemap:** curated, not comprehensive.
- **Experience Document:** real numbers and short stories, not vague claims.
- **Test first:** run the skill on a topic you know intimately before scaling up, so you can catch tone or factual inaccuracies early and refine the source documents.

## Related Notes

- Website performance still matters even with perfect content: a caching plugin (e.g. WP Rocket) to handle lazy loading, code minification, and Core Web Vitals is worth pairing with this workflow, since slow load times increase bounce rate — a negative ranking signal.
- The same skill-building methodology can be extended to other SEO tasks: keyword research, competitor analysis, etc.

## Related Frameworks
- Content Creation Workflow (`content-creation/content-creation-workflow.md`)
- E-E-A-T Framework (`content-creation/eeat-framework.md`)
- Local SEO Entity System / AI Agent (`topical-authority-and-links/local-seo-entity-system.md`)
