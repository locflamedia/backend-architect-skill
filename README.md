# backend-architect

A Claude Code skill that turns a plain-language feature request into a codebase-aware backend design document (data model, domain boundaries, transactions, queues, observability, anti-pattern scan) before any code is written.

Written for Laravel multi-tenant SaaS systems; the structure adapts to other stacks.

## Install

```bash
mkdir -p ~/.claude/skills/backend-architect
curl -fsSL https://raw.githubusercontent.com/locflamedia/backend-architect-skill/main/SKILL.md \
  -o ~/.claude/skills/backend-architect/SKILL.md
```

Then ask Claude Code to "design feature X" or "thiết kế tính năng X".
