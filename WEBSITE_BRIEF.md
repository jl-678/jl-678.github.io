# Personal Executive Website — Project Brief

**Owner:** Jay Livens  
**Site:** https://jl-678.github.io/  
**Repository:** `jl-678/jl-678.github.io`  
**Potential custom domain:** `jlivens.com`  
**Status:** Version 1 published; refining content. The selected portfolio content and structure are finalized.

## 1. Purpose

Create a polished, concise personal website that establishes Jay as an enterprise technology product marketing executive. It should support opportunities at the **VP / Head of Product Marketing** and **Senior Director of Product Marketing** levels without appearing to be a job-search landing page or a duplicate resume.

**Primary audience:** Hiring executives, recruiters, peers, industry contacts, and potential collaborators.

**Visitor takeaway (within 15–30 seconds):** Jay builds and leads strong product marketing teams, develops differentiated go-to-market strategies, understands complex enterprise technology, and can engage credibly with executive audiences.

## 2. Positioning and Voice

- Lead with **executive leadership and business impact**, not a list of technical features.
- Be direct, confident, specific, and understated; avoid inflated claims and marketing clichés.
- Favor short paragraphs, meaningful headings, and easily scanned sections.
- Keep the page appropriate for both VP and Senior Director roles.
- Use only the explicitly approved public business metrics in Section 5: **44% above plan**, **50%+ of the business**, and triple-digit growth. Do **not** add other confidential or precise performance metrics (pipeline, bookings, attainment, etc.); those belong in private, tailored resumes.
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
4. **Selected Work & Speaking:** Two compact boxes, Articles & Publications and Presentations, each containing four curated entries with public links and short descriptors; no dates.
5. **Contact / footer:** Simple, professional contact options.

No separate VP and Senior Director resume download links are required on the public site. A minimal career timeline may be considered later only if it adds value.

## 4. Four Leadership Pillars

### Building & Leading High-Performing Teams
Building, mentoring, and empowering product marketing teams to deliver meaningful business results.

### Product Marketing & GTM Strategy
Driving differentiated positioning, successful product launches, and revenue growth across enterprise markets.

### Enterprise Technology & AI Expertise
Bringing hands-on technical depth across cloud, infrastructure, observability, and AI to product positioning, go-to-market strategy, and executive conversations.

**Approved messaging:** Use this description for the technical expertise pillar.

### Executive Engagement & Thought Leadership
Engaging and influencing executive audiences through strategic customer briefings, industry presentations, partner engagements, and thought leadership.

These are working descriptions, not immutable copy. Keep them balanced in length and avoid repetition with the hero and impact section.

## 5. Four Selected Career Impact Themes

Use the following approved card titles and descriptions in this order. Preserve the existing four-card, two-column desktop layout, responsive mobile behavior, styling, and spacing.

1. **Building High-Performing Teams:** Built a product marketing team from the ground up, growing to seven direct reports while mentoring and developing team members into more senior roles.
2. **Driving Significant Business Growth:** Led global GTM strategy for log management, contributing to pipeline performance **44% above plan** and triple-digit growth.
3. **Leading & Scaling Enterprise Solutions:** Led product marketing for Dynatrace's APM solution area, representing **50%+ of the business**, while helping launch and scale technologies across observability and enterprise infrastructure.
4. **Executive Engagement & Industry Speaking:** Presented at Gartner conferences, led executive briefings, and engaged customers and partners through technical webcasts.

**Approved public metrics:** The percentage-based business metrics above and the triple-digit growth statement are explicitly approved for these cards. Bold only **44% above plan** and **50%+ of the business** within their descriptions, using semantic `<strong>` markup and the existing text styling. Do not add any additional financial or business metrics, metric tiles, counters, or graphics beyond the outline icons described below.

**Impact icons:** Use consistent 26px blue outline icons to the left of each card's heading and description: users/group, upward-trending arrow, stacked layers, and microphone, respectively. Use the existing accent color, with no backgrounds, circles, or badges. The icons are decorative inline SVGs, hidden from assistive technology, with no added library dependency. Preserve all card copy and the responsive layout; the numbered leadership pillars remain unchanged.

**Editorial note:** Don't feature Sakon as a highlighted accomplishment. If necessary, it can appear in basic employment history.

## 6. Technical Depth — Where It Belongs

Use layered specificity:

- **Hero:** Broad executive positioning; ideally no technology laundry list.
- **Pillars:** Hands-on technical depth across cloud, infrastructure, observability, and AI, applied to product positioning, go-to-market strategy, and executive conversations.
- **Impact and portfolio:** Specific proof points such as logs, metrics, traces, OpenTelemetry, telemetry pipelines, AI-powered observability, AI application monitoring, cloud platforms, and relevant partnerships.

The website should communicate both strategic leadership and genuine technical fluency without reading like a product datasheet.

## 7. Selected Work & Speaking Portfolio

The section heading is **Selected Work & Speaking**. Use exactly two boxes, **Articles & Publications** and **Presentations**, each containing four curated entries in the order below. Keep the boxes equal in height and side by side on desktop, and stack them vertically on mobile. Preserve the compact card styling, typography, colors, spacing, and link hover behavior, with subtle separators between entries and descriptors visually subordinate to titles.

### Portfolio images

