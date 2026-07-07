# Fable Mode

Fable 5 costs $50/MTok. This gives you the same thinking discipline for free.

Claude Fable 5 is Anthropic's most capable model — it plans, verifies, tests its own work, and thinks adaptively before answering. That "always-on thinking" is what makes it good.

Fable Mode is one SKILL.md file that distills that same process so any model can follow it. Haiku, GPT-4o-mini, Sonnet, whatever. Same thorough thinking. No $50/MTok bill.

## How it works

Five phases the model must complete before delivering an answer:

1. **Understand** — restate the ask, catalog constraints, detect pattern-matching traps
2. **Plan** — decompose, generate alternatives, find the crux
3. **Execute** — show intermediate work, tag facts KNOWN/INFERRED/UNCERTAIN
4. **Self-Review** — verify by a different method, hunt counterexamples
5. **Deliver** — answer first, show uncertainty honestly

Effort dial T1/T2/T3 so trivial questions skip the protocol entirely.

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

> "Cheap models answer too fast. This fixes that."
