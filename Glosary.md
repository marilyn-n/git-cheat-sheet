### Review History

* git log
  _Shows history of commits with detail description_

* git log --oneline
  _Shows history (commitId and message) in one line_

* git show [commit]

### Make changes

* git status
* git add [file]
  _Add a file_
  
* git commit --message
  _Name a commit_

* git stash
* git diff

### Branches

* git checkout -b <branchName> 
  _Create new branch_

* git checkout <branchName>
  _Move to other branch_

### Rewriting History

* git rebase
  _Reapply commits on top of another base tip_

* git rebase --interactive
  options: 
   * --continue  _Continue the rebase process_
   * --skip _Next step_
   * --abort  _Undo_
   * --quit _Exit_
   * --edit-todo 
   * --show-current-patch

### Synchronize Changes

* git pull
* git push
* git merge
* git fetch


