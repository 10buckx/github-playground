# CLAUDE.md

## What this repo is

A sandbox for practicing GitHub workflows. There is no application code, no build,
and no test suite. Experiments here are meant to be created, broken, and discarded.

## Workflow rules

These exist for practice. Follow them even when a change is trivial.

- Never commit directly to `main`. Always branch first.
- Branch names: `kebab-case`, describing the change (`add-contributing-guide`).
- Every change reaches `main` through a pull request, even a one-line one.
- Do not merge a PR unless asked — opening it is usually the point of the exercise.
- Delete the branch after merge.

## Conventions

- Commit messages: imperative mood, one line ("Add README badge", not "Added...").
- Markdown files only, unless an exercise calls for something else.

## Notes for Claude

- Explain the git and `gh` commands being run. Learning the workflow is the goal,
  so a working result with no explanation misses the point.
- Prefer `gh` CLI over asking the user to click through github.com.
