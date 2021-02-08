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

**Git Checkout**
![Git Checkout](/Images/Git-Checkout.png)


## 4. Push
The git push command is used to upload a local repository to a remote (central) repository, syncing all new commits in a new branch to the master. This allows all team members to have access to the changes you have made in your local repository. This can be compared to the act of uploading new information to an existing repo.

For example: in the image below, the repo was cloned before commits were made. After adding commits, the changes were pushed to the cloned repo.

**Git Push**
![Git Push](/Images/Git-Push.png)

Collaborating with others in a remote repository, following a push command, a pull and merge command must be applied in the github repository to update with the most recent changes within the local repository.


## 5. Pull
The git pull command is used to pull content from a remote repository to a local repository. This ensures that a user is working on the most recent version of the repo. Merging any updates by collaborators is part of the general git workflow. Git pull is a simpler command that combines the git fetch and git merge commands; combining both steps into one.

For example: In the images below, the git pull command works as the shorthand for git fetch followed by a git merge of the branch that was fetched from the new work done in the remote repo. Results of the [ $ git pull ] can be seen in the second image.

**Git Pull**
![Git Pull](/Images/Git-Pull-1.png)

**Git Pull**
![Git Pull](/Images/Git-Pull-2.png)

Another important thing to note; GitHub allows multiple collaborators to work on the same repository at the same time. However, after adding commits to a local repo, the changes must then be pushed out to the remote. The conflict may occur if multiple collaborators are working on the same repository. Git will protect the changes made by other collaborators by flagging as a conflict once pull and merge function is applied. Users will then be able to correct the conflicts before completing a push, pull, merge into the share GitHub repo. 


## 6. Remote
The git remote command allows you to create, view, and delete links with other repositories. This is very useful when collaborating with other creators. It is done using a repository’s direct URL or the individual’s shortname.

For example, for this mini project, GitHub was used for collaborating with classmates by sharing one common repository. The remote command can be used in this case to connect both collaborators to a single repository.

In the image below, three repositories are presented, your personal repository and two remote repositories. The git remote command acts as an interface for you to access the remote entries in the linked repositories.

**Git Remote Visual Display**
![Git Remote](/Images/Git-remote-visual.PNG)

The remote command is used along with the git push and pull commands (described in previous sections) for complete syncing capabilities.

### a) Adding a Remote
The git remote add command creates a connection to a new remote repository. As briefly referenced above, you can add a remote repo using a short name rather than a complete URL for convenience. The short name can then be used to clone to your local repo.

For example: $ git remote add <name> <url> can be used to add a new remote repository to an existing one.



