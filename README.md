# 🧠 AI Skills for Claude Code

A collection of Claude Code skills for Product Managers and builders.

## Skills

### ai-intel-daily — Daily AI News Digest

Your personal AI knowledge system. Every morning at 5am it:
- Searches the web for today's **top 10 AI stories**
- Writes a full structured brief into a **Google Doc** (your growing knowledge repo)
- Creates a short **Gmail summary draft** linking to the full edition

Each story includes: plain-English explanation, PM-specific actions, tinkerer experiments, real verified source links, contrarian takes, and a "connected dots" synthesis across all 10 stories.

#### Install in 4 steps

```bash
# 1. Install Claude Code (if you don't have it)
npm install -g @anthropic-ai/claude-code

# 2. Install the skill
claude skill install https://github.com/mishan07/ai-skills/raw/main/ai-intel-daily.skill

# 3. Connect Gmail MCP + Google Drive MCP in Claude Code settings

# 4. Run setup
/ai-intel-daily setup
```

Setup takes 2 minutes — it asks for your email and timezone, creates your personal Google Doc, and schedules the daily 5am task. Everything is private to you.

#### Manual trigger

```
/ai-intel-daily run
```

#### Requirements

- Claude Code CLI
- Gmail MCP connected
- Google Drive MCP connected

---

Built by [@mishan07](https://github.com/mishan07) · Powered by Claude + Live Web Search
