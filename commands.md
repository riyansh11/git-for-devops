Git Commands Reference

This document contains commonly used Git commands, organized by topic for easy understanding.

1. Repository Setup

Create a directory and move into it
mkdir mahesh_repo
cd mahesh_repo/

Configure Git user details (Global)
git config --global user.name "Riyansh11"
git config --global user.email "riyanshgaikwad7@gmail.com
"

Initialize a new Git repository
git init

2. Checking Repository Status

Check the current state of the working directory and staging area
git status

3. Working with Files

Create a new file
touch mahesh.txt

List files in the directory
ls

Remove a file from the working directory
rm mahesh.txt

4. Staging Area (Index)

Add a file to the staging area
git add mahesh.txt

Remove a file from the staging area (keep it in working directory)
git rm --cached mahesh.txt

5. Committing Changes

Commit staged changes with a message
git commit -m "New File"

Incorrect usage (not recommended)
git commit mahesh.txt

6. Restoring Files

Restore a deleted or modified file from the last commit
git restore mahesh.txt

7. Viewing Commit History

View full commit history
git log

View commit history in one-line format
git log --oneline

8. Summary

git status → shows file states
git add → stages files
git commit → saves changes
git restore → recovers files
git log → shows commit history
