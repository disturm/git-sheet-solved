## 5. Immutable History
### Нельзя переписать историю — можно создать новую
- `git commit --ammend` - Replace the tip of the current branch by creating a new commit. the message from the original commit is used instead of an empty message. The new commit has the same parents.
- `git rebase <upstream>` — Reapply commits on top of another base tip (из HEAD)
- `git rebase -i <upstream>` Make a list of the commits which are about to be rebased. Let the user edit that list before rebasing.
- `git cherry-pick <commit>` Apply the changes introduced by some existing commits
- `git stash` — Temporarily stores all modified tracked files
- `git stash pop` — Restores the most recently stashed files
- `git stash list` — Lists all stashed changesets
- `git revert <commit>` Revert some existing commits
