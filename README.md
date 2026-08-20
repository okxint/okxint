### Hey, I'm Ashwin

PM who codes. I ship production fixes to large open source codebases, build AI tools, and write deep analysis on tech, crypto, and business. The goal: close the gap between product thinking and technical execution.

MBA · [IIM Kozhikode](https://www.iimk.ac.in/) &nbsp;|&nbsp; B.Tech · [NIT Trichy](https://www.nitt.edu/) &nbsp;|&nbsp; Ex-PwC US Advisory · Wipro · Polygon

[Substack](https://thedailysignal.substack.com/) · [Twitter/X](https://twitter.com/cashmein10) · ashwinchittrarasu@gmail.com

---

#### Projects

**[Farmaze](https://farmaze.com)** — AI procurement platform for B2B restaurants

Restaurants send one WhatsApp message. The platform parses the order, splits it across suppliers, confirms delivery, and reports back. Built across 8 services in production.

Key problems solved:
- Chefs order in natural language ("10 kg tomatoes, 5 bunches coriander") - NLP + fuzzy matching maps to SKUs and quantities without structured input
- Some chefs send voice notes or photos of handwritten lists - Whisper transcription and GPT-4o Vision extract line items from both
- Restaurants source from multiple suppliers per category - a routing engine splits one order into N per-supplier messages based on category mappings, pricing, and delivery schedule
- Ops team needed Claude Desktop access to query orders and analytics - built a 23-tool MCP server with tools for order management, analytics, and OCR; includes `daily-ops` and `client-health` prompt templates
- Supplier performance was tracked manually - weekly automated report cards score fill rate, delivery time, and confirmation latency per supplier

Agents: order parser, supplier router, supplier onboarding, demand forecast, MCP admin agent

`Go` `PostgreSQL` `Node.js` `TypeScript` `Next.js` `Redis` `Meta WhatsApp API` `GPT-4o` `MCP SDK` `Docker`

---

**[gtm-intel](https://github.com/okxint/gtm-intel)** — Pre-call technical intelligence CLI for GTM teams

Give it a GitHub org, get a sales-ready brief: stack, engineering velocity, open bugs translated to business impact, integration angles, and conversation starters. Powered by GitHub API + Claude.

`TypeScript` `Claude API` `GitHub API`

---

**[Product Teardown](https://pm-teardown.vercel.app)** — PM-grade product analysis on demand

Drop in a product name, get a structured analysis: parallel scraping across 8+ sources, user journey mapping, drop-off identification, RICE-prioritised feature recommendations.

`Next.js` `TypeScript` `RAG` `Claude API`

---

**[twitter-agent](https://github.com/okxint/twitter-agent)** — Automated content pipeline

Reddit scraping to Claude synthesis to scheduled publishing. Fully automated: data collection, generation, and posting.

`TypeScript` `Node.js` `Claude API`

---

#### Open Source — 20+ Merged PRs

**[PostHog](https://github.com/PostHog/posthog)** 35k stars, 8 merged

- [Race condition on feature flag creation](https://github.com/PostHog/posthog/pull/65356) - `afterMount` fired two concurrent API calls; fixed with cache-first resolver
- [LLM analytics error state](https://github.com/PostHog/posthog/pull/58405) - sentiment API failure left chart in broken render; added error boundary
- [SQL editor Y-axis isolation](https://github.com/PostHog/posthog/pull/55753) - settings object shared across series; scoped per-series key
- [Insights legend tag suppression](https://github.com/PostHog/posthog/pull/58946) - math/SQL tag showed even with custom name set
- [Dialog form isolation](https://github.com/PostHog/posthog/pull/62113) - nested dialogs shared kea logic key; each instance now gets a UUID
- [CLI scope fix](https://github.com/PostHog/posthog/pull/67252) - privileged scope in read-only preset caused silent 400s; excluded and surfaced errors

**[Immich](https://github.com/immich-app/immich)** 102k stars - Substring matching for person name search

**[Hoppscotch](https://github.com/hoppscotch/hoppscotch)** 79k stars - Handle non-string values in Postman collection import

**[Plane](https://github.com/makeplane/plane)** 50k stars - Strip whitespace from instance configuration values

**[Directus](https://github.com/directus/directus)** 36k stars - Deduplicate aggregate count requests on content navigation

**[Actual Budget](https://github.com/actualbudget/actual)** 27k stars - Preserve schedule link when merging transactions

**[wasp-lang](https://github.com/wasp-lang/wasp)** 18k stars - Auth pills border style fix

**[SurfSense](https://github.com/MODSetter/SurfSense)** 14k stars - Memoize `formatRelativeTime` in thread list

Also: [melonJS](https://github.com/melonjs/melonJS) · [llm-d-prism](https://github.com/llm-d/llm-d-prism) · [KanaDojo](https://github.com/lingdojo/kana-dojo)

Open PRs in review: [tldraw](https://github.com/tldraw/tldraw) 47k stars · [shadcn-ui](https://github.com/shadcn-ui/ui) 115k stars · [Grafana](https://github.com/grafana/grafana) 74k stars · [trpc](https://github.com/trpc/trpc) · [TanStack Query](https://github.com/TanStack/query) · [SvelteKit](https://github.com/sveltejs/kit)

---

#### Work

**PwC US Advisory** - Tech strategy for Fortune 500 clients. $5.2M+ in estimated savings across IT sourcing, ITSM automation, and infrastructure optimisation.

**Wipro** - Built a chatbot used by 100K+ employees. ML anomaly detection model and exception reporting algorithm at 95% accuracy. Top 5% appraisal among 10K+ people.

**Polygon (MATIC)** - Community growth and DeFi engagement for Southeast Asia.

---

#### Stack

`TypeScript` `Go` `Python` `React` `Next.js` `Node.js` `Claude API` `GPT-4o` `RAG` `PostgreSQL` `Redis` `Docker` `Tailwind CSS`

---

Open to remote AI PM and GTM Tech roles - [ashwinchittrarasu@gmail.com](mailto:ashwinchittrarasu@gmail.com)
