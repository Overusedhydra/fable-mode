# Fable Mode

A deep-reasoning protocol for AI agents. Forces systematic thinking — understand, plan, execute, self-review, deliver — before answering.

**The problem:** Most AI errors aren't from missing knowledge. They're from skipped thinking steps. Models pattern-match to the first answer and run with it.

**The fix:** One portable SKILL.md that makes any AI think like a frontier model at maximum effort. Install once, better answers every time.

## Quick Install

```bash
# via skills.sh
npx skills add overusedhydra/fable-mode

# or just copy SKILL.md to your agent's skills dir:
# .opencode/skills/fable-mode/SKILL.md
# ~/.claude/skills/fable-mode/SKILL.md
# ~/.agents/skills/fable-mode/SKILL.md
```

## How It Works

Five phases, effort-matched by difficulty:

| Dial | When | What runs |
|------|------|-----------|
| **T1** | Trivial facts, one-line answers | Skip protocol |
| **T2** | Typical questions, small code changes | Understand + Plan + Self-Review (brief) |
| **T3** | Hard problems, debugging, strategy, anything you'll act on | All 5 phases in full |

**Phases:** Understand → Plan → Execute (with intermediate checks) → Adversarial Self-Review → Deliver

## The 7 Failure Modes It Kills

1. Pattern-matching instead of understanding
2. Dropping constraints by the end
3. Fabricated specifics delivered confidently
4. Hidden arithmetic/logic errors
5. Agreeing with wrong premises
6. First-draft as final answer
7. Bullet-point structure substituting for thought

## Who Is This For

- Anyone using AI coding agents (Claude Code, opencode, Cursor, Codex CLI)
- Anyone who's thought "this AI is smart but cuts corners"
- Anyone who wants better answers from the same model

---

[SKILL.md](./SKILL.md) | Works with opencode, Claude Code, Codex CLI, Cursor — any agent that loads SKILL.md
