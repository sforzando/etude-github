# Git Basics

## Core Concepts

| Term       | Description                                        |
| ---------- | -------------------------------------------------- |
| Repository | A project folder tracked by Git                    |
| Commit     | A snapshot of changes saved to the history         |
| Branch     | An independent line of development                 |
| Merge      | Integrating changes from one branch into another   |
| Remote     | A version of the repository hosted on a server     |

## Common Commands

### Checking Status

```bash
git status
```

### Staging Changes

```bash
# Stage a specific file
git add README.md

# Stage all changes
git add .
```

### Committing Changes

This project uses [Commitizen](https://commitizen-tools.github.io/commitizen/) to
enforce the [Conventional Commits](https://www.conventionalcommits.org/) format.

Instead of `git commit`, use:

```bash
npm run commit
```

You will be guided through a prompt to write a well-formatted commit message.

### Viewing History

Display the history one line at a time

```bash
git log --oneline
```

Display a list of all branch forks

```bash
git log --graph --all
```

## Practice Exercise

1. Create a new file called `hello.md` in the `docs/` directory.
2. Stage and commit it using `npm run commit`.
3. Move on to [GitHub Flow](03-github-flow.md).
