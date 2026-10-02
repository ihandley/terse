# Jira

Write for a reader who may encounter the issue later without the author's
context. Favor durable facts and actionable structure over narrative.

Include only sections relevant to the work:

- Problem or goal
- Current and expected behavior
- Evidence and reproduction steps
- Scope and constraints
- Acceptance criteria
- Decision, owner, and next step

Use short paragraphs for explanation and bullets for independent facts or
criteria. Preserve technical identifiers, observed behavior, and uncertainty.
Remove chronology unless the sequence explains the cause or helps reproduce the
issue.

## Platform features

Apply the shared rules in [../links.md](../links.md) when the draft references
work artifacts or people. Jira-specific forms:

- Prefer the bare ticket key for same-site Jira issues when the key will
  autolink, e.g. `JET-74429`.
- Prefer a labeled link for external artifacts with a known URL: GitHub repos,
  PRs, Confluence pages, and similar work artifacts.
- Prefer `@` mentions when assigning or calling out a person and the editor
  supports them.

Bad: `See the implementation in https://github.com/example/lvt_ui.`

Good: `See the implementation in [lvt_ui](https://github.com/example/lvt_ui).`
