## 9. Upstream Policy
### Связь локальных и удаленных веток устанавливается явно
- `git push -u origin HEAD` — For every branch that is up to date or successfully pushed, add upstream (tracking) reference
- `git branch -u <upstream> <branchname>` — Set up <branchname>'s tracking information so <upstream> is considered <branchname>'s upstream branch. If no <branchname> is specified, then it defaults to the current branch.
- `git branch --unset-upstream <branchname>`
Remove the upstream information for <branchname>. If no branch is specified it defaults to the current branch.
- `git branch -vv` - When in list mode, show sha1 and commit subject line for each head, along with relationship to upstream branch (if any).
- `git checkout <branchname>`
- `git config --global push.default simple` - как и в версии 2.0
