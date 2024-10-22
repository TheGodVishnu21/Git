# Git Commands

## Configuration

- `git config --global user.name "Your Name"`: Set the name that will be attached to your commits.

- `git config --global user.email "your.email@example.com"`: Set the email that will be attached to your commits.

## Repository Setup

- `git init`: Initialize a new Git repository.

- `git clone <repository-url>`: Clone an existing repository.

## Basic Snapshotting

- `git add <file>`: Add a file to the staging area.

- `git commit -m "commit message"`: Commit the staged changes to the repository.

- `git status`: Show the status of changes as untracked, modified, or staged.

- `git log`: Show the commit history.

## Branching and Merging

- `git branch`: List all branches.

- `git branch <branch-name>`: Create a new branch.

- `git checkout <branch-name>`: Switch to a branch.

- `git merge <branch-name>`: Merge a branch into the current branch.

## Remote Repositories

- `git remote add origin <repository-url>`: Add a remote repository.

- `git push -u origin <branch-name>`: Push changes to a remote repository.

- `git pull`: Fetch and merge changes from the remote repository.

## Undoing Changes

- `git reset --hard <commit>`: Reset the index and working directory to a specific commit.

- `git revert <commit>`: Create a new commit that undoes the changes from a previous commit.

## Viewing Changes

- `git diff`: Show changes between commits, commit and working tree, etc.

- `git show <commit>`: Show various types of objects.

## Stashing

- `git stash`: Stash the changes in a dirty working directory.

- `git stash apply`: Apply the stashed changes.

## Tagging

- `git tag <tag-name>`: Create a new tag.

- `git push origin <tag-name>`: Push a tag to the remote repository.

## Collaboration

- `git fetch`: Download objects and refs from another repository.

- `git rebase <branch>`: Reapply commits on top of another base tip.

For more detailed information, refer to the [official Git documentation](https://git-scm.com/doc).
