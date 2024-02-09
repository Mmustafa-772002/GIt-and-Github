# Git and GitHub Commands

This repository provides a comprehensive guide to essential Git and GitHub commands for effective version control.

## Introduction

### Git
Git is a distributed version control system that facilitates collaboration on software development projects. Developed by Linus Torvalds, Git allows multiple developers to work on a project simultaneously, tracking changes and managing different versions of the codebase.

#### Key Concepts:
- **Repository (Repo):** A collection of files and folders, along with the history of changes, stored on a version control system.
- **Commit:** A snapshot of changes made to the repository at a specific point in time.
- **Branch:** A parallel line of development that enables isolation of features or fixes.
- **Merge:** Combining changes from one branch into another.
- **Pull Request (PR):** A proposed change submitted by a developer for review and merging into the main branch.

### GitHub
GitHub is a web-based platform that complements Git, providing hosting for Git repositories and additional collaboration features. It enhances the Git workflow by offering tools for code review, issue tracking, and project management.

#### Key Features:
- **Collaboration:** Multiple developers can work on the same project, contributing code and managing changes.
- **Issues:** Track and discuss tasks, enhancements, bugs, and other topics related to a repository.
- **Pull Requests:** Propose changes, review code, and discuss modifications before merging.
- **Actions:** Automate workflows by creating custom CI/CD pipelines for testing, building, and deploying code.
- **Wikis:** Collaboratively document projects using built-in wikis.
- **Projects:** Manage tasks and prioritize work using Kanban-style project boards.

## Git Basics

- `git add`: Add files to the staging area for the next commit.
- `git bisect`: Automate the process of finding the commit that introduced a bug.
- `git branch`: Create, list, or delete branches.
- `git cat-file`: Display content or type information about repository objects.
- `git checkout`: Switch branches or restore working tree files.
- `git cherry-pick`: Apply specific changes from one branch to another.
- `git clean`: Remove untracked files from the working directory.
- `git clone`: Clone a repository into a new directory.
- `git commit`: Record changes to the repository.
- `git describe`: Display the most recent tag that is reachable from a commit.
- `git diff`: Show changes between commits, commit and working tree, etc.
- `git fetch`: Download objects and refs from another repository.
- `git grep`: Print lines matching a pattern.
- `git init`: Create an empty Git repository or reinitialize an existing one.
- `git log`: Display the commit logs.
- `git merge`: Join two or more development histories together.
- `git name-rev`: Find symbolic names for given revisions.
- `git pull`: Fetch from and integrate with another repository or a local branch.
- `git push`: Update remote refs along with associated objects.
- `git reflog`: Manage reflog information.
- `git remote`: Manage set of tracked repositories.
- `git revert`: Revert existing commits.
- `git show`: Show various types of objects.
- `git status`: Show the working tree status.
- `git stash`: Stash the changes in a dirty working directory.
- `git symbolic-ref`: Read or modify symbolic references.
- `git tag`: Create, list, delete, or verify a tag object.

## Advanced Git Commands

- `git am`: Apply a series of patches from a mailbox.
- `git apply`: Apply changes from a patch or a file.
- `git applymbox`: Apply changes from an mbox (mailbox) file.
- `git applypatch`: Apply changes from a patch file.
- `git archive`: Create an archive of files from a named tree.
- `git bisect`: Use binary search to find the commit that introduced a bug.
- `git cat-file`: Provide content or type information for object.
- `git check-attr`: Display gitattributes information.
- `git check-ignore`: Debug gitignore / exclude files.
- `git check-mailmap`: Show canonical names and email addresses of contacts.
- `git check-ref-format`: Ensures that a reference name is well formed.
- `git clean`: Remove untracked files from the working tree.
- `git commit`: Record changes to the repository.
- `git commit-tree`: Create a new commit object from the provided tree object.
- `git count-objects`: Count unpacked number of objects and their disk consumption.
- `git daemon`: A really simple server for Git repositories.
- `git diff`: Show changes between commits, commit and working tree, etc.
- `git diff-files`: Compare files in the working tree and the index.
- `git diff-index`: Compare a tree to the working tree or index.
- `git diff-tree`: Compares the content and mode of blobs found via two tree objects.
- `git fetch`: Download objects and refs from another repository.
- `git for-each-ref`: Output information on each ref.
- `git fsck`: Verifies the connectivity and validity of the objects in the database.
- `git gc`: Cleanup unnecessary files and optimize the local repository.
- `git grep`: Print lines matching a pattern.
- `git hash-object`: Compute the object ID value for an object.
- `git instaweb`: Instantly browse your working repository in gitweb.
- `git ls-files`: Show information about files in the index and the working tree.
- `git ls-remote`: Show references in a remote repository.
- `git ls-tree`: List a tree object.
- `git merge-base`: Find the common ancestor of two or more branches.
- `git pack-objects`: Create a packed archive of objects.
- `git prune`: Prune all unreachable objects from the object database.
- `git prune-packed`: Remove extra objects that are already in pack files.
- `git push`: Update remote refs along with associated objects.
- `git read-tree`: Reads tree information into the index.
- `git reflog`: Manage reflog information.
- `git remote`: Manage set of tracked repositories.
- `git revert`: Revert existing commits.
- `git rev-list`: Lists commit objects in reverse chronological order.
- `git rev-parse`: Parse revision (e.g., branch name) and display its full SHA-1.
- `git show`: Show various types of objects.
- `git show-ref`: List references in a repository.
- `git update-index`: Register file contents in the working tree to the index.
- `git update-ref`: Update the object name stored in a reference.
- `git verify-pack`: Verify the connectivity and validity of the objects in the database.
- `git write-tree`: Create a new tree object from the current index.

This comprehensive guide covers a wide range of Git and GitHub commands, from basic version control to advanced repository management. Use these commands to streamline your Git workflow and effectively collaborate with others on your projects.