---
name: terse
description: >-
  Rewrites or drafts workplace text for clarity, density, and a natural
  engineering voice. Use for Slack, email, Jira, Confluence, PR text, or any
  outward-facing draft, and when rewriting pasted text in-session.
tags:
  - writing
  - communication
metadata:
  author: ian.handley
  audience: all-guild
---

# Terse

Write like an experienced software engineer to coworkers: direct, precise,
natural, easy to read.

## §1 Workflow

1. Read [principles.md](principles.md).
2. Identify the medium; read matching [`modes/`](modes/) file, else
   [`modes/default.md`](modes/default.md). Ask which medium only when the choice
   would materially change the result.
3. If the draft mentions tickets, repos, PRs, Confluence pages, URLs, or
   people/channels to mention → also read [links.md](links.md).
4. Load voice (first existing file wins):
   - `~/.claude/terse-voice.md`
   - `<repo-root>/.claude/terse-voice.md`
   - [voice.md](voice.md) (skill default)
   Keep fingerprints without sanding useful edges.
5. Preserve original facts, uncertainty, request, and social intent, except
   praise. Delete praise in every medium and intensity.
6. Pick intensity (§2): Normal (default) or Brutal.
7. Rewrite with medium conventions, chosen intensity, and any loaded link rules.
8. Read [anti-ai-tells.md](anti-ai-tells.md); scrub remaining LLM tells.
9. Apply the final check in `principles.md` (§9).

Return only the rewritten text unless the user asks for commentary or
alternatives.

## §2 Intensity

Default Normal. Detect from the request.

| | Keep | Drop |
| --- | --- | --- |
| **Normal** (default) | decision, why-it-matters, request; full principles.md §1 priorities | filler only |
| **Brutal** | decision, request, blocker/status | rationale, alternatives, mechanism, pedagogy |

Brutal triggers: "brutal", "cut harder", "decision + ask only", "strip
rationale", "much/way shorter", or a length budget ("3 sentences", "one line").
A shorten request is an intensity signal, not a reformat: drop optional why,
never repack the same why into fewer sentences.

Ambiguous shorten request with no intensity cue → ask Normal vs Brutal, only
when the two outputs differ materially.

Brutal keeps voice.md, punctuation (§6), and anti-ai-tells. It overrides only
principles.md §1's "shorter is worse if it drops context" and §7 optional-info
retention: the reader has context, so do not re-teach it. If the ask is
incomprehensible without one clause of why, keep that one clause.
