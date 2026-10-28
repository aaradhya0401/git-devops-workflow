# Git and DevOps Interview Questions

## 1. What is Git?

Git is a distributed version control system that tracks changes in files and helps developers collaborate on software projects.

## 2. What is GitHub?

GitHub is an online platform for hosting Git repositories and collaborating through features such as pull requests, issues, and code reviews.

## 3. What is a Git repository?

A Git repository stores project files and their version history, including commits, branches, and tags.

## 4. What is the difference between Git and GitHub?

Git is a version control tool that runs locally or on a server. GitHub is a hosting and collaboration platform for Git repositories.

## 5. What is a Git commit?

A commit records a snapshot of staged changes in the repository. It includes a unique identifier, author information, a timestamp, and a commit message.

## 6. What is a Git branch?

A branch is a movable reference to a commit. Branches allow developers to work on different features independently.

## 7. What is the difference between `main` and `dev`?

The `main` branch generally contains stable, release-ready code. The `dev` branch is used to integrate and test ongoing development work.

## 8. What is a feature branch?

A feature branch is created to develop a specific feature or change without directly modifying the main development branch.

## 9. What is a pull request?

A pull request proposes merging changes from one branch into another. It allows team members to review changes and discuss them before merging.

## 10. What is the difference between `git fetch` and `git pull`?

`git fetch` downloads updates from a remote repository without integrating them into the current branch. `git pull` fetches updates and then integrates them into the current branch.

## 11. What is `.gitignore`?

A `.gitignore` file specifies files and directories that Git should normally ignore when detecting untracked changes.

## 12. What is a Git tag?

A Git tag identifies a particular commit, often marking a release such as `v1.0.0`.

## 13. What is the difference between `git add` and `git commit`?

`git add` stages changes for the next commit. `git commit` records the staged changes in the repository history.

## 14. What is a merge conflict?

A merge conflict occurs when Git cannot automatically reconcile changes from different branches. A developer must resolve the conflicting sections before completing the merge.

## 15. What is the purpose of `git status`?

`git status` shows the current branch and reports staged, unstaged, and untracked changes.

## 16. What is the purpose of `git log`?

`git log` displays the repository's commit history.

## 17. What is semantic versioning?

Semantic versioning commonly uses the format `MAJOR.MINOR.PATCH`, such as `1.2.3`. The numbers communicate the type and scale of changes in a release.

## 18. Why should secrets not be committed to Git?

Committing passwords, API keys, or tokens can expose sensitive information to other people. Secrets should be stored securely, and sensitive files should be excluded from version control.

## 19. What is a remote repository?

A remote repository is a version of a repository hosted elsewhere, such as on GitHub, that developers can fetch from and push to.

## 20. Why are meaningful commit messages important?

Meaningful commit messages explain the purpose of a change and make project history easier to understand, review, and maintain.