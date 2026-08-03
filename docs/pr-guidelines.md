# Pull Request Guidelines (OctoAcme)

Purpose: Standardize PR practices to improve review quality and cycle time.

Size and scope
- Prefer small, focused PRs. Aim for changes that are easy to review; avoid > 400 LOC where practical.
- Break large work into feature branches and multiple PRs.

Description
- Link the related issue and include a short summary.
- Include clear acceptance criteria and testing instructions.
- Note any migrations, config changes, or rollout steps.

Checks before requesting review
- [ ] All CI checks passing (unit, integration, lint)
- [ ] Local smoke test completed for critical flows
- [ ] Tests added or updated for new logic
- [ ] If applicable, add screenshots or recordings for UI changes

Review expectations
- Reviewer to check for correctness, test coverage, security implications, and runtime impact
- Request changes with specific guidance; avoid approving without verifying acceptance criteria
- Author to address comments and re-request review

Merging
- Require at least one approval and passing CI
- Prefer squash-and-merge for small features; use merge commits for long-lived branches if needed
