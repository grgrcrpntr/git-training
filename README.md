License number 3.1415926

# Git Training

Welcome to this Git and GitHub training course!

### Prerequisites

1. Download and install Git for Windows: https://gitforwindows.org/
2. Open a GitHub account: https://github.com/ and share your GitHub ID
3. Download and install Visual Studio Code : https://code.visualstudio.com/

### Start here

`git clone https://github.com/grgrcrpntr/git-training.git`

### Agenda

- Work locally:
  - Stage changes with `git add`
  - Commit changes with `git commit`
  - See changes with `git status`, `git log` and `git diff`
- Sync with remote:
  - Share your code with `git push`
  - Update your local repo with `git fetch` and `git pull`
- Work with remote branches:
  - Create a remote branch
  - Switch branches with `git checkout`
- Merge your code
  - Open and merge Pull Requests
  - Drop local branches with `git branch -d`
  - Drop remote branch references with `git remote prune origin (--dry-run)`
- Create releases (use tags)
- Manage a bug on an old Release
  - Create a *hotfix* branch from release tag
  - Fix bug
  - Create a new Release from *hotfix* branch
  - Merge *hotfix* into *develop*, drop *hotfix*
  - Drop local *hotfix* branch and remote branch reference