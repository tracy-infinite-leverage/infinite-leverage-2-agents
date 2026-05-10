# Infinite Leverage 2 — Agents Repo

Single source of truth for all 8 AI agent definitions for Infinite Leverage 2.

## Usage

Clone this repo and copy agents to any machine:

```bash
git clone https://github.com/tracy-infinite-leverage/infinite-leverage-2-agents.git ~/infinite-leverage-2-agents
cp -r ~/infinite-leverage-2-agents/.claude/agents/* ~/.claude/agents/
```

## Keep agents in sync

Install the `sync-agents` skill (see `skills/sync-agents/SKILL.md`) and run it daily:

```bash
# Inside Claude Code
sync agents
```

## The 8 agents

### Build Team
| Agent | Role |
|-------|------|
| Product Manager | OKRs, epics, standups, RAG status |
| Developer | Code to project standards |
| QA | Testing — knows what AI can and cannot test |
| DevOps | Git, environments, deployments |

### GTM Team
| Agent | Role |
|-------|------|
| Writer | One post per run, owner's voice |
| Designer | One hero image per run, Gemini |
| Web Publisher | Publishes post, stages git commit |
| Email Marketer | Subscriber nurture via Brevo |
