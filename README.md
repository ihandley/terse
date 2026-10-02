# Terse

Rewrites workplace communication in a direct, natural engineering voice, per
[`principles.md`](principles.md)'s reader-effort priorities.

## Layout

```text
terse/
├── SKILL.md          # Discovery metadata and execution workflow
├── README.md         # Repository guide
├── principles.md     # Shared priorities, rules, and final check
├── voice.md          # Shipped default voice (override outside the plugin)
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
