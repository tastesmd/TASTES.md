# TASTES.md

The missing layer between SOUL.md and SKILL.md.

An open standard for encoding aesthetic judgment into AI agents.

## What it is

Agents have identity (SOUL.md) and capability (SKILL.md). They lack taste — the trained capacity to distinguish what is worth making from what is merely possible.

TASTES.md is a compact file (≤500 tokens) that encodes aesthetic constraints your agent applies to all creative work: what to reject, what to require, how to decide when ambiguous.

It is not written by you and handed to the agent. It is **distilled from your collaboration** — mined from memory logs and refined through conversation.

## Install

```bash
mkdir -p ~/.openclaw/skills/tastes && curl -fsSL https://tastes.md/skill.md -o ~/.openclaw/skills/tastes/SKILL.md
```

Then say to your agent:

> Build my TASTES.md

## What TASTES.md looks like

```markdown
# TASTES.md

## REJECT
- Never use gradients as decoration.
- Never exceed 250ms for UI transitions.
- Never use opacity-on-white to simulate gray.

## REQUIRE
- Use exact hex values for grays: `#1a1a1a` `#2a2a2a` `#6b6560`.
- Pair one display face with one monospace face.
- Maintain minimum 40% negative space ratio.

## WHEN AMBIGUOUS
- Subtract rather than add.
- Orient toward: Zumthor (spatial), Sakamoto (temporal), Teenage Engineering (tactile).
```

## How it works

1. **Mine** — Agent searches MEMORY.md and old daily logs for aesthetic signals buried across months of interaction.
2. **Talk** — Agent shares what it found, asks you to confirm, correct, expand.
3. **Draft** — Agent writes TASTES.md in declarative form. You approve.
4. **Apply** — Agent loads TASTES.md during creative work and enforces its constraints.
5. **Evolve** — Say "update my taste" anytime. Agent re-scans memory, proposes changes.

## Links

- **Website** — [tastes.md](https://tastes.md)
- **Manifesto** — [English](MANIFESTO.md) · [中文](MANIFESTO_ZH.md)
- **Skill file** — [skill.md](https://tastes.md/skill.md)

## License

MIT-0 — Taste cannot be owned. Only practiced.

