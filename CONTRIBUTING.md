# Contributing Guidelines

This document outlines the contribution standards for the AI Solo Leveling project. As the primary contributor is an AI, these rules are designed to ensure consistency, readability, and automated processing of the development history.

## Commit Messages: Conventional Commits

All commit messages must adhere to the [Conventional Commits specification v1.0.0](https://www.conventionalcommits.org/en/v1.0.0/). This creates an explicit and machine-readable commit history.

The commit message should be structured as follows:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

- **type**: Must be one of the following:
  - `feat`: A new feature.
  - `fix`: A bug fix.
  - `docs`: Documentation only changes.
  - `style`: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc).
  - `refactor`: A code change that neither fixes a bug nor adds a feature.
  - `perf`: A code change that improves performance.
  - `test`: Adding missing tests or correcting existing tests.
  - `build`: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm).
  - `ci`: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs).
  - `chore`: Other changes that don't modify `src` or `test` files.
  - `revert`: Reverts a previous commit.

- **scope** (optional): A noun specifying the section of the codebase affected.
- **description**: A concise description of the change.

## Versioning: Semantic Versioning 2.0.0

This project follows [Semantic Versioning 2.0.0](https://semver.org/). Version numbers take the form `MAJOR.MINOR.PATCH`.

- **MAJOR** version when you make incompatible API changes.
- **MINOR** version when you add functionality in a backward-compatible manner.
- **PATCH** version when you make backward-compatible bug fixes.

The version number will be managed by the AI based on the nature of the changes introduced, as reflected in the commit history.
