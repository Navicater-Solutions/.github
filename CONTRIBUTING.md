# Contributing to Navicater

## Table of Contents

- [Getting Started](#getting-started)
- [Branching Guidelines](#branching-guidelines)
- [Naming Conventions](#naming-conventions)
- [Creating a Pull Request](#creating-a-pull-request)

## Getting Started

1. **Clone Repo**: Clone the repository to your local machine.

   ```sh
   git clone url
   ```

## Branching Guidelines


1. **Create a New Branch**: Create a new branch for each feature or bug fix you are working on. Use descriptive names for your branches.

   ```sh
   git checkout -b feature/your-feature-name	
   ```

## Naming Conventions

- **Branch Names**:

  - Use `feature/` prefix for new features (e.g., `feature/add-user-authentication`).
  - Use `bugfix/` prefix for bug fixes (e.g., `bugfix/fix-login-issue`).
  - Use `hotfix/` prefix for urgent fixes (e.g., `hotfix/critical-security-update`).
  - Use `chore/` prefix for non-functional changes (e.g., `chore/update-dependencies`).
  
- **Commit Messages**:

  - Use the imperative mood (e.g., "Add", "Fix", "Update").
  - Include a brief description of the change.
  - Reference any relevant issue numbers (e.g., "Fix issue #123").

## Creating a Pull Request

1. **Push Your Branch**: Push your branch code to the repository.
	
 ```sh
 git push origin feature/your-feature-name
 ```
 
2. **Create a Pull Request**

Create a pull request to the `main` branch and wait for approval to merge.
