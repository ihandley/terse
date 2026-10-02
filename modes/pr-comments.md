# Pull request comments

Make each comment specific enough for the author to understand the concern and
act without guessing.

A useful comment identifies the relevant combination of:

- The problem or question
- Why it matters
- The requested change or decision

Do not force every comment into all three parts. "Needs a test" is sufficient
when the missing case is obvious; otherwise name the behavior that needs
coverage.

Prefer direct questions and concrete suggestions. Preserve uncertainty when
raising a possibility rather than reporting a confirmed defect. Delete all
praise, including specific praise, mechanism validation, and positive quality
judgments. Do not move praise into another paragraph or soften it into approval.

Default to as few sentences as the three parts need -- most findings take
1-3. These rules apply equally to the review-level summary body. Do not:

- Restate the diff or change; the author is already looking at it inline.
- Explain why the submitted change is correct. The author wrote it.
- Open or close with a compliment ("Solid fix", "Nice work", "Correct fix for
  a real defect", "useful complement"). Delete it.
- Narrate the act of commenting -- no explaining why this is flagged, no
  crediting/dismissing another reviewer's coverage ("Not re-raising:
  ...", "already covered, not restating here"), no "just making this
  trackable" framing. Say nothing if a prior finding needs no further
  comment.
- Narrate the review process -- "Re-checked fresh", "prior review
  auto-dismissed", "confirmed the failing check is...", "follows
  best-practices", bare "Clean." Process/CI with no author action stays in
  reviewer chat, not the PR.
- Phrase approval as praise. Prefer an empty approve-only body; use `Approved.`
  only when the decision must be explicit.

Write like a peer leaving a comment, not a system justifying its output.

## Platform features

Apply the shared rules in [../links.md](../links.md) when the draft references
work artifacts. GitHub comment forms:

- Prefer GitHub markdown links: `[label](url)`.
- Prefer `#123` / `owner/repo#123` style PR or issue references when they will
  autolink in GitHub.
