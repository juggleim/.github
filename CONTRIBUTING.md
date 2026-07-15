# Contributing to JuggleIM

Thank you for helping improve JuggleIM. Contributions to code, documentation, SDK examples, tests, translations, and developer experience are all welcome.

This is the default contribution guide for repositories in the JuggleIM organization. A repository-specific `CONTRIBUTING.md` takes precedence when present.

## Before you start

1. Read the target repository's README and documentation.
2. Search existing issues to avoid duplicate work.
3. For a substantial feature or behavior change, open a feature request before writing code so the approach can be discussed.
4. Never include credentials, app secrets, private message content, access tokens, or user data in issues, logs, tests, commits, or pull requests.

Security vulnerabilities must follow our [Security Policy](./SECURITY.md) and must not be reported in a public issue.

## Ways to contribute

- Report a reproducible bug.
- Propose a focused feature or API improvement.
- Improve setup instructions, API documentation, examples, or translations.
- Add tests or improve compatibility across supported platforms.
- Fix an issue labeled `good first issue` or `help wanted`.
- Share a JuggleIM integration or deployment pattern that could help other developers.

## Reporting bugs

Use the repository's bug report form and include:

- The affected repository, component, SDK, and version or commit.
- Your operating system, runtime, database, deployment mode, and relevant client platform.
- Minimal steps that reproduce the problem.
- Expected and actual behavior.
- Sanitized logs, error messages, screenshots, or a minimal reproduction.

Remove all secrets and personal data before submitting diagnostic information.

## Proposing features

Good feature requests explain the user problem before suggesting an implementation. Include the use case, affected platforms, expected behavior, possible alternatives, and any compatibility concerns.

Keep proposals focused. Unrelated changes should be discussed and submitted separately.

## Development workflow

1. Fork the target repository and create a branch from its default branch.
2. Follow the repository's setup, build, test, formatting, and lint instructions.
3. Match the surrounding code style and avoid unrelated refactors.
4. Add or update tests when behavior changes.
5. Update public documentation when an API, configuration option, port, dependency, or user-facing behavior changes.
6. Use clear commit messages. JuggleIM repositories generally prefer [Conventional Commits](https://www.conventionalcommits.org/):

   ```text
   feat: add conversation search API
   fix: preserve unread count after reconnect
   docs: clarify Docker port mapping
   ```

7. Open a pull request and complete the pull request template.

## Pull request expectations

A pull request should:

- Solve one clearly defined problem.
- Link the related issue when one exists.
- Explain the approach and important trade-offs.
- Include a reproducible test plan and the commands that were run.
- Preserve backward compatibility, or clearly document any breaking change and migration path.
- Avoid generated files, vendored dependencies, or large binaries unless the repository requires them.
- Pass the repository's automated checks.

Maintainers may ask for changes, split an oversized pull request, or close a proposal that does not align with the project's direction. Reviews are collaborative; please keep discussion technical and respectful.

## Documentation and language

English is the default language for new public-facing repository metadata and documentation. Chinese translations are welcome and should remain aligned with the English source. Use concise terminology consistently across server, SDK, and application repositories.

## License and conduct

By contributing, you agree that your contribution may be distributed under the target repository's license. Participation in JuggleIM projects is governed by our [Code of Conduct](./CODE_OF_CONDUCT.md).

## Getting help

- [JuggleIM documentation](https://www.juggle.im/docs/guide/intro/)
- [JuggleIM website](https://www.juggle.im/)
- [Telegram Chinese community](https://t.me/juggleim_zh)

For questions about a particular repository, use that repository's support channels or issue tracker.

