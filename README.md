# Github actions publish workflow

## Deployment

1. Change version in package.json<br>
  `npm version 1.0.1`
2. After commit, push change to remote branch with tag<br>
  `git push --follow-tags`

## Docs

[Github actions contexts](https://docs.github.com/en/actions/learn-github-actions/contexts)

[Events that trigger workflows](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows)

