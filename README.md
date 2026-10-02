# Terse

Rewrites workplace communication to minimize length and maximize signal.

## Layout

```text
terse/
├── SKILL.md          # Objective, workflow, writing rules, final check
├── scripts/
│   └── check-dashes  # Exit 1 if the draft contains an em dash or en dash
├── agents/
│   └── openai.yaml   # Codex picker metadata; model-invoked
├── README.md         # Repository guide
├── voice.md          # Shipped default voice (override with a personal file)
├── anti-ai-tells.md  # Compact LLM-tell scrub (from humanizer patterns)
├── links.md          # Shared link and reference rules
└── modes/            # Medium-specific conventions (includes default)
```

## Supported modes

- `slack`: Direct, scannable, natural tone.
- `pr-comments`: Actionable review feedback, no process narration, no praise.
- `pr-description`: Compact, intent-focused PR summaries under 15 lines.
- `jira`: Durable issue context, acceptance criteria, no filler.
- `confluence`: Scannable documentation, clear headings.
- `email`: Purpose upfront, clear actions.
- `default`: Fallback for unspecified tools.

## Install

```sh
npx skills add ihandley/terse
```

Add `-g` to install for your user instead of the current project. Copy
[`voice.md`](voice.md) to `~/.claude/terse-voice.md` to keep a personal voice;
updates overwrite the installed copy.
