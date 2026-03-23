# etude-github

GitHub Practice Repository for Beginners

## Overview

This repository is designed to help beginners learn Git, GitHub, and GitHub Flow.
The assumed environment is **macOS**, **Zsh**, and **VS Code**.

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- [Git](https://git-scm.com/)
- [VS Code](https://code.visualstudio.com/)

## Setup

Install dependencies after cloning:

```bash
npm install
```

## Practice Documents

| File | Description |
| ---- | ----------- |
| [docs/01-getting-started.md](docs/01-getting-started.md) | Setting up Git and cloning the repository |
| [docs/02-git-basics.md](docs/02-git-basics.md) | Core Git commands and concepts |
| [docs/03-github-flow.md](docs/03-github-flow.md) | The GitHub Flow branching workflow |

## Tooling

### Linting

Markdown files are linted with [markdownlint-cli2](https://github.com/DavidAnson/markdownlint-cli2).
Rules are configured in [`.markdownlint.json`](.markdownlint.json).

Run the linter manually:

```bash
npm run lint:md
```

The linter also runs automatically on every commit via a Husky pre-commit hook.

### Commit Messages

Commit messages must follow the [Conventional Commits](https://www.conventionalcommits.org/) specification,
enforced by [commitlint](https://commitlint.js.org/).

Use the interactive Commitizen prompt instead of `git commit`:

```bash
npm run commit
```

Examples of valid commit messages:

```text
feat: add login page
fix: correct broken navigation link
docs: update README
```
