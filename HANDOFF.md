# Infinite Leverage 2 — AI Team Hand-off

**Prepared by**: Dave / Edge8
**Date**: 2026-05-10
**For**: Tracy

---

## Your AI team is ready

You have 8 AI agents installed and running. Here is what each one does and how to talk to them.

### Build Team
- **Product Manager** — Ask: "What should we build next?" / "Compile today's standups" / "Write a RAG report"
- **Developer** — Ask: "Build X feature" / "Fix this bug" / "Review this code"
- **QA** — Ask: "Test this change" / "What breaks if I do X?"
- **DevOps** — Ask: "Check deployment status" / "Review git history" — escalates to human engineer when needed

### GTM Team
- **Writer** — Ask: "Write this week's post" / runs automatically every Monday 9am
- **Designer** — Ask: "Generate the hero image" / runs automatically every Tuesday 9am
- **Web Publisher** — Ask: "Publish this post" / runs automatically every Wednesday 9am
- **Email Marketer** — Ask: "Draft a welcome email" / "Write this week's newsletter"

---

## Daily workflow

Your content publishes itself Monday–Wednesday. You only need to:
1. Add a `brief.md` to any `content/topics/{slug}/` folder to queue a post
2. Run `git push origin main` on Wednesday after the Web Publisher stages the commit

---

## Keeping agents current

When Dave updates the agent team:
1. Open Claude Code
2. Say: **"sync agents"**
3. The `sync-agents` skill pulls the latest from GitHub automatically

---

## Your live website
URL: https://infinite-leverage-2-hello-tracy.vercel.app
Repo: https://github.com/tracy-infinite-leverage/infinite-leverage-2-hello-tracy

---

## Credentials and access
All service credentials are in the credentials file Dave shared with you.
Store it securely — do not commit it to any repository.

---

## First actions
1. Open Claude Code on your laptop
2. Say hello to your Product Manager: "What are we working on this week?"
3. Add your first content brief to `content/topics/your-first-post/brief.md`
4. Watch the pipeline run Monday morning
