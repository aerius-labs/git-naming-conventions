# Git Commit, Branch, and Repository Naming Conventions

This document outlines the commit, branch, and repository naming conventions we follow in our projects.

## Commit Naming Convention

When committing changes, we use the following format:

```<type>: <description>```


Where `<type>` is one of the following:

- `fix`: A bug fix
- `feat`: A new feature
- `test`: Changes related to tests
- `chore`: Other kinds of work not related to production code

And `<description>` is a brief description of the changes made.

### Examples:

- `fix: corrected the login API endpoint`
- `feat: added new user registration feature`
- `test: added unit tests for user registration`
- `chore: updated project documentation`

## Branch Naming Convention

When creating a new branch, we use the following format:

`<type>/<description>`


Where `<type>` is one of the following:

- `fix`
- `feat`
- `test`
- `chore`

And `<description>` is a brief description of the changes to be made in the branch, separated by hyphens. All letters should be in lowercase.

### Examples:

- `fix/login-api-endpoint`
- `feat/user-registration`
- `test/user-registration`
- `chore/update-documentation`

## Repository Naming Convention

When naming a repository, we use the following format:

`<repo-name>`

Where `<repo-name>` is the name of the repository, separated by hyphens. All letters should be in lowercase.

### Examples:
- `book-store`

Remember, the goal of these conventions is to make the commit, branch, and repository names more readable and understandable. It's important that everyone on the team follows these conventions for consistency and clarity.




