# recap

Claude Code plugin to quickly recover previous session context after `/clear`.

`/clear` 후 이전 대화 맥락을 빠르게 복구하는 Claude Code 플러그인.

## What it does / 기능

- Lists recent 5 sessions with first user message preview
- Lets you select a session to recover
- Extracts last 3 user messages from the selected session
- Summarizes what you were working on, last request, and current status

---

- 최근 5개 세션을 첫 번째 사용자 메시지와 함께 목록으로 표시
- 복구할 세션을 선택
- 선택한 세션에서 마지막 사용자 메시지 3개를 추출
- 무엇을 하고 있었는지, 마지막 요청, 현재 상태를 요약

## Install / 설치

```
/plugin install --source github:juniqlim/claude-recap-plugin
```

Or manually copy `skills/recap/SKILL.md` to `~/.claude/skills/recap/`.

또는 `skills/recap/SKILL.md`를 `~/.claude/skills/recap/`에 직접 복사.

## Usage / 사용법

- `/recap` — show recent sessions and pick one / 최근 세션 목록을 보고 선택
- `/recap 1` — recover from the most recent previous session / 가장 최근 이전 세션에서 복구
- `/recap <session-id-prefix>` — recover from a specific session / 특정 세션에서 복구
