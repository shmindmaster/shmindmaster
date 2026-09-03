## Sarosh Hussain

I am a **commercial AI CTO and former enterprise CIO** who builds multi-agent systems that survive regulated production and turn into real businesses.

**CTO & Partner** at [Pendoah](https://pendoah.ai) · Former **CIO**, Perry Homes · Director-level AI/cloud transformation at Accenture, PwC, and Omnicom/Credera.

- Built an autonomous customer-operations platform to **$1M ARR**
- Increased customer resolution rates by an average of **30%**
- Built a multi-intent support agent for a **$1M ARR Shopify portfolio**
- Deployed **HIPAA-compliant NLP-to-SQL across 50 pharmacy locations**
- Lead **30 engineers** while remaining hands-on with architecture, evaluation, and production operations

My production focus: durable agent orchestration, context engineering with hybrid retrieval and reranking, MCP tool surfaces, evaluation release gates, least-privilege tool access, auditable provenance, and OpenTelemetry-based agent observability.

---

### Enterprise operating impact

- Led technology strategy while enterprise revenue grew from **$800M to $1.71B**
- Reduced IT operating expense approximately **20%**
- Retired approximately **70%** of the legacy application estate
- AI-enabled enterprise platforms contributed approximately **$50M in commercial uplift**

---

### Open-source products (released)

#### [CrewScore](https://github.com/shmindmaster/crewscore) · [crewscore.ai](https://crewscore.ai)

**AI-agent prompt governance linter** — finds missing *written* safeguards in system prompts.

- 23 published controls across 8 dimensions: human approval, injection defense, cost limits, stop conditions, auditability, and more
- Offline and deterministic; **no API key or LLM required**
- Python CLI · GitHub Action · GitHub Marketplace · browser-local checker
- Current release: **v0.6.11** on PyPI and GitHub Releases
- Public corpus study: 356 prompts scored offline; among 83 production-labeled prompts, median written-control coverage was **10/100** (coverage is not quality; methodology is published)

`pip install crewscore` · Action: `shmindmaster/crewscore@v2`

#### [GitPin](https://github.com/shmindmaster/gitpin) · [site](https://shmindmaster.github.io/gitpin/)

**Agent-delivery assurance gate and local evidence MCP** — makes agent-authored claims point to exact committed source before merge.

- Read-only, multi-repository, private/offline Git roots
- 12 `pin.*` MCP tools: candidates → evidence packs → independent verification
- Exact path, line, full commit SHA, and content hash; dirty worktrees excluded from committed evidence
- PR evidence gate with base-trusted policy and changed-path coverage
- Current release: **v0.6.3** on npm, GitHub Releases, GitHub Pages, and the official MCP Registry

`npx -y gitpin@0.6.3` · MCP identity: `io.github.shmindmaster/gitpin`

---

### What I build

Commercial and regulated AI products across customer operations, healthcare, legal, finance, and enterprise transformation. The work spans product strategy, multi-agent architecture, retrieval and context systems, human approval boundaries, evaluation, observability, APIs, cloud delivery, and production recovery.

Open source is where I publish the control-plane pieces: written-control governance through CrewScore and commit-pinned delivery evidence through GitPin. Confidential client identities remain private.

Houston, TX · [Portfolio](https://saroshhussain.com) · [LinkedIn](https://www.linkedin.com/in/saroshhussain/) · [X](https://x.com/shmindmaster) · [Facebook](https://www.facebook.com/shmindmaster/) · [CrewScore](https://crewscore.ai) · [GitPin](https://shmindmaster.github.io/gitpin/)

<!-- Cross-channel profile refresh: 2026-09-02. -->
