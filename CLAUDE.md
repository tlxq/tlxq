# tlxq

The GitHub profile README (public, shown on github.com/tlxq). Facts and names come from cv.tex.

## Rules
- One branch and one PR per change; `mise run check` must pass on the PC before merge (squash), and the PR says so.
- `mise run check` is the whole check (the pre-push hook runs it; there is no GitHub CI). `mise run format` formats.
- Visible text follows `workflow:signum`.
- Safe to make public at any time: test and seed data are made up (names, emails, a neutral public place). Real
  accounts, family, home and device names never go in files, commit messages, issues or PR text. Screenshots come
  from demo data and live in `docs/assets/`. `tools/public-guard` checks this at every commit.

## Pointers
- Run it: nothing to run; GitHub renders README.md.
- Deploy: a push to main is live on the profile.
