# Personal Executive Website — Project Brief

**Owner:** Jay Livens  
**Site:** https://jl-678.github.io/  
**Repository:** `jl-678/jl-678.github.io`  
**Potential custom domain:** `jlivens.com`  
**Status:** Version 1 published; refining content and adding selected work.

## 1. Purpose

Create a polished, concise personal website that establishes Jay as an enterprise technology product marketing executive. It should support opportunities at the **VP / Head of Product Marketing** and **Senior Director of Product Marketing** levels without appearing to be a job-search landing page or a duplicate resume.

**Primary audience:** Hiring executives, recruiters, peers, industry contacts, and potential collaborators.

**Visitor takeaway (within 15–30 seconds):** Jay builds and leads strong product marketing teams, develops differentiated go-to-market strategies, understands complex enterprise technology, and can engage credibly with executive audiences.

## 2. Positioning and Voice

- Lead with **executive leadership and business impact**, not a list of technical features.
- Be direct, confident, specific, and understated; avoid inflated claims and marketing clichés.
- Favor short paragraphs, meaningful headings, and easily scanned sections.
- Keep the page appropriate for both VP and Senior Director roles.
- Do **not** publish confidential or precise performance metrics (pipeline, bookings, attainment, etc.). Those belong in private, tailored resumes.
- Avoid overly narrow positioning around the most recent job or one technology category.
- Do not portray Jay as an AI model builder or researcher. His relevant AI experience includes marketing AI-powered observability and monitoring/observability for AI applications and infrastructure.

### Homepage introduction — current working copy

> I build and lead product marketing teams, shape differentiated go-to-market strategies, and help enterprise technology companies connect innovation with customer needs and business outcomes.

**Open decision:** Whether to add a second sentence about technical expertise. The earlier sentence — “My experience spans AI-powered observability, cloud infrastructure, and enterprise data platforms” — felt generic and resume-like. A candidate alternative is:

> My expertise spans observability, AI, cloud-native infrastructure, and enterprise data platforms.

**Current preference:** Try the **single-sentence introduction** first; let the technical expertise pillar and portfolio establish depth. Do not put “logs, metrics, traces” in the hero. These and OpenTelemetry/telemetry pipelines can appear in substantive examples elsewhere.

## 3. Information Architecture

Single-page website, in this order:

1. **Hero:** Name, concise executive descriptor, short introduction, discreet LinkedIn/contact links.
2. **What I Bring:** Four leadership pillars, preferably a compact 2×2 grid.
3. **Selected Career Impact:** Four brief examples organized by impact, not a chronological resume.
4. **Selected Work & Speaking:** Curated evidence (conference talks, webcasts, articles, executive presentations), with actual links as they become available.
5. **Contact / footer:** Simple, professional contact options.

No separate VP and Senior Director resume download links are required on the public site. A minimal career timeline may be considered later only if it adds value.

## 4. Four Leadership Pillars

### Building & Leading High-Performing Teams
Building, mentoring, and empowering product marketing teams to deliver meaningful business results.

### Product Marketing & GTM Strategy
Driving differentiated positioning, successful product launches, and revenue growth across enterprise markets.

### Enterprise Technology & AI Expertise
Deep expertise spanning enterprise IT infrastructure, cloud technologies, observability, and AI-powered solutions.

**Approved messaging:** Use this description for the technical expertise pillar.

### Executive Engagement & Thought Leadership
Engaging and influencing executive audiences through strategic customer briefings, industry presentations, partner engagements, and thought leadership.

These are working descriptions, not immutable copy. Keep them balanced in length and avoid repetition with the hero and impact section.

## 5. Four Selected Career Impact Themes

These should become **concrete, credible accomplishments** rather than generic capability claims. Keep them succinct and avoid hard public metrics.

1. **Building & Leading High-Performing Teams:** Built a product marketing team from the ground up, growing to seven direct reports while mentoring and developing team members into more senior roles. **Approved messaging** for the career-impact description; retain the existing website heading, “Building teams that deliver.”
2. **Driving Significant Business Growth:** Observability and logs go-to-market work at Dynatrace; show business contribution without confidential figures.
3. **Launching & Scaling Innovative Technologies:** Actifio's Database DevOps offering; Dynatrace Bindplane / OpenTelemetry and telemetry pipeline initiatives. Explain what Jay led and why it mattered.
4. **Executive Engagement & Industry Speaking:** Lead presenter and moderator in executive briefing centers (EBCs), Gartner conference speaking, customer and global systems integrator/partner webcasts, executive and analyst engagements.

