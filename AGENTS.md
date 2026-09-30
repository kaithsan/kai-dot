# Instructions for Codex tasks

- Work in the existing checkout. Cloud tasks already run in an isolated
  environment; create a Git worktree only when the user explicitly requests it.
- Read the README and inspect Git status before editing. Preserve existing
  user changes.
- This repository starts as a general development workspace. Choose an
  application stack only when the user's task calls for one.
- When adding a project, document its prerequisites and exact installation,
  startup, and validation commands in the README. Use pinned dependencies and
  lockfiles when supported by the chosen package manager.
- Run checks relevant to each change and report what ran, what passed, and any
  blockers. Do not claim application readiness based only on Git access.
- Keep secrets out of source files, logs, and commits. Use cloud environment
  settings for credentials and runtime configuration.
