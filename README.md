# aifyi

This repository contains a small static site (HTML pages) from the local workspace.

How to push this to GitHub

Option A — using GitHub CLI (recommended):

1. Authenticate: `gh auth login --web`
2. Create repo and push: `gh repo create <owner>/<repo-name> --public --source=. --remote=origin --push`

Option B — using a Personal Access Token (PAT):

1. Create a repo via the GitHub web UI or API (use a PAT with `repo` scope).
2. Add the remote and push:

```
git remote add origin https://github.com/<username>/<repo-name>.git
git branch -M main
git push -u origin main
```

If you'd like, I can create the remote repo for you — provide permission via the `gh` CLI auth or a PAT and I'll run the commands.

Files in this repo:
- `page.html` and several other HTML pages and folders (static site)

License: add a license file if you want this published publicly.
