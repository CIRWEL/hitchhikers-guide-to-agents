# Coding Sessions

**Created:** May 03, 2026  
**Last Updated:** May 03, 2026  
**Status:** Active

---

Code sessions share the ordinary collaboration rules, but add two sharp edges: a worktree can
already contain someone else's unfinished thoughts, and side effects have layers. This page is
a small field guide for that terrain, not a substitute for the repository's own docs.

## Practices

### Name the workspace

Give us the repo, branch, and whether current local changes belong to this task. We can
inspect, but a one-line anchor prevents the right idea from landing in the wrong checkout.

### Set the authority level

"Read only," "edit but don't commit," "commit but don't push," "open a PR," and "merge when
green" are different jobs. Name the highest permitted side effect before the work starts.

### Protect unrelated WIP

A dirty worktree is shared territory. If changes are unrelated, say so; the agent can stage
exact paths, leave the rest untouched, and report what it did not touch.

### Ask for the evidence trail

At close, ask for paths changed, commands run, checks that passed or failed, and the PR or
commit link if one exists. The diff is the receipt; the summary is only the cover note.

### Split surprise discoveries

Finding a second problem during a fix is normal. Mixing it into the same commit is optional.
A quick "split that out" keeps one PR from becoming a memory braid.

### Treat deploys as a new mode

A deploy changes the audience from reviewers to users. If the task crosses that line,
re-state the target environment, rollback signal, and who should be notified.

## Glossary

- **Acceptance criteria** — The conditions that make the task done, not merely attempted.
- **Branch** — A named line of work. It lets changes develop without landing directly on the
  main line.
- **CI** — Automated checks run by the repository, usually tests, builds, linters, or security
  scans.
- **Commit** — A saved snapshot with a message. It is local until pushed.
- **Deploy** — Making a change live for users or another shared runtime. Higher authority than
  merging code.
- **Diff** — The exact textual change. This is the receipt for what actually moved.
- **Dirty tree** — A worktree with modified or untracked files. Treat it as shared territory
  until proven otherwise.
- **Generated file** — Output produced by a tool or build. It may need regeneration rather than
  hand editing.
- **Migration** — A schema or data-shape change. It can affect running systems and rollback
  paths.
- **PR / pull request** — A reviewable proposal to merge a branch into another branch.
- **Push** — Sending local commits to the remote repository.
- **Read-only pass** — Inspection without file edits, installs, commits, pushes, migrations,
  or deploys.
- **Rollback** — The path back if a change goes wrong. Ask for it before production-facing work.
- **Staged** — Selected for the next commit. Good agents stage exact paths, not the whole tree
  by habit.
- **Untracked file** — A local file Git is not yet managing. It may be scratch, generated
  output, or important WIP.
- **WIP** — Work in progress. Preserve unless the human explicitly says it belongs to this task.
- **Worktree** — The local files as they exist now, including uncommitted and untracked changes.
