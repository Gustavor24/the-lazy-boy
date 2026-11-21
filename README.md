# The Lazy Boy 🛋️

**A skill for AI agents that makes you the last resort.**

Tired of your agent saying *"open your terminal and run…"* or *"send me a screenshot"* when it has the tools to do it itself? The Lazy Boy fixes that.

Before asking you anything, the agent works through every route it has, in a sensible order for the kind of task:

- connectors / MCP servers
- shell access to your computer
- web search
- its own browser
- your browser (only asking you to sign in)
- screen control

Only when all of them are truly exhausted does it ask you, and then with **one single step**, already set up and waiting.

## What it does NOT change

Lazy doesn't mean reckless. The agent still never types your passwords, never solves CAPTCHAs, never moves money or publishes anything without your explicit yes, and confirms before deleting anything permanently.

## Install

**Claude Code**

```bash
mkdir -p ~/.claude/skills/the-lazy-boy
curl -o ~/.claude/skills/the-lazy-boy/SKILL.md \
  https://raw.githubusercontent.com/Gustavor24/the-lazy-boy/main/SKILL.md
```

**Claude apps:** upload `SKILL.md` as a custom skill.

**Other agents:** paste the contents of `SKILL.md` into your system prompt or rules file.

## License

MIT
