# Git Commands
## 1. Commit
A commit is a snapshot of a project history. It is used to save changes to a local Git repository. Commits act as a project directory and should be used after each step is complete or a change is made. This is the only way the repository can reflect the changes made to a project.

For example: after adding a new branch to a project in WebStorm, in order for the changes to be reflected in the local repository, the next step would be to use the commit command.

**Git Commit**
![Git Commit](/Images/Git-Commit.png)


## 2. Merge
A merge git command will bring together any changes made to a commit from multiple branches into one, i.e. two local branches can be merged into the master to bring together both commits. The merge command is especially useful to maintain the context of both branches while preserving the history and order.

For example: In the image below, the bugfix commit was created, commits C2 and C3 were merged to come together in the main. 

**Git Merge**
![Git Merge](/Images/Git-Merge.png)

## 3. Checkout
The checkout command is used to switch a current branch and is most commonly used to switch to a different branch making it the new HEAD. The git merge and git checkout commands are often used simultaneously with each other and are both important for git workflows.

For example: In the image below, the git checkout command is used to create a new branch. The command [git checkout -b bugfix] allows us to create a new branch (bugfix) and check it out in one step.
