# Local SEO as Entity Matching: The "Core 30" System

**Source:** SEO Agency Owner / AI Developer (Claude Code case study)
**Tags:** #seo #local-seo #entities #claude-code #ai-agent #google-business-profile

## Core Concept

Most agencies treat local SEO like regular SEO (blog posts, generic backlinks) and fail. **Local SEO is not about keywords — it's about entities.** Google ranks local businesses based on how well their Google Business Profile (GBP), website, and online footprint all tell the *same story*.

## What Is an "Entity" Here

An entity is Google's internal representation of what something is: your GBP, your website, your business, and each individual service you offer. Google constantly checks whether these entities agree with each other. The closer they match, the more Google trusts — and ranks — the business. If they don't match, Google doesn't trust the business enough to rank it well.

## Case Study Result (Plumber, Malden MA)

- **Before:** Average Google Maps rank 6.18; only 15% top-three coverage (mostly near the business address); website full of placeholder Lorem Ipsum text.
- **After:** Average rank 3.22; 74% top-three coverage across the entire metro area; remaining spots ranked 4th.
- **What changed:** Not months of blogging or hundreds of backlinks — a systematic, entity-based restructuring.

## The Four-Step Manual Process

### Step 1: Entity Research
Understand how Google currently sees the business — primary/secondary GBP categories, listed services. This is the foundation for every subsequent step.

### Step 2: GBP Audit
Google allows up to 10 categories on a profile; most businesses use 1-2. Businesses should list 30+ services; most list ~5. **Every empty field is a missed trust signal.**

### Step 3: Gap Analysis (the step most agencies skip)
Compare the GBP to the website and find every discrepancy.
- Example: GBP lists "water heater installation" as a service, but the site has no page for it → that's a gap.
- Every gap tells Google "I don't know if this business actually does this."
- **This same consistency check is used by AI models** (ChatGPT, Perplexity, Gemini) for local recommendations — the gap costs you both channels at once.

### Step 4: The "Core 30" Website Structure
Most local sites have a homepage, an about/contact page, and maybe one service page — while the GBP lists 4 categories and 30 services. This mismatch destroys trust. The fix is a mirror-image structure:
- One page for every single category and service on the GBP (~30 pages)
- Homepage targets the primary category + city
- Each secondary category gets its own page linking to all its service pages
- Internal linking hierarchy exactly mirrors the GBP hierarchy

### Content Requirements for Core 30 Pages
- **Hyper-local relevance:** mention actual neighborhoods, local infrastructure conditions, local weather — written as someone who genuinely operates in that market. Generic copy-paste content fails this test immediately.
- **Manual effort (without automation):** ~1-2 hours per page for writing, schema, images, video, and deployment — 45-60 hours total per client.

## The AI Agent Automation (Built in Claude Code)

### Client Setup
- Paste the full GBP profile data (auto-parsed)
- Fill in "About the Business," voice/tone preferences, target audience, writing samples
- Use "Autogenerate Local Details" to scrape hyper-local city information if you don't know the area personally
- Set default image style preferences

### Automated Pipeline
1. **GBP & Service Audit**
   - Category audit: pulls competitors' secondary categories for your primary category, flags what you're missing
   - Service entity overlap check: runs searches comparing your primary category to each service to determine whether a service is a **distinct entity** (needs its own page, e.g. "sewer line repair") or an **overlapping entity** (doesn't need one, e.g. "bathroom plumbing" overlaps with "plumber")

2. **Site Crawler & Gap Analysis**
   - Crawls the existing site, auto-assigns pages to services/categories by URL/title
   - Runs the gap analysis and generates a prioritized content plan

3. **Bulk Content Production — The 8-Pass Humanization System**
   Generates content in bulk (e.g
      Generates content in bulk (e.g., 18 pages with videos in ~70 minutes) using 8 passes:
   1. Research & outline (crawls Reddit, local forums, competitor content for a locally-relevant outline + FAQ + AI-Overview-target snippet)
   2. Iterative section writing (each H2 written separately with slightly varied tone, mimicking human writing)
   3. Combination & tonal review pass
   4. Burst analysis (varies sentence length/word counts to remove predictable AI patterns)
   5. "Perplexity injection" (swaps predictable phrasing for less common, human-sounding equivalents)
   6. Conversational bookending (rewrites opening/closing lines in a distinctly opinionated, human voice — critical for both readers and AI-content detectors)
   7. Conversion optimization (adds localized CTAs, phone numbers, reasons to call this specific company)
   8. Final quality pass (transitions, factual accuracy, CTA strength)

4. **Schema Markup Generation:** auto-generates Organization, Video, Article, and FAQ schema for every page.
5. **Image Generation:** produces the specified number of images per page.
6. **Video Production & Upload:** writes a script, renders video, uploads to the client's YouTube channel.
7. **WordPress Deployment:** publishes the full post (content, images, video embed, schema) directly, scoring Grade A / 100% on performance checks.

### Expansion
The same tool can generate individual location pages to push 4th-place rankings into the top 3.

## The Key Takeaway

Give Google and AI models exactly what they want: **perfect entity consistency** between your GBP and a hyper-local, mirror-image website. Understanding and executing this system puts you ahead of the vast majority of agencies still doing generic local SEO.

## Related Frameworks
- E-E-A-T Framework (`content-creation/eeat-framework.md`)
- Building an SEO Content Skill in Claude (`claude-skills/building-an-seo-content-skill.md`)
- Topical Authority (`topical-authority-and-links/topical-authority.md`)
