# Contributing to BMDwiki

BMDwiki grows through focused improvements from BMD Lab students and researchers. Small corrections, clearer explanations, and practical examples are welcome.

## Two repositories

BMDwiki consists of two Git repositories:

| Repository | Default branch | Contains |
| --- | --- | --- |
| `bmd-lab/BMDwiki.git` (this repository) | `main` | Project and governance files: README, CONTRIBUTING, LICENSE |
| `bmd-lab/BMDwiki.wiki.git` | `master` | The Markdown pages rendered as the [BMDwiki](https://github.com/bmd-lab/BMDwiki/wiki) |

Do not add copies of wiki pages to this repository.

## Changing the wiki pages

GitHub does not provide normal pull requests for the wiki repository, and
updating its `master` publishes the wiki immediately.

1. Coordinate the change with a BMD Lab maintainer before starting.
2. Clone `https://github.com/bmd-lab/BMDwiki.wiki.git` (or update your existing
   clone).
3. Create a branch from the current `master` for one focused change.
4. Make your changes, commit with a short, descriptive message, and push the
   branch for review.
5. After review, a maintainer fast-forwards or merges the branch into wiki
   `master`, which publishes it.

## Changing this repository

1. Clone the repository.
2. Create a branch from `main` for one focused change.
3. Make and review your changes.
4. Commit with a short, descriptive message.
5. Push your branch.
6. Open a pull request and briefly explain what changed.

## Never commit

- API keys, passwords, tokens, or other credentials
- Private SSH keys
- VASP `POTCAR` files or licensed potential contents
- Private or unpublished research data unless sharing was explicitly approved
- Student or personal records
- Deployment-local credentials or configuration

If a credential is committed accidentally, report it to a BMD Lab maintainer immediately so it can be revoked and removed correctly. Deleting it in a later commit is not sufficient because it remains in Git history.
