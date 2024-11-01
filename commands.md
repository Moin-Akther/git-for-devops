# Git Commands Guide

## Project Setup

Create a new directory and initialize a Git repository:

- `mkdir git-for-devops`
- `cd git-for-devops/`
- `git init`

## Basic File Operations

Create files:

- `vim hello-dosto.txt`
- `touch nibba.txt nibbi.txt`
- `ls -ltrh`

## Staging and Unstaging Files

Check the status of the repository:

- `git status`

Add files to the staging area:

- `git add hello-dosto.txt nibba.txt nibbi.txt`

Stage all files:

- `git add .`

Unstage files:

- `git rm --cached hello-dosto.txt nibba.txt nibbi.txt`

## Making a Commit

Commit changes with a message:

- `git commit -m "adding hello nibba and nibbi"`

## Removing Files

Remove a file:

- `rm nibbi.txt`

Restore a removed file (if it was staged):

- `git restore nibbi.txt`

## Configuring User Information

Set the global username and email for Git:

- `git config --global user.name "moin.akther"`
- `git config --global user.email "moin.akther@gmail.com"`

## Working with Branches

List branches:

- `git branch`

Create and switch to a new branch:

- `git checkout -b dev`

Switch to an existing branch:

- `git checkout master`

## Viewing Commit History

Show the commit log:

- `git log`

Show a condensed version of the log (one-line format):

- `git log --oneline`

## Useful Commands

Display command history:

- `history`

---

This markdown format removes any additional formatting that would cause "copy code" buttons to appear in many renderers.
