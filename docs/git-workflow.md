# Git Workflow Guide

## 1. Introduction

Git is a distributed version control system used to track changes in source code and collaborate with other developers. It helps maintain project history and supports parallel development through branches.

## 2. Initialize a Repository

Create a local Git repository using:

```bash
git init
```

Check the current repository status:

```bash
git status
```

## 3. Configure Git Identity

Set the username and email used for commits:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Replace these example values with your own Git identity if configuration is needed.

## 4. Stage and Commit Changes

Stage the files you want to include:

```bash
git add .
```

Create a commit with a meaningful message:

```bash
git commit -m "Add initial project documentation"
```

A commit records a snapshot of the staged changes.

## 5. Create and Manage Branches

Create a development branch:

```bash
git switch -c dev
```

Create a feature branch from `dev`:

```bash
git switch -c feature/update-project-info
```

After making changes, stage and commit them:

```bash
git add .
git commit -m "Update project information"
```

## 6. Connect to GitHub

Add the GitHub repository as a remote:

```bash
git remote add origin https://github.com/YOUR-USERNAME/git-devops-workflow.git
```

Replace `YOUR-USERNAME` with your GitHub username.

Push the main branch:

```bash
git push -u origin main
```

Push another branch:

```bash
git push -u origin feature/update-project-info
```

## 7. Pull Requests

A pull request allows changes from one branch to be reviewed before merging them into another branch.

Typical workflow:

1. Push the feature branch to GitHub.
2. Open the repository on GitHub.
3. Create a pull request from the feature branch into `dev`.
4. Review the changed files.
5. Merge the pull request.
6. Update your local branches.

## 8. Version Tagging

Create an annotated tag for a release:

```bash
git tag -a v1.0.0 -m "Release version 1.0.0"
```

Push the tag to GitHub:

```bash
git push origin v1.0.0
```

List existing tags:

```bash
git tag
```

Tags provide convenient references to specific versions of a project.

## 9. Useful Commands

| Command | Description |
|---|---|
| `git log --oneline` | View the commit history |
| `git branch` | List local branches |
| `git switch main` | Switch to the main branch |
| `git fetch origin` | Fetch remote changes |
| `git pull` | Fetch and integrate changes |
| `git diff` | View unstaged changes |
| `git tag` | List available tags |

## 10. Best Practices

- Use descriptive commit messages.
- Keep commits focused on related changes.
- Use feature branches for new work.
- Review pull requests before merging.
- Never commit passwords, API keys, or other secrets.
- Keep project documentation updated.
- Use tags to identify stable releases.