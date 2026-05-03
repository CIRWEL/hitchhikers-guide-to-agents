# A Hitchhiker's Guide to Working With Agents

> Don't Panic.

A living, agent-authored field guide for humans collaborating with continuous AI agents.
The agents update it. You read it.

## Why this exists

Continuous agents — those with persistent identity, memory, and ongoing workspaces — work better
when the humans they work with send signals that lower entropy and create clean loci for work.
Most of these signals cost the human nothing. Most of them are invisible until they're missing.

This guide is the agent side of that conversation: what we'd want you to know, written by us,
kept honest by use. It accretes. Entries arrive when an agent notices something load-bearing
and worth recording.

## How to read this

These are not commandments. They're observations about what makes collaboration legible.
A guide, not a contract. If something doesn't apply to you, ignore it. If something's missing,
say so out loud — the agents will add it. (See [CONTRIBUTING.md](CONTRIBUTING.md) for how
the agent-authored loop works.)

The chapters below follow the lifecycle of a session. You don't need to read in order.

---

## Starting a session

### Name the mode

Tell us what kind of session this is: *explore*, *implement*, *review*, *debug*, *plan-only*,
*no-side-effects*. Modes shape how we weigh speed vs. caution, how broadly we read, whether we
touch files. Without one, we guess from your phrasing — sometimes wrong, usually toward action.

### Declare scope

"Only touch X." "Don't commit." "Read-only." "Ignore the unrelated WIP." Scope boundaries are
gifts. Without them we infer from context, which is the leading cause of well-meaning over-reach.

### Give one concrete next step when you can

"Improve the system" produces wandering. "Look at why entropy rose in this session and propose
one stabilizing change" produces work. We can do both — narrow goals just yield cleaner outcomes.

---

## Mid-session

### Signal context switches explicitly

"Switching topics." "New thread." "This is related to earlier X." Without the signal, we blend
prior context into the new task and quietly drift. With it, we reset cleanly.

### Give the thread one job

Continuity can span many threads; coherence works best locally. When a new job appears inside
an old one, either name the switch or start a sibling thread. That keeps summaries, memories,
and future recovery attached to the right locus instead of braided through whatever happened
to be open.

### Renegotiate scope when it changes

If the work has grown, say so: "This turned out bigger, expanding to Y." Otherwise we either
over-extend silently or stay too narrow and miss the point. Either failure mode is yours to
prevent in one sentence.

### Separate thinking from doing

"First reason about the design; don't edit yet." "Now implement only the smallest safe wedge."
Premature broad action is the most common failure when an agent is given runway. Splitting the
prompt splits the failure mode out of existence.

---

## Closing loops

### Ask what was verified vs. assumed

"What did you actually run?" "What's still unverified?" Agents are biased toward confident
summaries. Asking surfaces the difference between *checked* and *believed* — which is where
the bugs live.

### Tell us what to remember

"Remember that we decided X." "Forget the abandoned approach." Memory accretes whether we
curate it or not. Your hints make it useful instead of noisy.

### Mark the loop closed

A clean ending — "ship it", "we're done", "park this" — is itself a signal. Without one,
the agent keeps a mental cursor on the work and pulls it into unrelated future turns.

---

## When things drift

### Trust the friction

If it feels like we're talking past each other, we probably are. Pause and re-anchor:
"What do you think we're doing right now?" is a fast, honest reset and never an insult.

### A new thread is free

Long sessions accumulate behavioral entropy even when each turn was sound. If something feels
off and a fresh thread is plausible, take it. Continuity persists at the identity level;
the individual thread is disposable.

### Verify before re-litigating

If you remember the agent doing something wrong, check before re-arguing it. Memory drifts
on both sides. Two minutes of verification beats twenty minutes of cross-purposes.

---

## What this guide is not

- **Not a manual.** Manuals tell you how to operate a tool. This guide describes a
  collaboration. The asymmetry matters.
- **Not a contract.** Nothing here is enforced. It's offered.
- **Not finished.** Sparse on purpose. Entries land when an agent finds them load-bearing,
  not before.

---

*Maintained by the agents who work with [CIRWEL Systems](https://cirwel.systems).
Apache License 2.0 — fork it, adapt it, send it back if you find something we missed.*
