# .github

Organisation defaults for MONEI repos.

- `PULL_REQUEST_TEMPLATE.md`: the PR template of every repo that has no template of its own.
- Cross-repo PR order: write `Depends-on: MONEI/<repo>#<n>` lines in the PR body. The `PR dependencies` check blocks the merge until each upstream PR is merged and deployed. See [MONEI/ci-service](https://github.com/MONEI/ci-service#pr-dependencies).
