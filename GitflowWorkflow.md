# Gitflow Workflow
The Gitflow workflow is a brancing model normally used in projects that have a scheduled release cycle. This model is well suited for collaboration and allows development teams to scale.

Instead of starting your project with just a master branch, a development branch is created based on the master branch. Master stores the release history but whenever there are new changes required, a feature branch is created based of the development branch.

Once developers have completed the changes on the feature they are working on, these merges will be merged into the developement branch. After a few features have been merged into development they will be released to the master branch.

```
# Createa new repository
cd [Path]/my_project
git init

# Create the development branch
git branch develop
git push -u origin develop

# Create a feature branch
git checkout develop
git checkout -b feature_branch

# Commit the changes
git commit -m "Description of the commit"

# Merge feature into development branch
git checkout develop
git merge feature_branch

# Create a release branch based of developement after multiple features have been merged
git checkout develop
git checkout -b release/0.1.0

# Merge release branch into master
git checkout master 
git merge release/0.1.0

```

![Gitflow Workflow](/Images/GitflowA.png)

If there are any hotfixes or maintenace needed when using the Gitflow workflow, new hotfix branches are created against master instead of the development branch.

```
# Create a hotfix branch based of master
git checkout master
git checkout -b hotfix_branch

# Merge hotfix branch into master and into development
git checkout master
git merge hotfix_branch
git checkout develop
git merge hotfix_branch
git branch -D hotfix_branch
```
![Gitflow Workflow Hotfix](/Images/GitflowB.png)