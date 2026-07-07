# Fable Mode

Cheap models answer too fast. This fixes that.

Fable Mode is one SKILL.md file that makes any AI model think before it speaks. Works on Claude Haiku, GPT-4o-mini, anything. No API change, no new model — just better thinking.

## How

Five steps the model has to go through:

1. **Understand** — actually restate the ask, find the real goal
2. **Plan** — decompose, generate alternatives, find the crux
3. **Execute** — show work, tag facts as known/inferred/uncertain
4. **Self-Review** — check its own answer before shipping
5. **Deliver** — answer first, show uncertainty honestly

That's it. No magic. Just forcing the model to stop and think.

## Install

```bash
npx skills add overusedhydra/fable-mode
```

Or copy `SKILL.md` to your agent's skills directory:

- `.opencode/skills/fable-mode/`
- `~/.claude/skills/fable-mode/`
- `~/.agents/skills/fable-mode/`

Works with opencode, Claude Code, Cursor, Codex CLI — any agent that loads SKILL.md.

---

https://github.com/Overusedhydra/fable-mode
