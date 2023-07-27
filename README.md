# Version Control with Git

## Introduction

Version control is a crucial aspect of modern software development that allows developers to track changes, collaborate with others, and manage code effectively. Git is one of the most popular version control systems used by developers worldwide. This guide provides an introduction to Git and its fundamental concepts.

## What is Git?

Git is a distributed version control system that was created by Linus Torvalds in 2005. It is designed to handle everything from small to very large projects with speed and efficiency. Git allows multiple developers to work on the same codebase simultaneously without interfering with each other's changes.

## Basic Concepts

### Repositories

In Git, a repository (repo) is a collection of files and their revision history. It can exist locally on a developer's machine or on a remote server, such as GitHub, GitLab, or Bitbucket.

### Commits

A commit is a snapshot of the changes made to the files in a repository at a specific point in time. Each commit has a unique identifier (SHA-1 hash) that helps track and reference it.

### Branches

Branches are separate lines of development within a repository. They allow developers to work on new features or bug fixes independently without affecting the main codebase. Branches can be merged back into the main branch when the changes are ready.

### Remote Repositories

Remote repositories are versions of your project that are hosted on servers like GitHub. They enable collaboration between developers by allowing them to push and pull changes to and from the central repository.

### Working Directory, Staging Area, and Repository

Git has three main parts: the working directory, the staging area (index), and the repository. The working directory is where you make changes to your files. The staging area is where you prepare changes to be committed, and the repository is where all the committed snapshots are stored.

## Basic Git Commands

Here are some essential Git commands to get started:

1. `git init`: Initializes a new Git repository in the current directory.

2. `git clone <repository_url>`: Creates a local copy of a remote repository on your machine.

3. `git add <file>`: Adds changes in a file to the staging area.

4. `git commit -m "Commit message"`: Commits the changes in the staging area to the repository with a descriptive message.

5. `git status`: Shows the current state of your working directory and the files that are staged or not.

6. `git pull`: Fetches and merges changes from a remote repository into your current branch.

7. `git push`: Sends committed changes from your local repository to a remote repository.

8. `git branch`: Lists all branches in the repository.

9. `git checkout <branch_name>`: Switches to the specified branch.

## Using Git to Collaborate
We will follow the code review approach here - every changes made to the system should be carefully reviewed and tested to ensure quality and prevent potential flaws :)

### Steps
1. Create a new branch out of `main` branch via `git checkout -b <branch_name>` and start coding!
  
2. Once you're done, push your branch to remote repository via `git push origin <branch_name>`

3. Open the the repository > Pull Requests > New Pull Requests

4. Ask someone to review your code

5. After the reviewer has approved your Pull Request, merge!!!!
