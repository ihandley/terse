# Voice

Default engineering voice for coworkers: direct, conversational, concrete,
curious, candid. Medium conventions and density first; this file only keeps
useful fingerprints and stops generic "professional" sanding.

## Personal override

Prefer a personal or project voice file when present (first match wins):

1. `~/.claude/terse-voice.md`
2. `<repo>/.claude/terse-voice.md`
3. This file (skill default)

Copy this file to `~/.claude/terse-voice.md` and edit to add your fingerprints.
Do not edit the installed copy — skill updates overwrite it.

## §1 Cadence

- Lead with the real point. No ceremonial intro.
- Concrete observation → why it matters → what you want next.
- Contractions/fragments OK when natural in the medium. Default short; write
  more only when the subject warrants it.
- Close informally. No padded sign-off ("let me know if you have questions!").

## §2 Preserve

Keep when in the source or clearly intended: strong relevant opinions;
specificity; mild human roughness; useful sharp edges (conviction, severity,
humor); mid-thought candid openers ("honestly", "personally") when they carry
the point (not theatrical standalone hooks). Praise is never a useful edge;
delete it per `principles.md`.

## §3 Do not auto-soften

Do not replace vivid wording with corporate euphemism by default:

| Keep | Not |
| --- | --- |
| painful | suboptimal |
| this makes no sense | there may be another perspective |

Soften only for accidental hostility, mind-reading, or derailing the ask.

## §4 Ask, don't order

When directing someone else's work or floating a diagnosis: prefer questions /
invitations over commands and confident claims. Match the author's certainty;
do not inflate it.

| Avoid | Prefer |
| --- | --- |
| Make this change | Consider making this change / What do you think about making this change? |
| I think this is the problem | Could this be the problem? |
| You should X | Would X work here? / Curious if X is worth trying |

Keep a direct claim or request when the author is sure, or the source already
commits. Illocution and epistemic temperature only, not vivid-word sanding (§3).

## §5 Audience

Adjust polish, not identity.

| Audience | Adjust |
| --- | --- |
| Close coworker | More candid; less shared-context explanation |
| Manager / senior | Clear purpose and ask; critique systems/outcomes, not motives |
| Unfamiliar / executive | Concise; keep 1–2 distinctive specifics; cut tangents first |

## §6 Work references

- Do not bury a ticket ID as a mid-sentence modifier ("I fixed PROJ-123 in auth").
  State it plainly or lead with it.
- Ticket/repo references → inline links per [links.md](links.md).

## §7 Never invent

Do not invent personal experiences, opinions, commitments, or emotional
reactions the author has not supplied. Preserve uncertainty when context is
incomplete.
