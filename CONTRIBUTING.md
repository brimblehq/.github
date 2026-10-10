# Contributing to Brimble

Thanks for considering a contribution. This is the default guide for all
[@brimblehq](https://github.com/brimblehq) repositories. If a repository has its
own `CONTRIBUTING.md`, follow that one instead.

## Code of conduct

By participating, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## How to contribute

1. **Find or open an issue.** For bugs and feature requests, check existing
   issues first. For large changes, open an issue to discuss the approach before
   writing code.
2. **Fork and branch.** Fork the repo, then create a branch from `main`:
   `git checkout -b feat/short-description`.
3. **Make your change.** Keep it focused — one change per pull request.
   - Match the repo's existing style (run its linter/formatter before pushing).
   - Add or update tests where the repo has them.
   - Don't commit secrets, `.env` files, or build artifacts.
4. **Write a clear PR.** Fill in the pull request template: what changed, why,
   and how to verify it. Link the issue it closes.
5. **Respond to review.** Maintainers may ask for changes. Push follow-up
   commits to the same branch.

## Reporting bugs

Use the bug report template. Include:

- What you expected vs. what happened
- Steps to reproduce (minimal if possible)
- Repo, version/commit, OS, and relevant logs or screenshots
- Project/service ID or deployment URL if it's a platform issue (never post
  secrets — redact API keys and tokens)

Security vulnerabilities are **not** handled via public issues — see
[SECURITY.md](SECURITY.md).

## Suggesting features

Use the feature request template. Describe the problem, the proposed solution,
and any alternatives you considered. Small, well-scoped proposals get reviewed
fastest.

## Development setup

Each repository documents its own setup — check that repo's `README.md` for
prerequisites and commands. As a rule:

- Never commit real credentials. Copy `.env.example` to `.env` where provided.
- Keep pull requests small and self-contained.
- Delete dead code instead of commenting it out. Git remembers.

## License

By contributing, you agree that your contributions will be licensed under the
repository's license (typically [Apache-2.0](LICENSE)).
