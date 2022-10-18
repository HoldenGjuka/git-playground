# Git Playground Commands and Notes

### Author: Holden Gjuka

## Tracking commands:

0. git help \[command]
1. git status (shows staged files)
2. git branch (shows branches)
> - append \[branchname] to create a new local branch 
> - asterisk next to listed branch name mean this is the active branch
3. git checkout \[branchname]
4. git merge \[branchname]
> - Merges the branchname branch into the active branch
5. git push -u origin \[branchname]
> - Pushes a new remote branch from local (creates a new remote branch)
6. git push origin --delete \[remotebranchname]
7. git checkout origin/main
> - Make experimental changes and commit them, and discard by switching to another branch or use the switch command to save the commits to a new branch. (Detached head)
8. git switch -c \[newbranchname]
9. git reset HEAD --hard
10. git clean -fd
> - Resets local workspace to last commit, cleans out added files


## Notes:
- Initial push sends all of the commits made

## Resources
- [Rudimentary Markdown Syntax Cheat Sheet](https://www.collectiveray.com/images/2021/05/markdown-cheat-sheet-basic-elements.jpeg)
- [Markdown Basic Syntax Doc](https://www.markdownguide.org/basic-syntax)
- [.gitignore cheat sheet](https://github.com/kenmueller/gitignore)

## Look Into
- git reset
- git cherry-pick
- git revert
- git lens plugin (vscode)