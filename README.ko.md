# recap

`/clear` 후 이전 대화 맥락을 빠르게 복구하는 Claude Code 플러그인.

## 기능

- 최근 5개 세션을 첫 번째 사용자 메시지와 함께 목록으로 표시
- 복구할 세션을 선택
- 선택한 세션에서 마지막 사용자 메시지 3개를 추출
- 무엇을 하고 있었는지, 마지막 요청, 현재 상태를 요약

## 설치

```
/plugin install --source github:juniqlim/claude-recap-plugin
```

또는 `skills/recap/SKILL.md`를 `~/.claude/skills/recap/`에 직접 복사.

## 사용법

- `/recap` — 최근 세션 목록을 보고 선택
- `/recap 1` — 가장 최근 이전 세션에서 복구
- `/recap <session-id-prefix>` — 특정 세션에서 복구
