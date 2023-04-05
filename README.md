# GitHub and Version Control

## What is Git?

* Git is a version control system
* Most Popular VCS (Apache)
* Open Source
* Provides version history
* Good for working in teams
* Distribution is good in the sense where local copies and remote copies can be provided.
* Commands in Git are run through Git Bash (cmd line ui)
* "Repository" is a folder/directory controlled by Git

## What is GitHub?

* GitHub is a remote repository hosting service
  * It lets developers store, manage and share code "repos" online
    * Allows for developers to work collaboratively on code
* GitHub is based on Git, which is a distributed VCS.
  * Type of VCS that allows for multiple copies of a repo to be made and distributed over different locations
  * Without relying on a single repo, each copy of this repo has a full history of changes, which are then shared and merged between the different copies.
  * Advantages of this are that users can work on their own copy of the repo without being connected to a central server, and the changes made to it can be easily shared and merged.

## What is the difference between the two?

Git is a version control system that lets you monitor changes

## Benefits of version control :

* Remembers each version update
  * keeps a history between updates (changes made)
  * Rollback to previous version allowed
* Copies made on a local system can be easily synchronised
  * allows for efficient collaboration and version control of files
* Collaboration made easy
  * changes can be overlapping
    * allows members to work on same file simultaneously without conflicts
    * simultaneous updates, merging is also supported

## Main Git Commands
* `git init` - initialises new git repo
* `git add .` - adds changes made to files in repository 
* `git commit -m "####"` commits changes to local repository with a commit message describing changes made
* `git push` - Pushes changes committed from local repository to GitHub ( remote repo )
* `git pull` - Pulls changes from GitHub to local repository
* `git status` - status of repository, shows changes made but still not yet committed
* `git log` - shows all commits made in repository
* `cd filename` - change directory to specific folder
* `cd ..` - move current folder up by one
* `ls` - list contents of folder
* `git merge <source_branch> ` - combine changes from one branch into another branch.

## What are branches?
A branch represents an independent line of development, it is a way to work on different versions of a repo at the same time.
When a new branch is made, you are essentially creating a copy of the entire repository, 
including the files and commit history. 
Changes can then be made to the copy of the repository without affecting the original. 
You can create as many branches as you need, and each branch can have its own set of changes and commit history.

**Advantages of branches**:
* Collaboration
* Feature development
* Experimentation
* Versioning

## What is git merge?
We had just seen what branches were and the advantages of them.

Now we are talking about git merge, and this is a way to combine two or more branches.

When you merge two branches, 
Git combines the changes made in both branches into a new commit that has two parent commits, one from each bra nch.

Merge is a common way to include changes in one branch to another, and to put it into context:  
when working on a new feature in a separate branch and now you must incorporate those changes into the main branch, 
you can merge the feature branch into the main branch.

The main command which is used is one we have seen in the Main Git Commands section and it is `git merge <source_branch>`.
`source_branch` is the branch that contains the changes you want to merge into the current branch(which is the branch you are in fact targeting)

## What is a pull request?

Pull request is a feature which lets developers propose changes to a project, 
and the changes that were made can now be merged into the main branch, but of course a request must be sent first.

When a pull request is created, the **maintainers** of the project review and will eventually merge the changes.

**Maintainers** - individuals responsible for managing and maintaining the project's codebase, documentation, issues, and other related aspects

Pull requests are used for a variety of purposes, 
such as fixing a bug, 
adding a new feature, 
or improving the documentation.