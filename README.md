# kai-dot

A starting workspace for development tasks in Codex cloud.

## Working in the cloud environment

The repository is checked out at `/workspace/kai-dot`. Use that checkout for
tasks; cloud tasks already run in an isolated environment.

Read `AGENTS.md` before making changes. No application stack, dependencies,
services, or test suite have been selected yet. Add those when a task requires
them, and document the installation, startup, and validation commands here.

## Initial readiness checks

```sh
cd /workspace/kai-dot
git status --short
git ls-remote --exit-code origin refs/heads/main
```

These commands check checkout state and access to the configured branch. They
do not validate an application. No credentials are required beyond the
platform-provided GitHub access for this initial workspace.
