<!-- @format -->

# Contributing to MrewyOrg

Contributions to our projects are welcome. Follow the target repository's README and contribution
guide first; these shared guidelines apply when it has no project-specific instructions.

## Issues and pull requests

- Search existing issues and pull requests before opening a new one.
- Report bugs in the affected repository with reproduction steps, expected and actual behavior, and
  relevant version information. Remove credentials and personal data from logs.
- Explain the problem and proposed behavior when suggesting a feature.
- Keep pull requests focused. Describe the change, link related issues, and include validation.
- Follow our
  [code of conduct](https://github.com/MrewyOrg/.github/blob/main/.github/CODE_OF_CONDUCT.md).

Use English for issues and pull requests.

## Working on this community repository

Use the Node.js version in `.nvmrc` and install the locked dependencies. Format and check changes
before submitting:

```sh
npm ci
npm run prettier
npm run check
```

For changes to other projects, run the checks documented in that repository.

Git hooks format and lint staged files and check commit messages. Use scoped conventional commits,
such as `docs(profile): update project links`. Hooks supplement the full `npm run check` validation;
record results or limitations in your pull request.
