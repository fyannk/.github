# Contributing

Thanks for taking the time to contribute. This file is the default guide for
my repositories; a project's own `CONTRIBUTING.md`, when present, takes
precedence and usually lists its build and test commands.

## Before you start

- **Small fixes** (typos, docs, obvious bugs): open a pull request directly.
- **Anything larger** (new features, behavior changes, refactors): open an
  issue first so we can agree on the approach before you spend time on code.
- **Security issues**: do not open a public issue. Follow [SECURITY.md](SECURITY.md).

## Making a change

1. Fork the repository and create a branch from `main`.
2. Keep one focused change per pull request.
3. Add or update tests alongside the code they cover.
4. Update the documentation when user-facing behavior changes.
5. Run the project's checks locally (usually `make check` or the equivalent
   listed in the README) and make sure they pass.
6. Open the pull request and fill in the template.

## Commit messages

- Use the imperative mood: "Add retry on WAL fetch", not "Added" or "Adds".
- Keep the first line under about 72 characters.
- Explain *why* in the body when the reason is not obvious from the diff.

## Review

I maintain these projects alone and in my spare time, so reviews may take a
few days. A pull request that is small, tested, and explains its intent gets
merged fastest.

## Licensing

By contributing, you agree that your contribution is licensed under the
license of the repository you contribute to.

## Code of conduct

Participation is governed by the [Code of Conduct](CODE_OF_CONDUCT.md).
