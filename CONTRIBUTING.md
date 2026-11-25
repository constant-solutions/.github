# Contributing

Constant Solutions repositories are proprietary and mostly private, so contributions are by invitation. If you have access, these conventions apply across our repositories. A repository's own `CLAUDE.md` or `CONTRIBUTING.md` takes precedence.

## Workflow

1. Open or pick an issue before starting non-trivial work.
2. Branch from `main` using a prefix: `feat/`, `fix/` or `chore/` (e.g. `feat/room-swaps-123`).
3. Keep commits atomic, with messages that explain *why*, not just *what*.
4. Open a pull request, fill out the template, and include a closing reference (`Closes #123`).
5. Make sure CI is green, including end-to-end tests where the repository runs them, before merge.

## Data and secrets

- Never commit secrets, keys, tokens, `.env` files or Terraform state.
- Never put real personal data (names, emails, phones, medical or allergy notes, photos, especially of children) in code, fixtures, seeds, screenshots or logs. Use synthetic values and `@example.com` addresses.

## UI changes

Attach before and after screenshots (light and dark themes, 390px wide) to any pull request that changes rendered markup, styling or layout.

## Dependencies

Dependabot opens weekly update PRs. Review them at least monthly, and immediately for critical advisories.

## Security

Do **not** open public issues for vulnerabilities. See [SECURITY.md](SECURITY.md).

## Code of Conduct

By participating, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).
