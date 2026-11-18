### Sarosh Hussain

CTO & Principal AI Architect.

Anthropic [Claude Certified Architect - Foundations](https://www.credly.com/badges/feebd26f-810a-4d05-bd4c-7db753a8bf50/public_url) · November 2026.

---

I build open-source tools for AI-agent reliability — small, tested, documented, with honest limits.

| Repo | What it does | Try it |
| --- | --- | --- |
| [agenthub](https://github.com/shmindmaster/agenthub) | See every MCP server, skill and instruction file your coding agents actually load (21 supported) — and what's broken. Read-only, no account. Plus a sync control plane with drift detection. | `npx @shmindmaster/agenthub doctor` |
| [heatlot](https://github.com/shmindmaster/heatlot) | AI reads supplier certificates; deterministic rules decide; cited, signed receipts. | `npx heatlot demo` |
| [subtext-scan](https://github.com/shmindmaster/subtext-scan) | Find hidden prompt-injection text in PDF/DOCX/HTML before your agent follows it. The MCP server withholds the payload. | `npx subtext-scan scan file.pdf` |
| [replyonce](https://github.com/shmindmaster/replyonce) | Stop your agent replying, refunding or ticketing twice. Fencing tokens + effect ledger. Node + Python, zero runtime deps. | `npx replyonce demo` |
| [fakeplane](https://github.com/shmindmaster/fakeplane) | Stateful fake Zendesk/Slack/Linear/HTTP backends for agent evals that block bad releases. | `npx fakeplane demo` |
| [safeguards](https://github.com/shmindmaster/safeguards) | Dataset: 356 publicly collected AI system prompts scored against 23 written safeguards. None states even half. Data CC BY 4.0. | [Hugging Face](https://huggingface.co/datasets/shmindmaster/agent-prompt-safeguards-2026) |

They form an agent-reliability stack: screen untrusted documents (subtext-scan), make side effects at-most-once (replyonce), test against stateful fakes before release (fakeplane), and keep every coding agent's config in sync (agenthub). [heatlot](https://github.com/shmindmaster/heatlot) is the worked example; [safeguards](https://github.com/shmindmaster/safeguards) is the evidence that prompts alone don't enforce controls.

Writing: [saroshhussain.com](https://saroshhussain.com).
