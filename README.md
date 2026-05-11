# Anikhet Mulky

Software engineer. Currently at Clover Labs, working on product around LLMs and agents.

[anikhetmulky.com](https://www.anikhetmulky.com/) · [github](https://github.com/Anikhet) · [x](https://x.com/anikhetmulkyy) · [soundcloud](https://soundcloud.com/anikhetmulky) · [email](mailto:animulky@gmail.com)

---

### Lately

At Clover Labs since October 2025. A few things I've shipped there:

* A GPT‑4o chatbot that orchestrates 40+ tools across 9 SaaS APIs (Stripe, Slack, Notion). Cut cross platform data retrieval time by roughly half.
* Semantic search over 1,000+ document chunks with multiple retrieval thresholds. Relevance scores went up around 40%.
* An onboarding pipeline that replaced what used to be a fully manual flow. Now serves 1,000+ users, with proxy failover, atomic state transitions, and credential safe logging.
* An in house carousel editor that replaced Figma for the content team. Stacked image, opacity, and text layers as first class types, drag to resize transforms, and AI image generation across four models.

Before Clover I did a co‑op at Peeker AI (August 2024 to May 2025). Migrated their email deliverability dashboard from SvelteKit to Next.js, and built a serverless Lambda backend running 100,000+ inbox health checks a day.

### Side projects

**goswr** is a Go port of Vercel SWR's stale‑while‑revalidate caching pattern for server side use. The Go ecosystem only had partial coverage. Singleflight in one library, mutation API in another, no single piece with all of it plus generics, so I wrote one. Generic API, background revalidation, mutation, polling. [code](https://github.com/Anikhet/goswr)

**AstroAgent** is a voice enabled astronomy assistant. A 5 tool agent talking to the OpenAI Realtime API over WebRTC, paired with a real time Three.js scene that renders 8 planetary bodies. Cached position lookups stay under a millisecond and tool calls stay under 100ms. Built with Next.js 15, FastAPI, and Three.js. [code](https://github.com/Anikhet/astroagent)

A few others live in private repos. Happy to walk through any of them on a call:

* **DevInterview.AI** is a real time AI interviewer with a VRM avatar that actually looks at you. MediaPipe face tracking writes to refs (no React re‑renders) on one rAF loop, a Three.js loop reads them per frame to drive blendshapes, and a WebAudio AnalyserNode feeds visemes for lip‑sync. Gemini for the interviewer brain.
* **Drip** is an AI stylist for streetwear. Composes head to toe fits from a user's existing closet plus 1 or 2 shoppable adds, with a "Crew of 5" 🔥/MID/💀 voting loop. Next.js 16, GPT‑5.5 stylist + GPT‑5.4‑mini parser, FLUX via fal.ai, Trigger.dev for async generation, Serper for product matching.
* **Reverse GEO** tracks which queries cite your domain in LLM responses, not just Google. Firecrawl scraping into FAISS embeddings, then GPT‑4o for query generation and execution, then citation extraction. The LLM SEO problem, basically.
* **AstroAI** is an Expo + React Native production app. AI astrology chat, palm reading via camera with a vision model, RevenueCat IAP, Zustand persisted state, FastAPI backend.

### Stack

TypeScript and Python day to day, Go for infra side projects. React with Next, Node, FastAPI, Postgres, Redis, and AWS (Lambda, S3, DynamoDB, SQS). Comfortable in C++. Lately I've been deep in tool orchestration with the Vercel AI SDK and the OpenAI Realtime API.

### Off duty

Visual astronomy is what pulled me into AstroAgent in the first place. I produce music too. Everything on my SoundCloud is mine, start to finish. Video games, and a bit of competitive programming when I want to feel slow again.

### Reach

[animulky@gmail.com](mailto:animulky@gmail.com) is the best place. Happy to chat about agent tooling, eval design, or early stage roles.