**Editorial note:** Don't feature Sakon as a highlighted accomplishment. If necessary, it can appear in basic employment history.

## 6. Technical Depth — Where It Belongs

Use layered specificity:

- **Hero:** Broad executive positioning; ideally no technology laundry list.
- **Pillars:** Enterprise IT infrastructure, cloud technologies, observability, and AI-powered solutions.
- **Impact and portfolio:** Specific proof points such as logs, metrics, traces, OpenTelemetry, telemetry pipelines, AI-powered observability, AI application monitoring, cloud platforms, and relevant partnerships.

The website should communicate both strategic leadership and genuine technical fluency without reading like a product datasheet.

## 7. Selected Work & Speaking Portfolio

Prioritize **real, verifiable, attributable examples** over a large gallery. Potential categories:

- Gartner and other industry conference presentations.
- Executive briefing center presentations and moderation (where publicly shareable).
- Customer, GSI/partner, and expert webcasts.
- Articles, interviews, thought leadership, and relevant launch or partnership materials.

Each item should ideally have a short title, context (role and audience), and an external link; thumbnails are optional. Do not invent links, speaking credits, quotations, or metrics. Do not expose private customer materials.

**To collect:** Public recordings, event pages, article links, presentation titles, dates, and Jay's exact role in each.

## 8. Design Principles

- Clean, modern, **understated executive** design; white or light background, dark text, restrained navy/technology accents.
- Strong typography, whitespace, clear hierarchy, and mobile responsiveness.
- Minimal visual clutter; no gimmicky badges, toy-like awards, excessive animation, or gratuitous clicks.
- Fast-loading and accessible; semantic HTML, clear links, visible focus states, sufficient contrast.
- A recruiter should grasp the essentials quickly; the portfolio provides optional depth.

## 9. Technical and Publishing Workflow

- **Implementation:** Lightweight static HTML/CSS; only minimal JavaScript if necessary. No React, WordPress, database, or self-hosted server needed.
- **Source control:** GitHub repository `jl-678/jl-678.github.io`.
- **Current site:** https://jl-678.github.io/
- **Local development:** Clone repository onto Mac, edit in VS Code, preview locally, commit and push; GitHub Pages automatically deploys.
- **Potential domain:** `jlivens.com`, connected through GitHub Pages custom domain and DNS once ready.
- **Roles:** Use ChatGPT for strategy, messaging, and editorial decisions; use VS Code/Codex to implement changes in the repository.
- **This file:** Commit `WEBSITE_BRIEF.md` to the repo so future Codex sessions can follow the same decisions. Keep it updated as decisions evolve.

## 10. Decisions and Guardrails

**Do:**
- Emphasize team leadership, GTM strategy, enterprise technical depth, and executive engagement.
- Showcase concrete examples, especially executive speaking and thought leadership.
- Write for hiring executives first, with optional deeper evidence for interested readers.
- Keep factual claims aligned with Jay's resumes and confirmed public materials.

**Don't:**
- Turn the homepage into a long-form resume or a keyword-stuffed SEO page.
- Publish confidential performance numbers or internal business data.
- Overemphasize Sakon.
- Claim hands-on AI research/model-building expertise.
- Add fabricated portfolio links or unpublished speaking engagements.
- Redesign the whole site for each copy change; iterate incrementally.

## 11. Open Questions / Next Steps

1. Review hero with **one sentence only** and decide whether technical scope needs a second sentence.
2. Refine the other three impact cards for specificity and differentiation.
3. Collect and verify the strongest 3–6 public portfolio examples.
4. Review mobile layout and accessibility; polish as needed.
5. Decide when to connect `jlivens.com` and whether to allow search indexing.
6. Separately, at a later time, strengthen executive engagement/speaking experience in both VP/Head PMM and Senior Director resume versions. **Do not let resume editing derail website work.**

---

**Maintenance note for AI coding assistants:** Treat this brief as the website's editorial source of truth, but prefer explicit new user instructions if they revise a decision. Preserve existing design and site functionality unless asked to change them. Ask for clarification rather than inventing achievements, metrics, or public portfolio evidence.
