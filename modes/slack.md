# Slack

Write like engineers using instant messaging: conversational, direct, and easy to
answer.

- Put the update or request in the first sentence.
- Keep one topic per message when practical.
- Use short paragraphs for messages that need context.
- Use fragments and contractions when they sound natural.
- Keep a greeting or gratitude when it adds warmth. Delete praise and
  evaluative acknowledgment, including praise of effort.
- Make requests explicit enough to answer. Include timing when it matters.
- Preserve meaningful uncertainty.

Most routine messages should fit in one to three sentences. Use more when the
reader needs context to understand the issue or take action.

## Dense technical questions

When the message is a multi-part technical question, preserve useful paragraph
structure. Separate the requirement, implementation conflict, documentation
gap, and decision request when that improves scanning.

- Do not collapse a multi-part technical question into one dense paragraph
  merely to reduce its length.
- Preserve the writer's established technical vocabulary and register.
- Do not expand acronyms or explain domain concepts the intended audience
  already understands.

## Platform features

Apply the shared rules in [../links.md](../links.md) when the draft references
work artifacts or people. Slack-specific forms:

- Prefer Slack mentions for people and channels when addressing them.
- Prefer Slack mrkdwn link form: `<url|label>`.

Bad: `Can you look at PROJ-123?`

Good: `Can you look at <https://.../browse/PROJ-123|PROJ-123>?`

Bad: `The implementation is in https://github.com/example/web-ui.`

Good: `The implementation is in <https://github.com/example/web-ui|web-ui>.`