Each box has one wide image above its heading. Use identical responsive image frames, approximately 3:1 (14:5), about 175px high at the site's full desktop content width. Use `object-fit: cover` with an individual `object-position` for each image. The existing card's rounded corners clip the images. Preserve all entry titles, descriptors, and links below the images; add no captions, dates, badges, or decorative graphics.

- **Articles & Publications:** `assets/images/state-of-log-management-2026.webp` (1000×525). Authentic Dynatrace promotional artwork for the report, downloaded from the `og:image` metadata of the [State of Log Management 2026 page](https://www.dynatrace.com/resources/state-of-log-management-2026-18096921/). [Original promotional image](https://cdn.dm.dynatrace.com/assets/images/conversion-pages/conversion-page/_1200x630_crop_center-center_82_none/bae24801-RC-state-log-mgmt-2026-1600x900-FINAL.png?mtime=1787232235). Keep the report title readable in the crop. Do not recreate the cover or substitute unrelated artwork; if authentic artwork is unavailable, use a placeholder and report the limitation.
- **Presentations:** `assets/images/gartner-spain-speaking.webp` (450×300). Jay confirmed that the supplied `ChatGPT Image Nov 19, 2026, 12_08_49 PM.png` is his authentic second Gartner photograph, despite its filename. The 450×600 portrait source shows Jay presenting in front of the IT Xpo Stage 2 signage in Spain. Crop excess ceiling and foreground, emphasizing Jay and the stage branding while retaining some audience context. The portrait source limits how much audience can fit into the wide frame; do not stretch or generate missing image content.

Both assets are optimized WebP files with meaningful alt text and lazy loading. Use authentic report artwork and Jay's actual photograph only; no AI-generated artwork, mockups, stock photography, or per-entry thumbnails.

### Articles & Publications

1. [State of Log Management 2026](https://www.dynatrace.com/resources/state-of-log-management-2026-18096921/) — Industry research · Research strategy, narrative & GTM
2. [OpenTelemetry: A Guide to Open Observability](https://www.dynatrace.com/resources/ebooks/opentelemetry/) — Ebook · Open standards and observability
3. [What is APM?](https://www.dynatrace.com/news/blog/what-is-apm/) — Cloud-native application performance
4. [What is OpenTelemetry?](https://www.dynatrace.com/news/blog/what-is-opentelemetry/) — Open standards and telemetry

**Research attribution:** Jay played a significant role throughout the State of Log Management initiative, helping shape the research, findings, narrative, and go-to-market strategy. He did not personally write the report; do not imply sole authorship. Keep this context in the documentation rather than adding a long description to the website.

### Presentations

1. [Scaling AI: From Hype to High Performance](https://www.gartner.com/en/conferences/emea/symposium-spain/sessions/detail/6658378-Dynatrace-Scaling-AI-From-Hype-to-High-Performance) — Gartner IT Symposium/Xpo, Spain · Featured Speaker
2. [Why APM and Distributed Tracing Are Foundational for Agentic AI Operations](https://www.dynatrace.com/info/webinars/why-apm-and-distributed-tracing-are-foundational-for-agentic-ai-operations/) — Agentic AI · Technical webcast
3. [Scaling AI from Development to Production](https://www.dynatrace.com/resources/scaling-ai-from-development-to-production-20237967/) — DXC Technology · Partner webcast
4. [Vitality's Journey to Unified, Privacy-First Observability](https://www.dynatrace.com/resources/vitalitys-journey-to-unified-privacy-first-observability-20087393/) — Customer webcast · Vitality

**Presentation attribution:** Jay personally delivered the Gartner presentation. Keep its title and descriptor meaningful independently of the external session page, which Gartner may eventually remove. Do not invent or imply specific presenter or moderator roles for the webcasts.

Titles are clickable, opening the supplied external URLs in a new tab with `target="_blank"` and `rel="noopener noreferrer"`. Each entry has only its title and short descriptor. **Omit publication dates and event dates.** Retain “2026” as part of the research report's title. Apart from the two approved images above the box headings, do not add images, thumbnails, badges, lengthy descriptions, or additional portfolio categories.

Prioritize **real, verifiable, attributable examples** over a large gallery. Do not invent links, speaking credits, quotations, or metrics. Do not expose private customer materials.

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
- Publish additional financial or business metrics beyond the explicitly approved statements in Section 5, or disclose other confidential internal business data.
- Overemphasize Sakon.
- Claim hands-on AI research/model-building expertise.
- Add fabricated portfolio links or unpublished speaking engagements.
- Redesign the whole site for each copy change; iterate incrementally.

## 11. Open Questions / Next Steps

1. Review hero with **one sentence only** and decide whether technical scope needs a second sentence.
2. Maintain the approved career-impact card titles, copy, and limited public business metrics in Section 5.
3. Maintain the finalized Articles & Publications and Presentations selections as public work evolves; retain the decision to omit dates.
4. Review mobile layout and accessibility; polish as needed.
5. Decide when to connect `jlivens.com` and whether to allow search indexing.
6. Separately, at a later time, strengthen executive engagement/speaking experience in both VP/Head PMM and Senior Director resume versions. **Do not let resume editing derail website work.**

---

**Maintenance note for AI coding assistants:** Treat this brief as the website's editorial source of truth, but prefer explicit new user instructions if they revise a decision. Preserve existing design and site functionality unless asked to change them. Ask for clarification rather than inventing achievements, metrics, or public portfolio evidence.
