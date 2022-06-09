# Github actions

## publish_release.yml

Used to automatically publish a new version of the library when a new tag has been pushed on main branch
### Steps to deploy
1. Move to main branch<br>
  `git checkout main`
2. Change version in package.json (e.g. from 1.0.0 to 1.0.1)<br>
  `npm version 1.0.1`
3. After commit, push changes to remote branch with tag<br>
  `git push --follow-tags`

### Docs

[Github actions contexts](https://docs.github.com/en/actions/learn-github-actions/contexts)

[Events that trigger workflows](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows)

[Defining outputs for a job](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#example-defining-outputs-for-a-job)

