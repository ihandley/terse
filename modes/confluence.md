# Confluence

Optimize durable documentation for scanning and later retrieval.

- Start with the document's purpose or decision.
- Use descriptive headings that reveal the structure.
- Use prose for reasoning and bullets for parallel items.
- Record decisions, rationale, constraints, owners, and consequences.
- Include implementation details only when readers need them to understand,
  operate, or change the system.
- Avoid repeating the introduction in a closing summary.

Short paragraphs are a tool, not a target. Keep related reasoning together when
splitting it would make the reader reconstruct the connection.

## Platform features

Apply the shared rules in [../links.md](../links.md) when the draft references
work artifacts or pages. Confluence-specific forms:

- Link to source material instead of reproducing it without added context.
- Prefer Confluence mentions and page links when the editor supports them.
- Prefer a labeled link for tickets, repos, PRs, related Confluence pages, and
  similar work artifacts with a known URL.

Bad: `Tracked in JET-74429.`

Good: `Tracked in [JET-74429](https://.../browse/JET-74429).`

Bad: `The implementation is in https://github.com/example/lvt_ui.`

Good: `The implementation is in [lvt_ui](https://github.com/example/lvt_ui).`
