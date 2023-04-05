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

## What are branches? What is merging/git merge? What is Pull Request?

* Branches
  * 