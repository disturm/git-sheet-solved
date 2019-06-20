## 10. Reset The Difference
### Хранятся файлы, diff вычисляется на лету
- `git reset --hard <commit>` - Discards all history and changes back to the specified commit
- `git reset --mixed <commit>` - Undoes all commits afer [commit], preserving changes locally
- `git reset --soft <commit>`
- `git diff <commit> [<commit>]` - Show changes between commits, commit and working tree, etc
- `git difftool <commit> [<commit>]` - Show changes using common diff tools
