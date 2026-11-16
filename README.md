**Full-Stack AI Engineer — I design LLM features (RAG, agents) and ship them into products that are already running.**

I'm Kien Duong, based in Hanoi, Vietnam (UTC+7), with 10+ years building production web software.

## Selected work

**RAG chatbot for healthcare — HealthImpact (01/2024 – 06/2026)**
React + Laravel + PostgreSQL/pgvector, serving 100–500 monthly active users. Retrieval uses ~800-char chunks with 200-char overlap, OpenAI embeddings, and hybrid BM25 + vector search (later moved to Reciprocal Rank Fusion) on an HNSW index.
Below a relevance threshold it answers "no information available" without calling the model; every answer cites its sources. Responses stream over SSE with caching and token limits, and a Q&A regression suite re-runs after every change.

**jira-mcp — 5-agent delivery pipeline on the Claude API (personal project, since 06/2026)**
Coordinator, analyzer, coder, tester and reviewer agents read a Jira ticket, ask back when requirements are unclear, draft the fix on its own branch, review it, and wait for human approval over Telegram; on failure the pipeline stops and reports. Haiku handles retrieval and reporting, Sonnet writes code and tests, Opus coordinates.
*Status: so far run only on test repositories and test tickets — not yet used in production.*

**T4 Framework — JoomlArt (2018 – 2022)**
Led development from architecture through release; the framework passed 1M+ downloads, and T4 Page Builder reached v2.0.

Earlier, at Lab3 (11/2022 – 03/2026), I built the frontends for whales.market, Whales Predict and mention.network (React, Next.js, TypeScript): an idempotency key on every user action, a real-time order book over WebSocket, Lighthouse 90+, and page load time cut by about 40%. Today I also do contract Joomla work for an enterprise healthcare client.

## How I work (for agencies)

- **Estimates:** [TODO(Kien): how you estimate — e.g. unit of estimate, ranges vs. fixed, when you re-estimate]
- **Delivery milestones:** [TODO(Kien): milestone cadence and what "done" means at each milestone]
- **Handover documentation:** [TODO(Kien): what the client receives at handover — e.g. README, runbook, ADRs, recorded walkthrough]
- **Time zone:** Hanoi, UTC+7. [TODO(Kien): overlap hours you offer for EU / US clients]
- **Communication:** [TODO(Kien): preferred channels and response time]

## Contact

- Website: [kiendt.dev](https://kiendt.dev)
- LinkedIn: [linkedin.com/in/kien-duong-fullstack](https://linkedin.com/in/kien-duong-fullstack)
- [TODO(Kien): preferred first-contact route — e.g. "message me on LinkedIn" or the contact form on kiendt.dev]
