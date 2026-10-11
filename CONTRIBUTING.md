# Contributing at HTech & Designs

1. **Plan first**: non-trivial work starts with a short spec or plan linked in the ticket.
2. **Branch** from `dev` (or `main` if the repo has no `dev`): `feat/<ticket>-<slug>`, `fix/<ticket>-<slug>`.
3. **Commit** with Conventional Commits: `feat: ...`, `fix: ...`, `chore: ...`, `docs: ...`, `test: ...`.
4. **Pull request** using the template. Keep PRs small. At least 1 approving review; CODEOWNERS review for owned paths.
5. **CI must pass** (build, lint, tests, secret scan) before merge. Squash-merge, delete the branch.
6. **Never push directly to `main`**. Never commit secrets.
