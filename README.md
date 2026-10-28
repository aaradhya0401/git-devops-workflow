# Git DevOps Workflow

## Project Overview

This project demonstrates Git version control best practices commonly used in DevOps workflows. It covers repository management, branching strategies, feature development, pull requests, commit conventions, and version tagging.

## Objectives

- Understand Git repository initialization and remote configuration.
- Use `main`, `dev`, and feature branches.
- Follow a structured commit workflow.
- Create and merge pull requests using GitHub.
- Maintain project documentation using Markdown.
- Use `.gitignore` to exclude unnecessary files.
- Create Git tags to mark project releases.

## Technology Used

- Git
- GitHub
- Visual Studio Code
- Markdown

## Project Structure

```text
git-devops-workflow/
├── docs/
│   ├── branching-strategy.md
│   ├── git-workflow.md
│   └── interview-questions.md
├── screenshots/
├── src/
│   └── app-info.txt
├── .gitignore
└── README.md
```

## Git Workflow

1. Initialize a local Git repository.
2. Create and maintain the `main` and `dev` branches.
3. Create feature branches for individual changes.
4. Commit changes with meaningful messages.
5. Push branches to GitHub.
6. Open pull requests and merge reviewed changes.
7. Tag stable releases using semantic versioning.

## Useful Git Commands

| Command | Purpose |
|---|---|
| `git init` | Initialize a repository |
| `git status` | Check the working tree |
| `git add .` | Stage changes |
| `git commit -m "message"` | Create a commit |
| `git branch` | List branches |
| `git switch -c dev` | Create and switch to a branch |
| `git push -u origin main` | Push the main branch |
| `git tag v1.0.0` | Create a version tag |
| `git push origin v1.0.0` | Push a tag to GitHub |

## Documentation

- [Git Workflow](docs/git-workflow.md)
- [Branching Strategy](docs/branching-strategy.md)
- [Git Interview Questions](docs/interview-questions.md)

## Expected Outcome

The project demonstrates a structured Git workflow with documented branching practices, pull requests, version tagging, and collaborative version control.

## Author

Created as part of the Elevate Labs DevOps Internship — Task 4.