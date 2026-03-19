# Git-and-Github

## Explain Version Control
Version control is a system that helps in tracking every change made to a file over time, making it possible to:
- See who changed what and wheen they changed it
- Go back to the previous version of a proect
- Work on/with different features simultaneously, without breaking anything
- Merge multiple people's work together.

### Explain the difference between Git and Github
1. **Git** is the tool/engine used in tracking changes made to a file, while
2. **Github** is the cloud platform that helps in the sharing and collaboration of files.

#### Github Alternatives
- Gitlab
- Bitbucket
- Codeberge

##### Explain the difference between Git-fetch and Git-pull
1. **Git-fetch** is a command used to tell **Git**, download my changes but **don't** apply them yet (safe preview).
2. **Git-pull** is a command used to **download** changes and **merge** them immediately (fetch + merge in one command).

###### Explain in simple terms git-rebase and the command for it
1. **Git-rebase** is used to move a commit to sit ontop of someone else's latest work (makes history look cleaner and linear).
2. **Git-rebase command**
- ``git checkout (branch name)`` Used to switch to a branch.
- ``git rebase main`` Used to rebase onto the main branch.

###### Explain in simple terms git cherry-pick and the command for it
1. **cherry-pick** used to copy a specific commit from one branch and paste it onto another branch (like copy-paste for commits).
2. **Git cherry-pick command**
- ``git checkout (whatever branch)`` used to switch to a branch.
- ``git cherry-pick (the commit name of the branch you need)`` used to copy the commit to your current branch.
