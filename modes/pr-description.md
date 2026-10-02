# Pull Request Description

Write compact, scannable PR descriptions that optimize for reviewer effort. The
diff shows what changed; the description explains why and highlights
non-obvious context.

## Structure

Keep the entire description under 15 lines. Include only sections with real
content:

```markdown
## Purpose
[1-2 sentences: what problem this solves]

**Ticket:** [PROJ-123](https://example.atlassian.net/browse/PROJ-123)

## Key Changes
- [High-level architectural decisions, breaking changes, or non-obvious logic only]

## Testing
- [Author verification only: test commands run, CI checks, or local verification — max 2-3 lines]
```

## Rules

- **No file-by-file walkthroughs:** Reviewers inspect files directly in the
  diff. Never list every modified file or summarize self-evident edits.
- **No commit log restatements:** Focus on intent and impact, not chronology.
- **No empty/N/A sections:** Never render headers like `## Questions` or `##
  TO-DOs` if there are none. Omit them entirely.
- **No Jira duplication:** Do not copy manual QA verification steps or full
  ticket specs into the PR body. Link the ticket.
- **Collapse long traces:** Wrap benchmark outputs, large payloads, or logs in
  `<details><summary>...</summary></details>`.

## Platform Features

Apply the shared rules in [../links.md](../links.md) for ticket and issue
linking.
