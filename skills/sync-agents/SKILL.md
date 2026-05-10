---
name: sync-agents
description: Pulls the latest agent definitions from GitHub and copies them to ~/.claude/agents/. Run daily or on demand to keep all machines current.
triggers: ["sync agents", "update agents", "pull latest agents"]
---

## Steps
1. Pull latest from GitHub:
   ```bash
   cd ~/infinite-leverage-2-agents
   git pull origin main
   ```
2. Copy all agent definitions to global Claude folder:
   ```bash
   cp -r .claude/agents/* ~/.claude/agents/
   ```
3. Confirm:
   ```bash
   echo "✅ Agents synced from GitHub."
   ls ~/.claude/agents/
   ```
