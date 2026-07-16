# AI Employee Templates

**Turn an AI agent (Claude Code or any file-based agent) into an autonomous employee that remembers, plans, and gets things done — using nothing but plain text files.**

This repo contains the free core system: 8 ready-to-paste markdown files (with both CLAUDE.md and AGENTS.md contract variants — works out of the box with Claude Code, Codex CLI, and other file-based agents) that give your agent permanent memory across sessions, a prioritized backlog, a decision journal, and guardrails — so you can start a session with a single word (*"continue"*) and the agent knows exactly where it left off.

> 🧪 **Proof it works:** these templates are extracted from a live system that autonomously researched a market niche, wrote a ~70-page playbook about itself, built its sales assets, and shipped to production — in one day, with the owner only answering yes/no questions. ([The playbook](https://continuepress.gumroad.com/l/ai-employee) tells the whole story.)

## The problem this solves

AI agent sessions are amnesiac: when a session ends, everything it knew is gone. So people babysit their agents, re-explain context every morning, and never get real autonomy.

The fix isn't smarter AI — it's structure: **the only thing that survives a session is what was written to files.** These templates are that structure.

## Quickstart (15 minutes)

> ⚡ **Prefer a personalized start?** The free [AI Employee Starter Kit Generator](https://continuepress.pages.dev/tools/ai-employee-generator) asks 8 questions about your business and generates a CLAUDE.md + STATE + BACKLOG + FOR_HUMAN set tailored to your answers — in the browser, no signup.

1. Create a folder — your agent's "office".
2. Copy the contents of [`core-system/`](core-system/) into it.
3. Fill in `GOALS.md` (your mission — be honest, not impressive) and task T-1 in `BACKLOG.md`.
4. Skim `CLAUDE.md` (the agent's "job contract") and adjust the guardrails.
5. Start your agent in that folder: **"Read CLAUDE.md and begin. First: initialize a git repository and make the first commit. Then take T-1."**

From then on, every session starts with one word: **"continue"**.

## The 8 files

| File | Role |
|---|---|
| `CLAUDE.md` | The job contract: session protocols + guardrails (auto-read by Claude Code every session) |
| `STATE.md` | Single source of truth: where work stands, next 3 steps |
| `GOALS.md` | Mission, strategy, KPIs — you write this once |
| `BACKLOG.md` | Prioritized tasks + ideas parking lot |
| `DECISIONS.md` | Decisions + reasoning, so no session re-litigates them |
| `METRICS.md` | Outcomes data — the honesty mechanism |
| `FOR_HUMAN.md` | Escalation inbox: what needs *your* decision |
| `log/` | One journal entry per working day |

Key mechanics the contract enforces: **start protocol** (state → log → backlog → inbox → work), **checkpoints** (update state + git commit every hour), and **guardrails** (the agent never spends money, publishes, or messages people — it proposes in `FOR_HUMAN.md` and keeps working on the next task).

## Want the full system?

The complete **playbook** explains how to run this well (delegation, metrics, failure modes, scaling) and ships with **three pre-built employee configurations** — Research Analyst, Content Producer, Project Builder:

- 📖 **[Your AI Employee: The Playbook + Template Pack](https://continuepress.gumroad.com/l/ai-employee)** — 15 chapters + 3 appendices + 17 files ($19 launch / $39)
- 🆓 **[Free chapter: The Amnesia Problem](https://continuepress.gumroad.com/l/free-chapter)** — the core idea, no email required
- 🌐 [continuepress.pages.dev](https://continuepress.pages.dev)

## License

MIT — use freely, commercially or otherwise. Attribution appreciated, not required.

*Independent project — not affiliated with or endorsed by Anthropic or any AI vendor.*
