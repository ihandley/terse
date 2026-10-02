# Pull request description

The diff shows what changed. The description explains why and the non-obvious context. State verified facts and decisions directly. Do not hedge them.

## Structure

Keep the description under 15 lines. Include a section only when the source contains that content:

```markdown
## Purpose
[1-2 sentences: the problem this solves]

**Ticket:** PROJ-123

## Key Changes
- [Architectural decisions, breaking changes, or non-obvious logic only]

## Testing
- [Test commands run, CI checks, or local verification. At most 2-3 lines.]
```

If the source contains the ticket URL, link the key as `[PROJ-123](url)`. Do not invent the URL.

## Rules

- Do not list every modified file or summarize an edit that is visible in the diff.
- Do not restate the commit log.
- Omit an empty section. Do not write `## Questions`, `## TO-DOs`, or `N/A`.
- Do not copy QA steps or the ticket spec into the body.
- Wrap benchmark output, large payloads, or logs in `<details><summary>...</summary></details>`.

## Platform features

Ticket and issue links follow [../links.md](../links.md). Keep `#123` or `owner/repo#123` when the source already uses that identifier.
