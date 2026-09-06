# Contributing to EpikodeLabs

Thanks for your interest in improving an EpikodeLabs project.

We build open-source libraries and tools around reactive programming, application architecture, TypeScript, developer tooling, and related infrastructure. Contributions are welcome, but we try to keep changes aligned with each project's design goals rather than growing APIs by accumulation.

## Before you start

Choose the smallest path that fits the change:

- **Small bug fix, typo, documentation correction, or narrowly scoped improvement:** open a pull request directly.
- **Bug with unclear expected behavior:** open an issue first.
- **New API, substantial feature, breaking change, or architectural change:** start a Discussion before implementation.
- **Experimental idea or interoperability proposal:** a Discussion is usually the best starting point.

This helps avoid spending time on work that may conflict with an existing design direction.

## Development

Each repository may have its own setup, build, test, lint, benchmark, or release commands. Follow the repository README and package scripts as the source of truth.

Before opening a pull request:

1. Run the relevant test suite.
2. Run type checking and linting when available.
3. Add or update tests for behavior changes.
4. Update documentation for public API changes.
5. Keep unrelated refactoring out of the same pull request where practical.

## Pull requests

A good pull request explains:

- what changed;
- why the change is needed;
- what behavior is affected;
- whether public APIs or compatibility are affected;
- how the change was tested.

Small, focused pull requests are easier to review and merge.

For large changes, link the Discussion or issue that established the direction.

## API and architecture changes

EpikodeLabs projects tend to be opinionated about architecture and public APIs.

Please discuss significant API additions or structural changes before implementing them. We may prefer a different abstraction, a smaller surface, or no new abstraction at all.

Breaking changes should include a clear motivation and migration impact.

## Tests

Bug fixes should include a regression test when practical.

New behavior should be covered at the level where the behavior is owned. Avoid tests that merely duplicate implementation details.

## Documentation

Documentation contributions are welcome.

Examples should favor clarity and real usage over exhaustive demonstrations. If behavior is surprising or easy to misuse, document the reasoning as well as the syntax.

## Issues

Please search existing issues and Discussions before opening a new one.

For bug reports, include a minimal reproduction whenever possible. For feature requests, describe the problem first; a proposed API can be useful, but it is not required.

## Code of Conduct

By participating in EpikodeLabs projects, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Security

Do not report security vulnerabilities in public issues. Follow [SECURITY.md](SECURITY.md).

## Questions

Use GitHub Discussions for design questions, usage questions, experiments, and ideas that are not yet concrete bug reports.

Thanks for contributing.
