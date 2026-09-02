# CLAUDE.md

## What this repo is

A sandbox for practicing Git and GitHub workflows. There is no application code,
no build, and no test suite. Experiments here are meant to be created, broken,
and discarded.

See [README.md](README.md) for the landing-page description of the repo.

## Workflow rules

These exist for practice. Follow them even when a change is trivial.

- Every change reaches `main` through a pull request, even a one-line one.
- Do not merge a PR unless asked — opening it is usually the point of the exercise.
- Delete the branch after merge.

## Conventions

- Commit messages: imperative mood, one line ("Add README badge", not "Added...").
- Markdown files only, unless an exercise calls for something else.

## README conventions

- Keep `README.md` accurate: if a change alters what the repo is or how it's used,
  update the README in the same PR.
- `README.md` is for humans landing on the repo (what it is, how to use it);
  `CLAUDE.md` is how we work in here. Keep the two from contradicting each other.
- The `What I'm practicing` checklist in the README tracks real progress. Tick an
  item only once it has actually been done in this repo.
- Same style as everything else: one H1, `##` sections, imperative mood, blank
  lines around headings and lists. Use relative links between repo files.

## Notes for Claude

- Explain the git and `gh` commands being run. Learning the workflow is the goal,
  so a working result with no explanation misses the point.
- Prefer `gh` CLI over asking the user to click through github.com.
