# AGENTS.md

## Mandatory repository entry check

Before discovery, editing, branching, committing, or preparing a pull request:

1. Run `git status --short --branch`.
2. Run `git fetch origin`.
3. Compare local `HEAD` with `origin/main` or the approved target branch.
4. If the local branch is behind and the working tree can be preserved safely, fast-forward before starting work.
5. If the branch is diverged, on an unexpected branch, or has uncommitted work that prevents safe synchronisation, stop and report the condition before proceeding.
6. State the local commit and remote commit used as the baseline for the work.

Do not discard local changes in order to synchronise.

This check is mandatory even when the repository was used recently. Work may have been performed in another environment, including ChatGPT Workspace, Codex, Claude, direct GitHub changes, or another local checkout.

Do not assume local architecture or canonical documents are current until the repository has been synchronised.

## Cross-repository source of truth

The canonical F4G repository ownership and placement rules are maintained in:

`Lisa-F4G/f4g-platform/F4G_GitHub_Estate_Map.md`

Use the owning repository for the artefact being changed. Do not duplicate cross-repository source-of-truth documents.
