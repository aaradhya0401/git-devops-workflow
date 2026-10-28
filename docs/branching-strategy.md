# Git Branching Strategy

## Overview

This project follows a simple branching strategy that separates stable code, development work, and individual features.

## Branch Types

### 1. Main Branch

**Name:** `main`

Purpose:
- Contains the stable version of the project.
- Holds reviewed and tested changes.
- Provides a reference for releases.

### 2. Development Branch

**Name:** `dev`

Purpose:
- Integrates completed features.
- Serves as a testing and review area before changes reach `main`.
- Helps coordinate ongoing development.

### 3. Feature Branches

**Naming convention:** `feature/short-description`

Examples:
- `feature/update-project-info`
- `feature/improve-documentation`

Purpose:
- Isolates individual changes.
- Keeps feature work separate from stable code.
- Makes pull requests easier to review.

## Proposed Workflow

1. Start from the `dev` branch.
2. Create a feature branch.
3. Make the required changes.
4. Commit changes using descriptive messages.
5. Push the feature branch to GitHub.
6. Open a pull request into `dev`.
7. Review and merge the changes.
8. Open a pull request from `dev` into `main` when the project is ready for release.
9. Create a version tag for the release.

## Branch Diagram

```text
main
  |
  └── dev
       |
       ├── feature/update-project-info
       |
       └── feature/improve-documentation
```

## Branching Best Practices

- Avoid committing unfinished features directly to `main`.
- Use a separate branch for each feature.
- Keep branch names short and descriptive.
- Merge changes through pull requests.
- Delete merged feature branches when they are no longer needed.
- Synchronize local branches with the remote repository regularly.