<!--
Default PR template for andzie-co repos.
Individual repos can override this by adding their own .github/pull_request_template.md.
-->

## What

<!-- One or two sentences: what does this change do? -->

## Why

<!-- Why is this change needed? Link to issue/ticket if applicable. -->

## How to reverse

<!-- Describe the rollback. "Revert the commit" is fine for pure code changes.
     For infra/config changes: specify the exact reversal steps. -->

## Risk / blast radius

- [ ] Pure code change (no infra, no data, no secrets)
- [ ] Touches CI/CD
- [ ] Touches infrastructure (Terraform, DNS, IAM, secrets)
- [ ] Touches production data
- [ ] Destructive / irreversible without backup restore

## Verification

<!-- How was this tested? What did you run? What did you see? -->

## Checklist

- [ ] Self-reviewed the diff
- [ ] No secrets, tokens, or credentials in the diff
- [ ] Third-party GitHub Actions (if added) are pinned to full commit SHAs
- [ ] Docs / runbooks updated if behavior changed
