# git-cheatsheet

### **Basic linux comands**:
* `ls` - shows list of files in present folder
* `ls -a` - shows list of hidden files in present folder
* `mkdir name` - creates folder with name
* `cd` - change directory
* `touch name` - creates a file
* `vi names.txt` - chance to edit the file 
  * `esc` - for stop edit 
  * `i` - insert
  * `:w` and then press enter
  * `:q` then press enter
* `cat file.txt` - shows inner content in terminal of the file
* `rm -rf text.txt` - delete file

___

### **initial git setup in terminal** :

* `git init`  -  initial folder setup in  for git

### **Git terminal commands** :
* `git status` - shows the status of the created files wheater they are added or not.
* `git add .` - gets ready for commit
* `git commit -m "reason"` - commits it to the git
* `git log` - knows history of commits
* `git restore --staged names.txt` - comes back to un-staged for commit
* `git reset <CommitNo.>` - then it will delete all commits above it (commits goto staged state)
* `git stash` - all the edited files from beginning will hide
* `git stash pop` - all will come back
* `git stash clear` - clear all edited files
* `git rebase -i < commitno. >` - combines all the above commits into 1 commit
  * `s` will be combines to `pick`
  * to save `:x`

### **GitHub terminal commands** :

* `git remote add origin < link of repo >` - connects repository to local
* `git add origin < link of repo >` - adds just origin of repo to use 
* `git remote -v` - shows the remote repo which was connected
* `git push origin < branch name >` - push code to github
* `git push origin < branch name > -f` - force push code to github
* `git branch < name >` - creates branch
* `git checkout < branch name >` - changes to that branch
* `git clone < link of repo >` - clones the entire repo
* `git branch -D < branch name >` - force deletes branch
* `git branch -d < branch name >` - deletes branch
* `git pull origin < branch name >` - pull code from github
* `git pull upstream main` - pulls from contributing page to our main forked file.
