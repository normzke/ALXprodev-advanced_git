# ALXprodev-advanced_git

This repository demonstrates advanced Git workflows using GitFlow, Git hooks, and automation for a typical software project.

## Project Structure

- `login-page/` - Contains the login feature and its documentation.
- `signup-page/` - Contains the signup feature and its documentation.
- `.git/hooks/` - Custom Git hooks for automation.

## GitFlow Workflow

This project uses [GitFlow](https://nvie.com/posts/a-successful-git-branching-model/) for managing features, releases, and hotfixes:

- **develop**: Main development branch.
- **feature/**: Feature branches for new features (e.g., `feature/implement-login`).
- **release/**: Release branches for preparing production releases (e.g., `release/1.0.0`).
- **master**: Production-ready code.

## Git Hooks

- **pre-commit**: Ensures every directory contains a README file before allowing a commit.
- **post-merge**: Logs merges into the main branch in `merge.log`.

## How to Use

1. Clone the repository.
2. Use GitFlow commands to manage branches:
   - `git flow feature start <feature-name>`
   - `git flow release start <version>`
   - `git flow release finish <version>`
3. Commit and push changes as needed.

## Requirements
- [Git](https://git-scm.com/)
- [GitFlow](https://github.com/nvie/gitflow)

---

**Author:** normzke 