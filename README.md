# recap

Claude Code plugin to quickly recover previous session context after `/clear`.

## What it does

- Lists recent 5 sessions with first user message preview
- Lets you select a session to recover
- Extracts last 3 user messages from the selected session
- Summarizes what you were working on, last request, and current status

## Install

```
/plugin install recap
```

Or manually copy `skills/recap/SKILL.md` to `~/.claude/skills/recap/`.

## Usage

- `/recap` — show recent sessions and pick one
- `/recap 1` — recover from the most recent previous session
- `/recap <session-id-prefix>` — recover from a specific session
