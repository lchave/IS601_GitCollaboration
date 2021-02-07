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
