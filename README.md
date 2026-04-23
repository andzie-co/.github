# .github

Org-wide community health files for `andzie-co`.

This repo is the **fallback** for any repo in the org that does not provide its own:

- `profile/README.md` — rendered at https://github.com/andzie-co
- `.github/pull_request_template.md` — default PR template
- `.github/ISSUE_TEMPLATE/*` — default issue forms
- `SECURITY.md` — vulnerability reporting policy
- `CODEOWNERS` — fallback review routing when a repo has none

## Conventions

- Main branch: `main`
- Destructive operations require written owner approval (see `SECURITY.md`).
- Third-party GitHub Actions MUST be pinned to a full commit SHA, not a tag.
- Secrets live at environment or org scope — never committed.

## Ownership

Owned by `@andzie-co/platform`.
