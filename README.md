### Git Cheat Sheet

Summary of useful 'git' commands.

### Basic Commands
* 'git init' - Initialize local git repository
* 'git status' - Show status of working directory
* 'git add .' - add everything in current directory to git index
* 'git commit -m "some message"' - commit current work to local repository
* 'git log' - shows every commit in history
* 'git log --oneline' - show git commit history
* 'git config -l' -  List git configuarations

### Branching Commands
* 'git branch' shows current branch location
* 'git branch someBranch' creates new branch called that
* 'git checkout someBranch' swaps to that branch
* 'git checkout -b otherBranch' - create and checkout
* 'git pull origin main' - pull remote 'main' into current Branch
* 'git push origin newbranch' - push current commited branch to remote repo

### Remote Commands
* 'git remote add origin URL' - set remote repo alias 'origin' for git 'url'
