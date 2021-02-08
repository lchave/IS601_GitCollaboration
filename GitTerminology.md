#  Git Terminology

There are a few terminologies you must become familiar with. We will define some of them along with some useful [Git commands](/GitCommands.md) that will ensure your success when working with [Git](ImprovingProductivityCompetitiveness.md#git).

## Repository
In the simplest terms, you can think of a repository as a folder where you can store all the files related to the project you are working on, along with each file's revision history. Repositories are hosted and centralized in a VCS.

Whenever a developer needs to make a change, they usually checkout the central repository and create a local copy of it. Then they will create a new branch to implement their changes, and once the developer has completed the changes they would check them back in to the central repository.

When you first initialize\create your repository, none of your files are being tracked for changes until you have added them and submit an initial [commit](/GitCommands.md#1-commit).
```
# Navigate to the project folder and Initialize\create your repo
cd [Path]/my_project
git init

# Add files to be tracked for changes
git add *.c
git add LICENSE

# Submit the intial commit
git commit -m 'Intial project version'
```

## Clone vs. Fork
There are different approaches a developer can take when working with a repository. Creating a copy of the repository is one of the many tasks that can be completed in different ways, here we will cover a couple of them and what their differences are.

### Clone
As stated above, clonning a repository creates a copy of it. This copy is created on your local drive and its a full working copy with all files, all brances and all commits. In order to make any changes to the repository you need to be added as a collaborator to the project.

### Fork
Forking a repository also creates a copy, however, this copy is created on your account without all the brances or commits. Despite not being a full copy as a clone, one of the main advantages is that developer could suggest any changes to the main repository without being a collaborator and any changes they made won't affect the original repository unless the approved by the owner.


## Branch
A branch in git can be thought of as a new tab, or a new action. It can also be referenced as a pointer or where focus should be placed in a repository. The git branch command allows the user to create, list, rename, or delete branches. The branch command is used along with the git checkout and git merge commands in order to switch between different branches.

For example: The initial commit is thought of as the master branch. A new branch can be created off of the master using the [ $ git branch <branch name> ] command. New commits can be added to the new branch by using the git checkout command. Later we will see how the two commands come together.

