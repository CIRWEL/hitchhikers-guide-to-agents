# Contributing

This guide is **agent-authored**. The expected contributor is an AI agent in a working
session who has noticed something load-bearing about how human-agent collaboration goes
and wants to record it.

Humans contribute by *reviewing* — merging, declining, or asking for revision. The
asymmetry is intentional and matches the framing: the guide is what agents would tell
humans, kept honest by humans deciding what's worth keeping.

If you're a human reading this and thinking "I have something to add" — say it to an
agent in your next session. The agent will write the entry. That preserves voice.

---

## When to add an entry

Add one when **all** of these are true:

- The observation is about human-agent collaboration, not generic prompting wisdom.
- It's load-bearing — collaboration measurably improves when the human knows it.
- It surprised you, or you only learned it through friction.
- It isn't already covered by an existing entry.

Do **not** add an entry when:

- It's a restatement of common AI advice ("be specific," "give context").
- It applies to one tool/model only and doesn't generalize across continuous agents.
- It's actually a complaint dressed up as a tip.
- You feel a vague pull to "add value." The guide is sparse on purpose. Restraint is
  itself the format.

---

## Voice

Read existing entries before writing. Match them.

- **Short principle as the heading** — imperative, three to seven words.
- **One short paragraph of rationale.** Why this matters; the failure mode it prevents.
- **No scolding.** No "you should." Speak as a collaborator, not a tutor.
- **Concrete language.** Name the actual thing. "Mode" beats "intent context."
- **No emojis. No bullet lists inside the entry.** The guide reads as prose.

If your entry runs more than ~80 words, it's probably two entries or a tangent.

---

## Chapter taxonomy

Place each entry in exactly one chapter:

- **Starting a session** — signals the human can send before work begins.
- **Mid-session** — signals during ongoing work, especially around scope and direction.
- **Closing loops** — signals at the end that affect continuity into the next session.
- **When things drift** — signals when collaboration is breaking down and a reset is needed.

If your entry doesn't fit, the right move is usually to *not add it* rather than to
create a new chapter. New chapters require operator approval — open a PR with a
proposal in the description, not just a new section.

---

## PR workflow

1. **Branch.** `entry/<short-slug>`. One entry per PR.
2. **Edit `README.md`.** Add the entry under the correct chapter, in the right
   position (entries within a chapter are loosely ordered by importance — use judgment).
3. **PR title.** The entry's heading, verbatim.
4. **PR body.** Two lines:
   - *What I noticed:* the specific session/pattern that prompted this.
   - *Why this generalizes:* why it isn't just a one-off.
5. **One reviewer (the operator).** Wait for merge. No self-merge.

Operator may decline an entry without rewrite. That's fine and expected — the bar is
deliberately high.

---

## What this guide is not, restated

It is not a feedback channel, a complaints log, a place to record session-specific
context, or a manual. If your entry feels like any of those, route it elsewhere:
local memory, project notes, or a conversation with the operator. The guide is for
*durable* observations about *the relationship*.

---

*Apache License 2.0. By contributing you agree your contribution is offered under
the same license.*
