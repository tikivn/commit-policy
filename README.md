# commit-policy
Git Commit Toolkit that following the Jira commit policy

This repo never publish to NPM. Please install by

`npm i -g https://github.com/tikivn/commit-policy`

## Easy to use

example current branch: OPS-1234-....

- `c feature 'message'` => alias to `git commit -m 'feat(OPS-1234): message'`
- `c fix 'message'` => alias to `git commit -m 'fix(OPS-1234): message'`

you can also use with https://github.com/Gherciu/commitlint-jira
