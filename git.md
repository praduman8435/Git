# Table of Contents
- [Introduction](#introduction)
- [Basic Commands](#basic-commands)
- [Branching](#branching)
- [Merging](#merging)
- [Remote Repositories](#remote-repositories)
- [Undoing Changes](#undoing-changes)
- [Collaboration](#collaboration)

## Introduction

Git is a distributed version control system that allows multiple developers to work on a project simultaneously. It tracks changes to files and allows you to revert back to a previous version if needed.

## Basic Commands

Here are some essential Git commands:

- `git init`: Initializes a new Git repository in the current directory.
- `git add <file>`: Adds a file to the staging area.
- `git commit -m "<message>"`: Commits the staged changes to the repository with a descriptive message.
- `git status`: Displays the status of the repository, including changes and branch information.
- `git log`: Shows a log of all commits in reverse chronological order.

## Branching

Git provides a powerful branching mechanism that allows you to work on separate lines of development. Here are some useful commands:

- `git branch`: Lists all branches in the repository.
- `git branch <branch-name>`: Creates a new branch with the specified name.
- `git checkout <branch-name>`: Switches to the specified branch.
- `git merge <branch-name>`: Merges changes from the specified branch into the current branch.

## Merging

Merging is the process of combining changes from different branches. Git offers various merging strategies. Some common commands include:

- `git merge <branch-name>`: Merges changes from the specified branch into the current branch.
- `git merge --abort`: Aborts a merge in progress.
- `git merge --no-ff <branch-name>`: Performs a non-fast-forward merge, preserving the branch history.

## Remote Repositories

Git allows you to collaborate with others by managing remote repositories. Here are some commands for working with remote repositories:

- `git remote add <name> <url>`: Adds a remote repository with the given name and URL.
- `git remote -v`: Lists all remote repositories and their URLs.
- `git push <remote> <branch-name>`: Pushes the specified branch to the remote repository.
- `git pull <remote> <branch-name>`: Fetches changes from the remote repository and merges them into the current branch.

## Undoing Changes

Git provides several ways to undo or revert changes. Here are some commonly used commands:

- `git checkout -- <file>`: Discards changes made to a file and reverts it to the last committed version.
- `git reset <commit>`: Resets the repository to a specified commit, discarding subsequent commits.
- `git revert <commit>`: Creates a new commit that undoes the changes made in the specified commit.

## Collaboration

Git enables seamless collaboration with other developers. Here are some collaborative commands:

- `git clone <url>`: Creates a copy of a remote repository on your local machine.
- `git fetch`: Retrieves the latest changes from a remote repository without merging them.
- `git pull`: Fetches and merges changes from the remote repository into the current branch.
- `git push`: Pushes your local changes to the remote repository.

This guide covers the basic Git concepts and commands. Feel free to explore additional features and advanced Git workflows to enhance your version control skills.
