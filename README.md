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

### Configuring Git

To configure Git with your name and email, use the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

### Checking Git Version

To check the version of Git installed on your system, run:

```bash
git --version
```

### Initializing a New Git Repository

To initialize a new Git repository, navigate to your project directory and run:

```bash
git init
```

### Cloning an Existing Repository

To clone an existing repository, use the following command:

```bash
git clone <repository-url>
```

### Adding Files to the Staging Area

To add files to the staging area for the next commit, use:

```bash
git add <file1> <file2> ...
```

### Committing Changes

To commit changes to the repository, use:

```bash
git commit -m "commit message"
```

### Creating and Switching Branches

To create a new branch, use:

```bash
git branch <branch-name>
```

To switch to a different branch, use:

```bash
git checkout <branch-name>
```

### Merging Branches

To merge changes from one branch into another, use:

```bash
git merge <branch-name>
```

### Pushing Changes

To push changes to a remote repository, use:

```bash
git push
```

### Pulling Changes

To pull changes from a remote repository, use:

```bash
git pull
```

### Viewing Commit History

To view the commit history, use:

```bash
git log
```

### Checking Working Tree Status

To view the status of the working tree, use:

```bash
git status
```

### Deleting a Branch

To delete a branch, use:

```bash
git branch -d <branch-name>
```

## Advanced Git Commands

This section covers more advanced Git commands for in-depth repository management.

### Amending Commits

To amend commits and make additional changes, use:

```bash
git commit --amend
```

### Interactive Rebase

To perform an interactive rebase, use:

```bash
git rebase -i <commit>
```

### Stashing Changes

To stash changes in a dirty working directory, use:

```bash
git stash
```

### Applying Specific Changes

To apply specific changes from one branch to another, use:

```bash
git cherry-pick <commit-hash>
```

### Checking Out Remote Branch

To check out a remote branch, use:

```bash
git checkout -b <branch-name> origin/<branch-name>
```

### Removing Untracked Files

To remove untracked files from the working directory, use:

```bash
git clean -fd
```

### Checking Out a Specific Commit

To check out a specific commit, use:

```bash
git checkout <commit-hash>
```

### Tagging Commits

To create, list, or delete tags, use:

```bash
git tag <tag-name>
```

### Using Git Bisect

To automate the process of finding the commit that introduced a bug, use:

```bash
git bisect start
git bisect bad
git bisect good <good-commit>
```

### Configuring Git Aliases

To configure Git aliases for commonly used commands, use:

```bash
git config --global alias.<alias-name> <original-command>
```

### Viewing Changes Between Branches

To show changes between branches, use:

```bash
git diff <branch1>..<branch2>
```

## Conclusion

This comprehensive guide covers a wide range of Git and GitHub commands, from basic version control to advanced repository management. Use these commands to streamline your Git workflow and effectively collaborate with others on your projects.

**Note:** This is a living document that will be updated with new commands and features. Stay tuned for more updates!