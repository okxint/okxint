### Hey, I'm Ashwin

PM who codes. I ship production fixes to large open source codebases, build AI tools, and write deep analysis on tech, crypto, and business. The goal: close the gap between product thinking and technical execution.

MBA · [IIM Kozhikode](https://www.iimk.ac.in/) &nbsp;|&nbsp; B.Tech · [NIT Trichy](https://www.nitt.edu/) &nbsp;|&nbsp; Ex-PwC US Advisory · Wipro · Polygon

[Substack](https://thedailysignal.substack.com/) · [Twitter/X](https://twitter.com/cashmein10) · ashwinchittrarasu@gmail.com

---

#### What I'm Building

- **[The Daily Signal](https://github.com/okxint/today-i-learned)** — in-depth analysis published every few days, weekly Substack roundup. Covers AI, crypto, business, F1, soccer, product.
- **[twitter-agent](https://github.com/okxint/twitter-agent)** — AI content pipeline: Reddit scraping → Claude synthesis → automated publishing
- **[Product Teardown](https://pm-teardown.vercel.app)** — drop a product name, get a PM-grade analysis. Scrapes 8+ sources, maps user journeys, prioritises with RICE scoring.

---

#### Open Source — 20+ Merged PRs

I fix real bugs in production codebases. Each PR is a shipped change with a clear problem → root cause → fix arc.

**[PostHog](https://github.com/PostHog/posthog)** ⭐ 35k &nbsp;— 8 merged, actively contributing

Notable fixes:
- [Race condition on new feature flag creation](https://github.com/PostHog/posthog/pull/65356) — `afterMount` fired two concurrent API calls; fixed with a cache-first resolver so the second call only runs if the first hasn't populated state yet
- [LLM analytics error state](https://github.com/PostHog/posthog/pull/58405) — sentiment API failure left the chart in a broken render state; added proper error boundary
- [SQL editor Y-axis settings isolation](https://github.com/PostHog/posthog/pull/55753) — settings object was shared across series; scoped per-series key so changing one doesn't affect others
- [Insights legend tag suppression](https://github.com/PostHog/posthog/pull/58946) — math/SQL tag showed even when the series had a custom name set
- [Dialog form isolation](https://github.com/PostHog/posthog/pull/62113) — nested dialogs shared a kea logic key; each instance now gets a UUID so form state doesn't bleed across
- [CLI scope: exclude llm_gateway from read-only preset](https://github.com/PostHog/posthog/pull/67252) — privileged scope in read-only preset caused silent 400s; excluded it and surfaced `invalid_scope` errors to the user

**[Immich](https://github.com/immich-app/immich)** ⭐ 102k — Substring matching for person name search

**[Hoppscotch](https://github.com/hoppscotch/hoppscotch)** ⭐ 79k — Handle non-string values in Postman collection import

**[Plane](https://github.com/makeplane/plane)** ⭐ 50k — Strip whitespace from instance configuration values

**[Directus](https://github.com/directus/directus)** ⭐ 36k — Deduplicate aggregate count requests on content navigation

**[Actual Budget](https://github.com/actualbudget/actual)** ⭐ 27k — Preserve schedule link when merging transactions

**[wasp-lang](https://github.com/wasp-lang/wasp)** ⭐ 18k — Auth pills border style fix

**[SurfSense](https://github.com/MODSetter/SurfSense)** ⭐ 14k — Memoize `formatRelativeTime` in thread list

Also: [melonJS](https://github.com/melonjs/melonJS) · [llm-d-prism](https://github.com/llm-d/llm-d-prism) · [KanaDojo](https://github.com/lingdojo/kana-dojo) (3 merged)

Open PRs in review: [PostHog](https://github.com/PostHog/posthog/pulls/okxint) (8 open) · [tldraw](https://github.com/tldraw/tldraw) ⭐ 47k · [shadcn-ui](https://github.com/shadcn-ui/ui) ⭐ 115k · [Grafana](https://github.com/grafana/grafana) ⭐ 74k

---

#### Projects

**[Product Teardown](https://pm-teardown.vercel.app)**
Drop in a product name, get a 5,000-word PM-grade analysis. Parallel scraping across 8+ sources, user journey mapping, drop-off identification, RICE-prioritised solutions. Built to answer "what would a real PM do with this product?"
`Next.js` `TypeScript` `RAG` `Streaming API`

**[twitter-agent](https://github.com/okxint/twitter-agent)**
End-to-end AI content pipeline. Scrapes Reddit for trending discussions, synthesises through Claude, posts original tweets on a schedule. Data collection → generation → publishing, fully automated.
`TypeScript` `Node.js` `Claude API` `Prompt Engineering`

**[The Daily Signal](https://github.com/okxint/today-i-learned)**
In-depth publication across AI, crypto, business, F1, soccer, and product. No summaries — every piece has an original take section built from 5–12 sources.

Recent pieces:
- [The AI PM gap](https://github.com/okxint/today-i-learned/blob/main/ai/ai-pm-gap-what-product-managers-get-wrong.md) — what most PMs still get wrong about building with LLMs
- [Arsenal won the league](https://github.com/okxint/today-i-learned/blob/main/soccer/arsenal-2026-season-deep-dive.md) — deep dive on the season that ended a 22-year wait
- [UCL Final: PSG vs Arsenal](https://github.com/okxint/today-i-learned/blob/main/soccer/ucl-final-psg-arsenal-preview-2026.md) — Budapest, May 31

---

#### Work

**PwC US Advisory** — Tech strategy for Fortune 500 clients. $5.2M+ in estimated savings across IT sourcing, ITSM automation, and infrastructure optimisation. Delivered across financial services and retail.

**Wipro** — Built a chatbot used by 100K+ employees. Shipped an ML anomaly detection model and an exception reporting algorithm at 95% accuracy. Top 5% appraisal among 10K+ people.

**Polygon (MATIC)** — Community growth and DeFi engagement for Southeast Asia.

---

#### Stack

`TypeScript` `Python` `React` `Next.js` `Node.js` `Claude API` `RAG` `Prompt Engineering` `SQL` `Tailwind CSS`

---

Open to remote AI PM and GTM Tech roles — [ashwinchittrarasu@gmail.com](mailto:ashwinchittrarasu@gmail.com)
