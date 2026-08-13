## Sarosh Hussain

I build **trustworthy enterprise AI systems** and the developer infrastructure that makes agent work verifiable.

**CTO & Partner** at [Pendoah](https://pendoah.ai) · Former **CIO**, Perry Homes · Director-level AI/cloud transformation at Accenture, PwC, and Omnicom/Credera.

Thesis: production AI needs architecture *and* control planes—agent safety, exact evidence, governance, and delivery discipline—not demos.

---

### Open-source products (released)

#### [CrewScore](https://github.com/shmindmaster/crewscore) · [crewscore.ai](https://crewscore.ai)

**AI-agent prompt governance linter** — finds missing *written* safeguards in system prompts.

- 23 published controls across 8 dimensions (human approval, injection defense, cost limits, stop conditions, auditability, and more)
- Offline, deterministic, **no API key / no LLM**
- Python CLI · GitHub Action · GitHub Marketplace · browser-local checker
- Current release: **v0.6.11** (PyPI + GitHub Release)
- Public corpus study: 356 prompts scored offline; among 83 production-labeled prompts, **median coverage 10/100** (coverage ≠ quality; methodology is published)

`pip install crewscore` · Action: `shmindmaster/crewscore@v2`

#### [GitPin](https://github.com/shmindmaster/gitpin) · [site](https://shmindmaster.github.io/gitpin/)

**Agent-delivery assurance gate + local evidence MCP** — makes agent-authored claims point to exact committed source before merge.

- Read-only, multi-repo, private/offline Git roots
- 12 `pin.*` MCP tools: candidates → evidence packs → independent verification
- Exact path, line, full commit SHA, content hash; dirty worktrees excluded from committed evidence
- PR evidence gate (base-trusted policy, changed-path coverage)
- Current release: **v0.6.3** on npm, GitHub Releases, GitHub Pages, and official MCP Registry (`io.github.shmindmaster/gitpin`)
- Formerly RepoContext 0.3.x (superseded product lineage)

`npx -y gitpin@0.6.3` · MCP identity: `io.github.shmindmaster/gitpin`

---

### What I do in production

Enterprise AI architecture and delivery—agentic platforms, RAG/LLMOps, regulated workflows—and the unglamorous work of making systems survive real estates, budgets, and audits. Client identities under NDA.

Open source is where I publish the **control-plane** pieces: written-control governance (CrewScore) and commit-pinned agent evidence (GitPin).

Houston, TX · [saroshhussain.com](https://saroshhussain.com) · [LinkedIn](https://www.linkedin.com/in/saroshussain/) · [crewscore.ai](https://crewscore.ai)

<!-- Reviewed 2026-08-05: products are released and publicly accessible; coordinated marketing announcements may still be pending. -->
