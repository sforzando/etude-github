# GitHub Flow

## What Is GitHub Flow?

GitHub Flow is a lightweight, branch-based workflow designed for teams that
ship regularly. It has six steps:

1. **Create a branch** from `main`.
2. **Add commits** to your branch.
3. **Open a Pull Request** to start a discussion.
4. **Review and discuss** the changes with collaborators.
5. **Deploy** from your branch to verify in production (optional).
6. **Merge** the Pull Request into `main`.

## Branch Naming Conventions

Please use descriptive, lowercase names separated by underscore, with a 3-digit issue number padded with zeros at the beginning:

```text
002_add-login-page
005_broken-nav-link
007_update-readme
```

## Opening a Pull Request

1. Push your branch to GitHub:

   ```bash
   git push origin your-branch-name
   ```

2. Open a Pull Request on GitHub.
3. Fill in the title and description.
4. Request a review from a teammate.

## Merging a Pull Request

Once the PR is approved:

1. Click **Merge pull request** on GitHub.
2. Delete the remote branch.
3. Pull the latest `main` locally:

   ```bash
   git switch main
   git pull origin main
   ```

## Practice Exercise

1. Create a new branch: `feature/my-first-pr`.
2. Add a new Markdown file to `docs/`.
3. Commit the change with `npm run commit`.
4. Push the branch and open a Pull Request on GitHub.
5. Ask a peer to review and merge it.
